# EXERCISE ONE: FIRST STEPS IN PYTHON

* **Name:** Amadi Kenneth Kachukwuside
* **Class:** Introduction to programming. 
* **Group:** B

---
## Question 1
--- 
> In 2015, a farmer made sales of 120,000 naira. This sales was from cassava which had 70,000
naira, maize which has 25,000 and plantain. if he invested 90000 and maize accounted for 30%
percent of his profit. Using multistep approach write a python code that answers the following
questions.

> **a.** What is the overall profit?

> **b.** What is the profit of cassava and plaintain?

> **c.** With a tax of 5% on the sales what is the net profit?

## Solutions 

##### Information Provided


```python
# Declaring our variables

total_sales = 120000
sales_from_cassava = 70000
sales_from_maize = 25000

investment = 90000
tax_rate = 0.05
profit_rate_from_maize = 0.3
```


```python
# Finding the unknown sales from plantain
sales_from_plantain = total_sales - (sales_from_cassava + sales_from_maize)
```


```python
sales_from_plantain
```




    25000



## Question 1(a) : 
##### What is the overall profit?


```python
# To find overal profit
overal_profit = total_sales - investment
```


```python
overal_profit
```




    30000



## Question 1(b) : 
##### What is the profit of cassava and plaintain?


```python
# Calculating profit per food stuff sold
profit_from_maize = profit_rate_from_maize * overal_profit
```


```python
profit_from_maize
```




    9000.0




```python
# Calculating for profit from cassava and plantain
profit_from_cassava_and_plantain = overal_profit - profit_from_maize
```


```python
profit_from_cassava_and_plantain
```




    21000.0



## Question 1(c) : 
##### With a tax of 5% on the sales what is the net profit?


```python
# Calculating for tax on the sales made
tax_on_sales = tax_rate * total_sales
```


```python
tax_on_sales
```




    6000.0




```python
# Finding the net profit made by the farmer
net_profit = overal_profit - tax_on_sales
```


```python
net_profit
```




    24000.0



---
## Question 2
--- 
> What is the output of the following code?(type them into jupyter line by line)

> `var1 = 1`

> `var2 = 2`

> `var3 = "3"`

> `print(var1 + var2 + var3)`

> if there is any error explain the reason for it.

## Solutions 


```python
var1 = 1
```


```python
var2 = 2
```


```python
var3 = "3"
```


```python
print(var1 + var2 + var3)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[17], line 1
    ----> 1 print(var1 + var2 + var3)
    

    TypeError: unsupported operand type(s) for +: 'int' and 'str'


### Explanation and solution to the error

This error occurs because the print() function expects the arguments to be of the same type. 

In this case, `var1` and `var2` are integers, but `var3` is a string. 

To fix the error, you would need to change the type of `var3` to an integer.


```python
var3 = 3
```


```python
print(var1 + var2 + var3)
```

    6
    

---
## Question 3
--- 
> Run the code below

> `This is a comment`

> `written in`

> `more than just one line`

> `print(' The above is a multiline comment')`

> did you encounter error? use multiline comment and comment out the letters in bold.

## Solutions 


```python
This is a comment

written in

more than just one line

print(' The above is a multiline comment')
```


      Cell In[20], line 1
        This is a comment
                  ^
    SyntaxError: invalid syntax
    


The code will encounter a syntax error. 
This is because, the `This is a comment written in more than just one line` statement is not valid Python code. 


```python
'''This is a comment

written in

more than just one line'''

print(' The above is a multiline comment')
```

     The above is a multiline comment
    

---
## Question 4
--- 
> Declare the following variables

> `height = 34`

> `men = 20`

> `age = 16`

> `gender = 'males'`
##### 
> Answer the following questions with python logical and conditional operators

> **a.** Are men less than 20 and age equal to 15?

> **b.** Is gender equal to 'Females' and men greater 30

> **c.** Height is equal to 34 or age less than 10

## Solutions 


```python
height = 34
```


```python
men = 20
```


```python
age = 16
```


```python
gender = 'males'
```


```python
men < 20 and age == 15
```




    False




```python
gender == 'Females' and men > 30
```




    False




```python
height == 34 or age < 10
```




    True



### The end


```python

```

