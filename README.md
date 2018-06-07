# datatypes1-assignment
assignment 3
>>> #question1
>>> s=[1,1,2,2,2,3,3,3,3,5,5]
>>> s
[1, 1, 2, 2, 2, 3, 3, 3, 3, 5, 5]
>>> #question2
>>> s1=['google','apple','facebook','microsoft','table']
>>> s1
['google', 'apple', 'facebook', 'microsoft', 'table']
>>> s.append(s1)
>>> s
[1, 1, 2, 2, 2, 3, 3, 3, 3, 5, 5, ['google', 'apple', 'facebook', 'microsoft', 'table']]
>>> #question3
>>> print("no. of element 2 in list s = "s.count(2))
SyntaxError: invalid syntax
>>> print("no. of element 2 in list s = " s.count(2))
SyntaxError: invalid syntax
>>> print("no. of element 2 in list s = " (s.count(2)))
Traceback (most recent call last):
  File "<pyshell#12>", line 1, in <module>
    print("no. of element 2 in list s = " (s.count(2)))
TypeError: 'str' object is not callable
>>> print(("no. of element 2 in list s = ")+(s.count(2)))
Traceback (most recent call last):
  File "<pyshell#13>", line 1, in <module>
    print(("no. of element 2 in list s = ")+(s.count(2)))
TypeError: must be str, not int
>>> print(s.count(2))
3
>>> n1=s.count(2)
>>> n2=s.count(3)
>>> print("no. of 2 in s =",n1)
no. of 2 in s = 3
>>> print("no. of 3 in s ="n2)
SyntaxError: invalid syntax
>>> print("no. of 3 in s =",n2)
no. of 3 in s = 4
>>> #question4
>>> n=[5,2,3,1,4]
>>> n
[5, 2, 3, 1, 4]
>>> print(n.sort())
None
>>> n.sort()
>>> n
[1, 2, 3, 4, 5]
>>> #question5
>>> a=[6,7,8,9,10]
>>> b=[1,2,3,4,5]
>>> c=a+b
>>> c
[6, 7, 8, 9, 10, 1, 2, 3, 4, 5]
>>> c.sort()
>>> c
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
>>> 

