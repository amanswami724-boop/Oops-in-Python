# Oops-in-Python


1.  Create a class named Student with attributes: 
# o name  
# o age  
# o course  
#  Create an object and print all the details. 

"""
class Student:
    name =  "Aman"
    age = 22
    course = "B.tech"

st = Student()
print(st.name)
print(st.age)
print(st.course)    """


# 2.  Create a class named Car with attributes: 
# o brand  
# o model  
# o price  
#   Create two objects and display their details.

"""
class Car:
    brand = "Mahindra"
    model = "Bolero"
    price = 1000000
mah = Car()
bol = Car()
print(mah.brand)
print(mah.model)
print(bol.price)"""

# 3. Create a class named Employee and use a constructor (__init__) to initialize: 
# o employee_id  
# o name  
# o salary  
#             Print the employee details. 

"""
class Employee:
    def __init__(self): 
        self.employee_id = "a101"
        self.name = "Aman"
        self.salary =30000
emp = Employee()
print(emp.employee_id)
print(emp.name)
print(emp.salary)
"""

# 4.
#  Create a class named Rectangle with attributes: 
# o length  
# o width  
#            Create a method to calculate and print the area of the rectangle. 


"""
class Rectangle:
    def __init__(self, length,width): 
       self.length = 10
       self.width = 10
       self.area = length*width
       
ar= Rectangle(10,10)
print(ar.area)
    """
    
# 5. Create a class named Circle with an attribute radius. 
#    Create a method that calculates and prints the area of the circle.


"""
class Circle:
    def __init__(self, radius, pie):
        self.radius = 5
        self.pie =3.14
        self.area = 2*pie*radius*radius
ar = Circle(5,3.14)
print(ar.area   )   
   """

   #6. Create a class named BankAccount with: 
# o account_holder  
# o balance  
#            Create methods: 
# o deposit(amount)  
# o withdraw(amount)  
#             Display the updated balance after each transaction.

"""
class BankAccount:
    def __init__(self, account_holder, balance):
        self.account_holder = account_holder
        self.balance = balance
    def deposit(self, amount):
        self.balance += amount
        print(f"Deposit: {amount}, balance: {self.balance}")
    def withdraw(self, amount):
        self.balance -= amount
        print(f"Withdraw: {amount}, balance: {self.balance}")

ac = BankAccount("aman", 30000)
ac.deposit(100000)
ac.withdraw(50000)
"""

# 7. Create a class named Animal with a method sound(). 
# Create a child class Dog that overrides the sound() method and prints "Bark". 

"""
class Animal:
    def sound(self):
        pass
class Dog(Animal): 
     def sound(self):
         print("Bark")
ani =Animal()
dog =Dog()

ani.sound()
dog.sound()  
"""

# 8. Create a class named Person with attributes: 
#     o name  
#     o age  
#Create a child class Student with an additional attribute: 
#     o roll_number  
#Display all the details using an object of the Student class. 


"""
class Person:
    name = "Aman"
    age = 22
class Student(Person):
        roll_number ="25ebkcs214"
std = Student()
print(std.name)
print(std.age)
print(std.roll_number )   
   """ 

   # 9. Create a class named Calculator with methods: 
#   o add()  
#   o subtract()  
#   o multiply()  
#   o divide()  
#Take two numbers as input and perform all operations.             
            
"""
class Calculator:
    def __init__(self, a, b):
        self.a = 10
        self.b = 20
    def add(self,a,b):
         print(a+b)
    def substract(self, a,b):
        print(a-b)
    def multiply(self,a,b):
         print(a*b)
    def divide(self,a,b):
        print(a/b)

cal = Calculator(10,20)
cal.add(10,20)
cal.substract(50,20)
cal.multiply(10,20)
cal.divide(40,20)

"""

# 10. Create a class named LibraryBook with attributes:  
#       ● book_name  
#       ● author  
#       ● price  
#Create a method display_book_info() that prints all book details.
# Create at least three book objects and display their information.


"""
class LibraryBook:
    def __init__(self, book_name, author, price):
        self.book_name = book_name
        self.author = author
        self.price = price

    def display_book_info(self):
        print(f"{self.book_name} by {self.author}: {self.price}")

b1 = LibraryBook("Python", "Guido Van Russam", 1000)
b2 = LibraryBook("Linux", "GS", 1500)
b3 = LibraryBook("Java", "Pardeep Singh", 1200)

b1.display_book_info()
b2.display_book_info()
b3.display_book_info()
        """
    
            
            





