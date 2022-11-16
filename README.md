# PythonAssignment-1
iNeuron PythonAssignment-1



## Assignment Part-1
### Q1. Why do we call Python as a general purpose and high-level programming language?
A) Python is called general purpose language because, it can widely be used across all platforms and python is also called high-level programming language because it is less efficient in terms of memory and processing power than low-level programming.


 
 ---

### Q2. Why is Python called a dynamically typed language?
A) It is dynamically typed language because we don't have to declare the type of variable while assigning a    value to a variable. python don't have any problem even if we don't declare the type of variable.



---

### Q3. List some pros and cons of Python programming language?
A) **Pros** : python is free and open source, it has vast collection of  libraries.
          python is a general purpose and high-level programming lanugage i.e, it can be easily understood by humans. <br>
    **Cons** : since python is a dynamically typed we can expect errors during run time.
            code is executed line by line which makes it slower.


---
### Q4. In what all domains can we use Python?
A) Python can be used in Big Data, Data science, Machine Learning, Artificial Intelligence.

---

### Q5. What are variable and how can we declare them?
A) variables are just like box or containers which stores a particular value. Just name a varialbe and assign a value to it, (data type will be automatically determined, we need not determine explicitly).

---

### Q6. How can we take an input from the user in Python?
A) input can be taken using input() method.
```
    Ex: input("enter a value: ")
``` 
---

### Q7. What is the default datatype of the value that has been taken as an input using input() function?
A)The default data type of a input method is "string".

---

### Q8. What is type casting?
A) converting one variable data type to another.
```
Ex: a = 5 (the data type of a is int)
    b = float(a) (the data type of a is converted to float)
 ```  
---

### Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A) using single input() we can take only one input from user. the input() method accepts only one input at a time.

---

### Q10. What are keywords?
A) keywords (or) special reserved words that have specific meaning and purpose and cannot used for anything else.
Ex: return, True, False.

---

### Q11. Can we use keywords as a variable? Support your answer with reason.
A) No keywords cannot be used as a variable, because are reserved words that are used for specific purpose.

---

### Q12. What is indentation? What's the use of indentaion in Python?
A)The spaces at the beginning of a code line is called indentation. The main use of indentation in python is to indicate the block of code.
```
Ex: for i in range(10):
        print(i) 
        
    print(i) is indented in the above code.
 ```  
---
    

### Q13. How can we throw some output in Python?
A) using print() method we can display the output.

---

### Q14. What are operators in Python?
A) Operators in python:
    Arithmetic operators.
    Assignment operators.
    Logical operators.
    Bitwise operators.
    
---

### Q15. What is difference between / and // operators?
A) / is a Division operator and // is floor division operator (it returns nearest whole value).

---

### Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
A) 
```
print("iNeuron"*4)
```
---

### Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A)
```
number = int(input('enter a number: '))
if number%2==0:
    print("number is even")
else:
    print("number is odd")
 ```
---

### Q18. What are boolean operator?
A)  To represent the truth value of an expression Boolean operators  are used it returns any one value either True or False.

---

### Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1
```
---


### Q20. What are conditional statements in Python?
A) (if else) are the conditional statements in python, these statements are used for decision making.
the block of code runs only when the if statement is True, and else block will be executed when if statement is False.

---

### Q21. What is use of 'if', 'elif' and 'else' keywords?
A) The if, elif, else are conditional statements, it is used to make decision, if we have three conditions
if, elif and else statements are used to make decision.

---

### Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A) 
```
age = int(input("enter your age: "))

if age >= 18:
    print("I can Vote")
else:
    print("I can't vote")
```
---


### Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
    if num%2==0:
        print(num, "is even")
```
---


### Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A)
```
first_num = int(input("Enter First Number: "))
second_num = int(input("Enter Second Number: "))
third_num = int(input("Enter Third Number: "))


if (first_num > second_num) and (first_num > third_num):
    largest_num = first_num
    print("The largest Number is :", largest_num)
elif (second_num > first_num) and (second_num > third_num):
    largest_num = second_num
    print("The largest Number is :", largest_num)
elif (first_num == second_num == third_num):
    print("all values cannot be equal")
else:
    largest_num = third_num
    print("The largest Number is:", largest_num)
```

---


### Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

---

### Q26. What is a string? How can we declare string in Python?
A) String is one of the datatype in python, it is represented with single or double quotes.
Ex: 'string'  or "string"

---

### Q27. How can we access the string using its index?
A) string is a squence type which means we can access string using its index values, using index number in square brackets we can access the string.
Ex: 
```
str = iNeuron
print(str[1])

result : N

```

---

### Q28. Write a code to get the desired output of the following
A) 
```
string = "Big Data iNeuron"
desired_output = "iNeuron"

print(string[9:])

```
---

### Q29. Write a code to get the desired output of the following.
A) 
```
string = "Big Data iNeuron"
desired_output = "norueNi"


print(string[slice(None,-8,-1)])

```
---

### Q30. Resverse the string given in the above question.
A)
```
print(string[slice(None,-17,-1)])

```
---

### Q31. How can you delete entire string at once?
A)using **replace()** method we can delete entire string at once,
```
str = "iNeuron"
print(str.replace(str,""))

```
---

### Q32. What is escape sequence?
A) Escape characters or sequences are illegal characters for Python and never get printed as part of the output. When backslash is used in Python programming, it allows the program to escape the next characters.

---

### Q33. How can you print the below string?
A)
```
'iNeuron's Big Data Course'
print("'iNeuron's Big Data Course'")

```
---
### Q34. What is a list in Python?
A) List is used to store collections of data, it is a sequence data type. A list can be defined as a collection of values or items of different types.

---

### Q35. How can you create a list in Python?
A) using square brackets we can create list in python.

```
lst = ["str", int, float]

```

---

### Q36. How can we access the elements in a list?
A) Each element in the list has index value, using those index values we can access the elements in list.

```
lst = ["str", 23, 24.5]
print(lst[1])

output : 23
```

---

### Q37. Write a code to access the word "iNeuron" from the given list.
A)
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])

output : "iNeuron"
```

---

### Q38. Take a list as an input from the user and find the length of the list.
A) 
```
n = input("enter elements seperated by comma as input: ") # 1,2,3,4,5
list_of_ele = n.split(",")
print(len(list_of_ele))


Step1 : we are accepting input as list separated by comma
step2 : we are splitting it with comma using split method
step3 : finally applying len() method 
```
---

### Q39. Add the word "Big" in the 3rd index of the given list.
A)
```
lst = ["Welcome", "to", "Data", "course"]
lst.insert(2, "Big")
print(lst)

output : ['Welcome', 'to', 'Big', 'Data', 'course']
```

---

### Q40. What is a tuple? How is it different from list?
A) Tuples and List are used to store multiple items in a single variable. A tuple is a collection which is **ordered** and **unchangeable**. The key difference between tuples and lists is that **while tuples are immutable objects**, **lists are mutable**. This **_means tuples cannot be changed while lists can be modified_**. **_Tuples are also more memory efficient than the lists. When it comes to time efficiency, tuples have a slight advantage over lists__ **.
