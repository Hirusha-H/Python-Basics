# Datatype: String
**Type:** `<class 'str'>` </br>
**Examples,**

1. How to assign a string to a variable. (2 ways)
```python
# String in single quotation mark
my_string = 'Hey, there'

# String in double quotation mark
my_string2 = "Hey, there"
```

2. Merge two or more strings into one
```python
merge_str_1 = "Hi "
merge_str_2 = "Bro!"
print(merge_str_1+merge_str_2)
```

3. Make every character in a string to uppercase
```python
to_uppper = "Hello, this is lowercase"
print(to_uppper.upper())
```

4. Make every character in a string to lowercase
```python
to_uppper = "HELLO, THIS IS UPPERCASE"
print(to_uppper.lower())
```

5. Replace character in a string
Below code'll replace 'replace this with x' with 'x'

**Arguments**,
- `oldvalue` - This is the old string that you want to replace
- `newvalue` - This is the new string that you want to replace with old string

```python
to_replace_str = "Hey, replace this with x"
print(to_replace_str.replace("replace this with x", "x"))
```

6. Find text in a string
**Arguments**,
- `value` - This is the string that you want to sear for

```python
find_text = "Yo, Wassup?"
print(find_text.find("Yo")) # This'll return index of the text
```

7. Check if string only has digits
```python
digit_str = "123456"
print(digit_str.isdigit())
```

8. Check if string has only uppercase characters
```python
upper_str = "HELLO BRO!"
print(upper_str.isupper())
```

9. Check if string has only lowercase characters
```python
lower_str = "wassup?"
print(lower_str.islower())
```

10. Check if string startswith  a specific character
**Arguments**,
- `value` - This is the string that you want to check if the string starts with

```python
startswith_str = "Hello"
print(startswith_str.startswith("H")) # This'll print True if yes else it'll print False
```

11. Check if string endswith  a specific character
**Arguments**,
- `value` - This is the string that you want to check if the string ends with

```python
endswith_str = "Hey"
print(endswith_str.endswith("y")) 
```


**Thats's all for today (i'll teach about others in day-2)
