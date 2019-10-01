Python cheats
===============================

#### The Zen of Python, by Tim Peters

```
>>> import this

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!

```


List
----
```
>>> class : <class 'list'>
```
```
methods : ['__add__', '__class__', '__contains__', '__delattr__', '__delitem__', 
	'__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', 
	'__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__iter__', '__le__', '__len__',
 	'__lt__', '__mul__', '__ne__', '__new__', '__reduce__', 
	'__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__',
 	'__setitem__', '__sizeof__', '__str__', '__subclasshook__', 
	'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert',
 	'pop', 'remove', 'reverse', 'sort']
```
```
>>> list = list[start : end : ±step]
```
```
Most repative number in list :

>>> list = [1,2,3,1,4,2,1,5,6,1]
>>> print(max(set(list), key=list.count))
```
```
Remove duplicate from list :

>>> list = [1,2,3,1,4,2,1,5,6,1]
>>> print(list(set(list)))
```
```
List count() and index()

>>> list = ['pikachu', 'meowth', 'mew', 'charizard', 'eevee', 'meowth', 'charizard'] 
>>> list.count('pikachu')
1

>>> list.index('charizard')
3
>>> list.index('charizard', 4)  # Find next charizard starting a position 4
6
```

```
Create a list of 2-tuples like (number, square)
 
>>> [(x, x**2) for x in range(6)]
[(0, 0), (1, 1), (2, 4), (3, 9), (4, 16), (5, 25)]

Listcomp combines

>>> [(i,j) for i in range(3) for j in range(i+i)] 
[(1, 0), (1, 1), (2, 0), (2, 1), (2, 2), (2, 3)]

>>> # It’s equivalent to
>>> list = []
>>> for i in range(3): 
...:     for j in range(i+i): 
   ...:         list.append((i,j))   
>>> list
[(1, 0), (1, 1), (2, 0), (2, 1), (2, 2), (2, 3)]
```
String
----

```
Find number in string

>>> word = 'My ages is 24'
>>> [int(i) for i in word.split() if i.isdigit()] 
[24]
```

Numbers
----

```
>>>  round(1.4)
1
>>>  from math import ceil
>>>  ceil(1.4)
2
```
```
Swipe numbers

>>> a,b = 1,2 # a=1, b=2
>>> a,b = b,a # a=2, b=1
```
