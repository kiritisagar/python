# Static Typing vs Dynamic Typing:

**Static Typing**:
it is when you must declare the type of each variable before you use it. 
This type can’t change once it’s set. 
For example, in a statically typed language like Java, if you declare a variable as an integer (a number), it must stay a number and cannot be changed to a different type, like text. 
This approach catches errors early on because the compiler checks for type errors before the program even runs.
ex:like Java, C, and C#


**Dynamic Typing** 
it is when you don’t have to declare the type of a variable in advance. 
The type is determined based on what you assign to it, and you can change it later if needed. 
For example, in a dynamically typed language like Python, you could assign a number to a variable and later change it to text without any issues. 
This makes coding fast and flexible, but errors can go unnoticed until the program runs, which can lead to bugs appearing later.
ex:Python


**To sum up**: Static typing is strict and stable, catching errors early, while dynamic typing is flexible and fast, allowing more changes but with the risk of finding errors only during runtime.

![image](https://github.com/user-attachments/assets/969ecafa-0ddf-49b2-8a2a-d02ce4b83e3a)

**1. Source Code**
This is the code you write in a .py file using Python’s syntax. It’s in human-readable form, written in plain text.

**Bytecode:** 
When you run your code, Python translates it into bytecode, which is like a simplified version of the code. 
Bytecode is not readable by humans and is stored in a .pyc file. This translation helps Python run your code faster the next time.

**Python Virtual Machine (PVM)**: 
The PVM is Python’s engine that actually runs the bytecode on your computer. It reads the bytecode instructions and tells your computer what to do.
