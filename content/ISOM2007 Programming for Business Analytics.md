
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