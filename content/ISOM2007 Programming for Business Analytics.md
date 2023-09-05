
## 8.25 Lecture 3

[[Statement in Python]]

Deal with the error:

```Python
try:
	statement
except:
	statement

```

For example:

```Python
try:
	print(z)
except SyntaxError:
	print("oops. an SyntaxError occured")
except:
	print("oops. an SyntaxError occured")
	raise
z = 1
print(z)
```

For more information, could refer to: [Python raise用法（超级详细，看了无师自通） (biancheng.net)](http://c.biancheng.net/view/2360.html)

The function of `raise` is to "raise" the error.

Also, you could use the `int()` to convert the data type. For example:

```Python
balance = total + tax   # balance: float
dollars = int (balance) # dollars: integer
```

### The round off problem

When we type:

```Python
price = 4.35
b = 100
total = price * b
print(total)
```

It would output the result `4.39999999`. How to solve it? Use the function `round()`

```Python
price = 4.35
b = 100
total = round(price * b)
print(total)
```

Then it would be `435`

> Warning: Do not use `int()` because it will only keep the integer part




## 8.29 Lecture 4

### Review

Assign a variable: `variable = expression`, remember do not use the `%` or `?` to assign it.

The function `%whos` , to show all the self-defined variables.

The arithmetic operators and some built-in functions and so on are also useful. Some math module can be also used (but have to `from math import sqrt`) 

Some interesting things: 

```python
print(-9//5)
```

It would print `-2` 

---

Today's class:

### Strings

See some explanation about Strings in [[Sequence Functions]]

#### String Length

```python
length = len("World!")
print(length)
```

It is `6`, (do not count `""`)

We use the `str` to convert between numbers and strings.

How to copy a character from a string? 

![[截屏2023-08-29 11.56.32.png]]

We set this string to be 'name'

```python
start = name[0]
```

#### Escape Sequences

```python
print("He said\"Hello\"")
```

To provide a double quote. Similarly, if you want to print a `\`, just need to add a `\`, which is

```python
print("\"C:\\Temp\\Secret.txt\"")
```

### Input and Output

How to separate? Use `sep=`

```python
print("Hello","World","Cheer",sep=" ")
```