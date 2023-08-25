
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

