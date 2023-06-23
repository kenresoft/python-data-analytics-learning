```python
today = 'Saturday'
```


```python
type(today)
```




    str




```python

```


```python
# Variables declaration
age = 15.0
name = 'Kenneth'
```


```python
type(age)
```




    float




```python
type(name)
```




    str




```python
age = str(age)
```


```python
class_motto = 'I must finish this course, "so help me God"'
```


```python
class_motto 
```




    'I must finish this course, "so help me God"'




```python
another_pun = "The first time I got a universal remote control, I thought to myself \"This changes everything\"."
```


```python
another_pun
```




    'The first time I got a universal remote control, I thought to myself "This changes everything".'




```python

```


```python
class_name = 'cohort 2'
```


```python
class_name2 = "cohort3"
```


```python
class_name 
```




    'cohort 2'




```python
class_name2
```




    'cohort3'




```python

```


```python
sentence = "I am very smart, 'yes it\'s true'"
```


```python
sentence
```




    "I am very smart, 'yes it's true'"




```python
sentence = ''' 'I am very smart, "yes it's true"' '''
```


```python
sentence
```




    ' \'I am very smart, "yes it\'s true"\' '




```python
sentence = '''
'I am very smart, "yes it's true"'
'''
```


```python
sentence
```




    '\n\'I am very smart, "yes it\'s true"\'\n'




```python
# We use print to remove the escape characters. 
print(sentence)
```

    
    'I am very smart, "yes it's true"'
    
    


```python
len(sentence)
```




    36




```python
name = 'Adaeze'
```


```python
list(name)
```




    ['A', 'd', 'a', 'e', 'z', 'e']




```python
name[0]
```




    'A'




```python
name[2]
```




    'a'




```python
name[7]
```


    ---------------------------------------------------------------------------

    IndexError                                Traceback (most recent call last)

    Cell In[29], line 1
    ----> 1 name[7]
    

    IndexError: string index out of range



```python
# always add 1 to the last index.
# in this case, for 'a' which has index of 2, we do 2 + 1 = 3
name[0:3]
```




    'Ada'




```python
name[1:4]
```




    'dae'




```python
school = 'Akwakuma Girls'
```


```python
school[9:14]
```




    'Girls'




```python
for x in school:
    print(x + ' : ' + str(school.index(x)))
```

    A : 0
    k : 1
    w : 2
    a : 3
    k : 1
    u : 5
    m : 6
    a : 3
      : 8
    G : 9
    i : 10
    r : 11
    l : 12
    s : 13
    


```python

```

## String Concatenation


```python
firstname = 'Kenneth'
lastname = 'Amadi'
```


```python
fullname = firstname + ' ' + lastname
```


```python
fullname
```




    'Kenneth Amadi'




```python

```


```python
name = 'kenneth'
```


```python
name2 = 'kachukwuside'
```


```python
name.upper()
```




    'KENNETH'




```python
name2.upper()
```




    'KACHUKWUSIDE'




```python
name.lower()
```




    'kenneth'




```python
name3 = name
```


```python
name3.capitalize()
```




    'Kenneth'




```python

```


```python
name3 = input('Enter your email address: ')
```

    Enter your email address: AMADIKENNETH8@GMAIL.COM 
    


```python
name3.lower()
```




    'amadikenneth8@gmail.com '




```python

```


```python
name = 'Kenneth Amadi'
```


```python
name
```




    'Kenneth Amadi'




```python
name.replace('Kenneth', 'Kenresoft')
```




    'Kenresoft Amadi'




```python
day = 'Wednesday'
```


```python
day = day.replace('Wednes', 'Fri')
```


```python
day
```




    'Friday'




```python
list(day)
```




    ['F', 'r', 'i', 'd', 'a', 'y']




```python
name.split()
```




    ['Kenneth', 'Amadi']




```python

```
