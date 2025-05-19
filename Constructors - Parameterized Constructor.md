  # Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a employee with a parameterized constructor, which will take the `name` and `userid` of the employee as parameters and print the `userid` of the employee.

---

### ALGORITHM

1. Begin the program.  
2. Define a `employee` class.  
3. The `employee` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `employee` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class employees:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def dis(self):
        print("Hello my id is :",a)
        print("My name is :",b)
a=int(input())
b=input()
obj=employees(a,b)
obj.dis()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/bfbf6e3c-13ac-453a-88cf-0f1bde496feb)
### RESULT
Thus,a Python code to create a class for a person with a parameterized constructor are verified.
