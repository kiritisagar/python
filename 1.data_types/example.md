### 1. String Concatenation**
String concatenation refers to joining two or more strings together to form a single string. 
The `+` operator is used to concatenate strings in Python.

# Example:
```python
str1 = "Hello"
str2 = "World"
result = str1 + " " + str2
print(result)
```

- **Explanation**:
  - `str1` contains "Hello" and `str2` contains "World".
  - We use `+` to concatenate `str1` and `str2` with a space in between (`" "`).
  - Output: `Hello World`

---

### **2. String Length**
You can calculate the length of a string using the `len()` function.

#### Example:
```python
text = "Python is awesome"
length = len(text)
print("Length of the string:", length)
```

- **Explanation**:
  - The `len()` function returns the number of characters in the string, including spaces.
  - Output: `Length of the string: 17`

---

### **3. String Case Conversion**
Python provides methods to convert strings to uppercase and lowercase.

#### Example:
```python
text = "Python is awesome"
uppercase = text.upper()
lowercase = text.lower()
print("Uppercase:", uppercase)
print("Lowercase:", lowercase)
```

- **Explanation**:
  - `text.upper()` converts all characters in the string to uppercase: `PYTHON IS AWESOME`.
  - `text.lower()` converts all characters to lowercase: `python is awesome`.

---

### **4. String Replacement**
You can replace parts of a string using the `replace()` method.

#### Example:
```python
text = "Python is awesome"
new_text = text.replace("awesome", "great")
print("Modified text:", new_text)
```

- **Explanation**:
  - The `replace()` method replaces the word "awesome" with "great".
  - Output: `Modified text: Python is great`

---

### **5. String Splitting**
You can split a string into a list of words using the `split()` method. The default behavior splits the string by spaces.

#### Example:
```python
text = "Python is awesome"
words = text.split()
print("Words:", words)
```

- **Explanation**:
  - The `split()` method splits the string at spaces and returns a list of words.
  - Output: `Words: ['Python', 'is', 'awesome']`

---

### **6. String Stripping**
You can remove leading and trailing spaces from a string using the `strip()` method.

#### Example:
```python
text = "   Some spaces around   "
stripped_text = text.strip()
print("Stripped text:", stripped_text)
```

- **Explanation**:
  - The `strip()` method removes extra spaces at the beginning and end of the string.
  - Output: `Stripped text: Some spaces around`

---

### **7. Substring Search**
You can check if a substring exists within a string using the `in` operator.

#### Example:
```python
text = "Python is awesome"
substring = "is"
if substring in text:
    print(substring, "found in the text")
```

- **Explanation**:
  - The `in` operator checks if `"is"` is a part of `text`.
  - Output: `is found in the text`

---

### **8. Float Variables & Basic Arithmetic**
Float variables store decimal numbers, and basic arithmetic operations can be performed on them like addition, subtraction, multiplication, and division.

#### Example:
```python
num1 = 5.0
num2 = 2.5

# Basic Arithmetic
result1 = num1 + num2
result2 = num1 - num2
result3 = num1 * num2
result4 = num1 / num2
```

- **Explanation**:
  - Addition: `5.0 + 2.5 = 7.5`
  - Subtraction: `5.0 - 2.5 = 2.5`
  - Multiplication: `5.0 * 2.5 = 12.5`
  - Division: `5.0 / 2.5 = 2.0`

#### Rounding:
```python
result5 = round(3.14159265359, 2)
print("Rounded:", result5)
```
- **Explanation**:
  - The `round()` function rounds the number to 2 decimal places.
  - Output: `Rounded: 3.14`

---

### **9. Integer Division & Modulus**
Integer division uses `//`, which divides two numbers and returns the quotient without the remainder. The modulus operator (`%`) returns the remainder of the division.

#### Example:
```python
num1 = 10
num2 = 5

result1 = num1 // num2  # Integer Division
result2 = num1 % num2   # Modulus (Remainder)
```

- **Explanation**:
  - Integer Division: `10 // 5 = 2`
  - Modulus: `10 % 5 = 0` (No remainder)

---

### **10. Absolute Value**
The `abs()` function returns the absolute (positive) value of a number.

#### Example:
```python
result3 = abs(-7)
print("Absolute Value:", result3)
```

- **Explanation**:
  - The `abs()` function converts `-7` to `7`.
  - Output: `Absolute Value: 7`

---

### **11. Regular Expressions (Regex)**
Regular expressions allow you to search, match, and manipulate strings in powerful ways. Python’s `re` module provides tools for working with regular expressions.

#### a. **Search for a Pattern**
The `re.search()` function looks for a pattern in a string and returns the match if found.

#### Example:
```python
import re

text = "The quick brown fox"
pattern = r"brown"

search = re.search(pattern, text)
if search:
    print("Pattern found:", search.group())
```

- **Explanation**:
  - Searches for the word `"brown"` in `text` and returns it if found.
  - Output: `Pattern found: brown`

#### b. **Matching a Pattern**
The `re.match()` function checks if the beginning of the string matches the pattern.

#### Example:
```python
import re

text = "The quick brown fox"
pattern = r"quick"

match = re.match(pattern, text)
if match:
    print("Match found:", match.group())
else:
    print("No match")
```

- **Explanation**:
  - Since `"quick"` is not at the beginning of `text`, no match is found.
  - Output: `No match`

#### c. **Replacing Substrings**
The `re.sub()` function replaces occurrences of a pattern with another string.

#### Example:
```python
import re

text = "The quick brown fox jumps over the lazy brown dog"
pattern = r"brown"
replacement = "red"

new_text = re.sub(pattern, replacement, text)
print("Modified text:", new_text)
```

- **Explanation**:
  - The function replaces every occurrence of `"brown"` with `"red"`.
  - Output: `Modified text: The quick red fox jumps over the lazy red dog`

#### d. **Splitting Strings**
You can split a string by a specific pattern using `re.split()`.

#### Example:
```python
import re

text = "apple,banana,orange,grape"
pattern = r","

split_result = re.split(pattern, text)
print("Split result:", split_result)
```

- **Explanation**:
  - The function splits the string wherever it finds a comma.
  - Output: `Split result: ['apple', 'banana', 'orange', 'grape']`

---

### Summary:
- **Strings**: You can manipulate strings through concatenation, case conversion, splitting, and searching.
- **Numbers**: Arithmetic operations work with integers and floats, with functions like `abs()` for absolute value and `round()` for rounding.
- **Regex**: Powerful tools for pattern matching, searching, and string manipulation.

