1. extend等list内置函数，对list做动作，函数返回的是None，因此不能直接a=b.extend(c)，此时a是None。https://www.runoob.com/python/python-lists.html
2. 初始化 list方法：res=\[\[1]\*(i+1)for i in range(numRows)]（[118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/)）
3. Class (类),Object（实例）,Attributes（属性）
实例的属性通过self绑定，类的属性在class中直接定义
https://www.liaoxuefeng.com/wiki/1016959663602400/1017594591051072
4. [True Value Testing](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)
Any object can be tested for truth value, for use in an if or while condition or as operand of the Boolean operations below.

By default, an object is considered true unless its class defines either a __bool__() method that returns False or a __len__() method that returns zero, when called with the object. 1 Here are most of the built-in objects considered false:

constants defined to be false: None and False.

zero of any numeric type: 0, 0.0, 0j, Decimal(0), Fraction(0, 1)

empty sequences and collections: '', (), [], {}, set(), range(0)

Operations and built-in functions that have a Boolean result always return 0 or False for false and 1 or True for true, unless otherwise stated. (Important exception: the Boolean operations or and and always return one of their operands.)
