

```python
a = "hobby"
a.count('b')
```




    2




```python
a = "Python is the best choice"
a.find('b')
```




    14




```python
a.find('k')
```




    -1




```python
a = "There are some cute babies"
a.index('i')
```




    23




```python
a.index('a')
```




    6




```python
a.index('x')
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    <ipython-input-6-51f0d5bb66b2> in <module>()
    ----> 1 a.index('x')
    

    ValueError: substring not found



```python
a = ","
a.join('abcd')
```




    'a,b,c,d'




```python
a = "hi"
a.upper()
```




    'HI'




```python
a = "HI"
a.lower()
```




    'hi'




```python
a = " hi "
a.lstrip()
```




    'hi '




```python
a = " hi "
a.rstrip()
```




    ' hi'




```python
a = " hi "
a.strip()
```




    'hi'




```python
a = "Some babies are cute"
a.split()
```




    ['Some', 'babies', 'are', 'cute']




```python
a = "a:b:c:d"
a.split(':')
```




    ['a', 'b', 'c', 'd']


