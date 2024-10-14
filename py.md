In Python, a dictionary (dict) is a mapping type that stores data in the form of key-value pairs. It’s highly efficient for lookups, insertion, and deletion based on keys.

 Error Handling (Exceptions)
In Python, errors can be managed using try-except blocks, ensuring that the program doesn’t crash.


![image](https://github.com/user-attachments/assets/6cfddcca-7622-4681-8cb0-cd7d0f7a9a5a)



Example
python
Copy code
try:
    result = 10 / 0  # This will raise a ZeroDivisionError
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("This will always run.")  # Final block to clean up resources

In Python, variables can store different types of data, and Python automatically manages the storage for these types. Here’s an overview of the **standard data types** provided by Python:

### 1. **Numbers**
   - **Integer (`int`)**: Whole numbers, positive or negative, without decimals.
     ```python
     x = 10  # integer
     ```
   - **Float (`float`)**: Numbers with decimal points (floating-point numbers).
     ```python
     y = 10.5  # float
     ```
   - **Complex (`complex`)**: Numbers with a real and an imaginary part.
     ```python
     z = 3 + 5j  # complex number
     ```

### 2. **Sequence Types**
   - **String (`str`)**: Ordered collection of characters, enclosed in quotes (single, double, or triple quotes).
     ```python
     name = "Alice"  # string
     ```
   - **List (`list`)**: Ordered and mutable sequence of elements, can contain mixed data types.
     ```python
     fruits = ["apple", "banana", "cherry"]  # list of strings
     ```
   - **Tuple (`tuple`)**: Ordered but immutable sequence of elements, like lists, but unchangeable.
     ```python
     coordinates = (10.0, 20.0)  # tuple of floats
     ```
   - **Range (`range`)**: Represents a sequence of numbers, commonly used for looping.
     ```python
     r = range(5)  # sequence of numbers from 0 to 4
     ```

### 3. **Boolean (`bool`)**
   - Represents one of two values: **True** or **False**. Used for logical operations.
     ```python
     is_active = True  # boolean
     ```

### 4. **Set**
   - **Set (`set`)**: Unordered collection of unique elements, mutable.
     ```python
     unique_numbers = {1, 2, 3, 3, 4}  # set (automatically removes duplicates)
     ```
   - **Frozen Set (`frozenset`)**: Immutable version of a set, once created, cannot be changed.
     ```python
     frozen_set = frozenset([1, 2, 3])  # immutable set
     ```

### 5. **Dictionary (`dict`)**
   - Stores key-value pairs, where keys are unique and can be of any immutable type (such as strings or numbers).
     ```python
     person = {
         "id": 101,  # integer
         "name": "Alice",  # string
         "age": 30  # integer
     }  # dictionary
     ```

These data types are foundational in Python and are used to store and manipulate different kinds of data effectively.
