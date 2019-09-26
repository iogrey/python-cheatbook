Python cheats
===============================

#### The Zen of Python, by Tim Peters 

**Beautiful is better than ugly.

Explicit is better than implicit.

Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.**
*Readability counts.*
**Special cases aren't special enough to break the rules.
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
Namespaces are one honking great idea -- let's do more of those!**



List
----
```
class : <class 'list'>
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
list = list[start : end : ±step]
```
```
Most repative number in list :

list = [1,2,3,1,4,2,1,5,6,1]
print(max(set(list), key=list.count))
```
```
Remove duplicate from list :

list = [1,2,3,1,4,2,1,5,6,1]
print(list(set(list)))
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
