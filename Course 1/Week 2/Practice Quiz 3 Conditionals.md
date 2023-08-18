**Conditionals**

###**Question 1**###

```
True
```

###**Question 2**###

```
def greeting(name):
  if name == "Taylor":
    return "Welcome back Taylor!"
  else:
    return "Hello there, " + name

print(greeting("Taylor"))
print(greeting("John"))
```

###**Question 3**###

```
if number > 11: 
  print(0)
elif number != 10:
  print(1)
elif number >= 20 or number < 12:
  print(2)
else:
  print(3)
```

###**Question 4**###

```
"A dog" is smaller than "A mouse" and 9999+8888 is larger than 100*100
```

###**Question 5**###

```
def calculate_storage(filesize):
    block_size = 4096
    # Use floor division to calculate how many blocks are fully occupied
    full_blocks = filesize
    # Use the modulo operator to check whether there's any remainder
    partial_block_remainder = filesize % 4096
    # Depending on whether there's a remainder or not, return
    # the total number of bytes required to allocate enough blocks
    # to store your data.
    if partial_block_remainder > 0:
        return 4096+(filesize//4096)*4096
    return (filesize//4096)*4096

print(calculate_storage(1))    # Should be 4096
print(calculate_storage(4096)) # Should be 4096
print(calculate_storage(4097)) # Should be 8192
print(calculate_storage(6000)) # Should be 8192
```
