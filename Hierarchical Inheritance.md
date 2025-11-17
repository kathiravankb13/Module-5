
# Exp.No:25  
## Hierarchical Inheritance

---

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

---

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**

---

### PROGRAM
```
class A:
    def data(self):
        self.idd = int(input())
        self.name = input()
        self.gen = input()
        self.comp = input()
        self.dept = input()
class B(A):
    def display1(self):
        A.data(self)
        print("Doctor Object")
        print("Id: ",self.idd)
        print("Name: ",self.name)
        print("Gender: ",self.gen)
        print("Hospital: ",self.comp)
        print("Department: ",self.dept)
        print("")
class C(B):
    def display2(self):
        A.data(self)
        print("Patient Object")
        print("Id: ",self.idd)
        print("Name: ",self.name)
        print("Gender: ",self.gen)
        print("Hospital: ",self.comp)
        print("Department: ",self.dept)
obj = C()
objj = B()
objj.display1()
obj.display2()
```

### OUTPUT  

![image](https://github.com/user-attachments/assets/1201879c-3d25-489e-8f4c-4f721c370f5f)
 
### RESULT
Thus the Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor` is successfully executed. 
