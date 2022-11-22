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

for element in numbers:
    if element > 500:
        break
    elif element > 150:
        continue
    elif element % 5 == 0:
        print(element)
        
 output : 75
          150
          145

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
A) Tuples and List are used to store multiple items in a single variable. A tuple is a collection which is **ordered** and **unchangeable**. The key difference between tuples and lists is that **while tuples are immutable objects**, **lists are mutable**. This **_means tuples cannot be changed while lists can be modified_**. **_Tuples are also more memory efficient than the lists. When it comes to time efficiency, tuples have a slight advantage over lists_** .

---

### Q41. How can you create a tuple in Python? 
A) A tuple in Python can be created by enclosing all the comma-separated elements inside the parenthesis (). Elements of the tuple are immutable and ordered. It allows duplicate values and can have any number of elements.
```
tup = (1,2,2,4,5,6)

```
---

### Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason. 
A) No, we cannot add any element once Tuple is created because, Tuple is immutable i.e, it cannot be changed once created.

---

### Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
A) Yes, we can append two tuples.

```
tup_1 = (1,2,3,4,5)
tup_2 = (6,7,8,9)
print(tup_1 + tup_2)

output : (1, 2, 3, 4, 5, 6, 7, 8, 9)

```

---

### Q44. Take a tuple as an input and print the count of elements in it.
A) 
```
tup = tuple(input("enter comma separated values: ").split(","))
print(len(tup))

```

---

### Q45. What are sets in Python?
A) Sets are used to store multiple items in a single variable. It is used to store collections of data. A set is a collection which is **unordered**, **unchangeable**, and **unindexed**.

---

### Q46. How can you create a set?
A) A set is created by placing all the  elements inside curly braces {} , separated by comma, or by using the built-in set() function. It can have any number of items and they may be of different types (integer, float, tuple, string etc.). **A set is mutable,** i.e., we can **remove or add elements to it**.

```
new_set = {1,2,4,5,"str"}
```

---

### Q47. Create a set and add "iNeuron" in your set.
A) 
```
my_set = {1,2,3,4}
my_set.add("iNeuron")
print(my_set)

output : {1, 2, 3, 4, 'iNeuron'}

```

---

### Q48. Try to add multiple values using add() function.
A) 
```
my_set = {1,2,3,4}
my_set_2 = {10,11,12}
my_set.update(my_set_2)
print(my_set)

output : {1, 2, 3, 4, 10, 11, 12}

```

---

### Q49. How is update() different from add()?
A) update() method is to add multiple elements to a set, whereas add() method is to add only one element to a set.

---

### Q50. What is clear() in sets?
A) clear() method is to remove all the elements from a set.

---

### Q51. What is frozen set?
A) The frozenset() method returns an unchangeable frozenset object it is unchangeable.

---

### Q52. How is frozen set different from set?
A) Frozenset is similar to set in Python, except that **frozensets are immutable, which implies that once generated, elements from the frozenset cannot be added or removed**.

---

### Q53. What is union() in sets? Explain via code.
A) The union() method returns a set that contains all items from the original set, and all items from the specified set.
```
my_set = {1,2,3,4}
my_set_2 = {10,11,12}
my_set_3 = {10,11,4}


result = my_set.union(my_set_2, my_set_3)
print(result)

output : {1, 2, 3, 4, 10, 11, 12}

```

---

### Q54. What is intersection() in sets? Explain via code.
A) The intersection() method returns a new set with elements that are common to all sets.

```
my_set_2 = {10,11,12,4}
my_set_3 = {10,11,4}
print(my_set_2.intersection(my_set_3))

output : {10, 11, 4}

```

---

### Q55. What is dictionary in Python?
A) Dictionaries are used to store data values in key:value pairs written in curly brackets. It is **ordered**, **changeable** and **do not allow duplicates**.

---

### Q56. How is dictionary different from all other data structures.
A) Dictionary is more memory efficient than other data structures in python. It is an **unordered collection of data values, used to store data values like a map, which, unlike other Data Types that hold only a single value as an element, Dictionary holds the key:value pair. Key-value is provided in the dictionary to make it more optimized**. Lookups are faster in dictionaries because Python implements them using hash tables.

---

### Q57. How can we delare a dictionary in Python?
A) Dictionary can be declared using curly brackets, data will be stored as key value pairs.

```
my_dict = {"car1":"maruthi", "car2": "ford", "car3":"benz"}

```

---

### Q58. What will the output of the following?
A)
```
var = {}
print(type(var))

output : <class 'dict'>

```

---

### Q59. How can we add an element in a dictionary?
A) 
```
my_dict = {"car1":"maruthi", "car2": "ford", "car3":"benz"}
my_dict["car4"] = "toyota"
print(my_dict)

output : {'car1': 'maruthi', 'car2': 'ford', 'car3': 'benz', 'car4': 'toyota'}

```

---

### Q60. Create a dictionary and access all the values in that dictionary.
A)
```
my_dict = {"car1":"maruthi", "car2": "ford", "car3":"benz"}
my_dict["car4"] = "toyota"
print(my_dict.items())

output: dict_items([('car1', 'maruthi'), ('car2', 'ford'), ('car3', 'benz'), ('car4', 'toyota')])

```

---


### Q61. Create a nested dictionary and access all the element in the inner dictionary.
A)
```

my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}

print(my_dict["cars"]["car1"])

output : maruthi

```
---

### Q62. What is the use of get() function?
A) The get() method returns the value of the item with the specified key.

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print(my_dict.get("bike1"))

output : honda

```

---

### Q63. What is the use of items() function?
A) The **items() method returns a view object**. The view object contains the **key-value pairs of the dictionary, as tuples in a list** .

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print(my_dict.items())

output: dict_items([('cars', {'car1': 'maruthi', 'car2': 'ford'}), ('bike1', 'honda')])

```

---

### Q64. What is the use of pop() function?
A) The pop() method removes the element at the specified position. 

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print("the poped value is :", my_dict.pop("bike1"))
print("the dicitionary after applying pop method : ", my_dict)

output : the poped value is : honda
         the dicitionary after pop method :  {'cars': {'car1': 'maruthi', 'car2': 'ford'}}
         
```

---

### Q65. What is the use of popitems() function?
A) The Python popitem() method removes and returns the last element (key, value) pair inserted into the dictionary.

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print(my_dict.popitem())

output : ('cars', {'car1': 'maruthi', 'car2': 'ford'})

```

---

### Q66. What is the use of keys() function?
A) The keys() method extracts the keys of the dictionary and returns the list of keys as a view object.

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print(my_dict.keys())

output : dict_keys(['cars', 'bike1'])

```

---

### Q67. What is the use of values() function?
A) The values() method returns a view object that displays a list of all the values in the dictionary.

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
print(my_dict.values())

output : dict_values([{'car1': 'maruthi', 'car2': 'ford'}, 'honda'])

```

---

### Q68. What are loops in Python?
A) Looping means repeating something over and over until a particular condition is satisfied.

---

### Q69. How many type of loop are there in Python?
A) There are 3 types of loops in Python : 
1. For loop - A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
2. While loop - With the while loop we can execute a set of statements as long as a condition is true.
3. Nested loop - A nested loop is a loop inside a loop. The "inner loop" will be executed one time for each iteration of the "outer loop".

---

### Q70. What is the difference between for and while loops?
A)A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string), whereas with the while loop we can execute a set of statements as long as a condition is true.

---

### Q71. What is the use of continue statement?
A) The continue keyword is used to end the current iteration in a for loop or a while loop, and continues to the next iteration.

---


### Q72. What is the use of break statement?
A) It is used to control the sequence of the loop. Suppose you want to terminate a loop and skip to the next code after the loop; break will help you do that.

---

### Q73. What is the use of pass statement?
A) The pass statement is used as a placeholder for future code. When the pass statement is executed, nothing happens, but you avoid getting an error when empty code is not allowed.


---

### Q74. What is the use of range() function?
A) The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

---

### Q75. How can you loop over a dictionary?
A) Using for loop we can loop over a dictionary.

```
my_dict = {"cars":{"car1":"maruthi", "car2":"ford"}, "bike1": "honda"}
for i in my_dict:
    print(i)
    
output : cars
         bike1
         
```

---

# Coding problems

### Q76. Write a Python program to find the factorial of a given number.
A)

```
num = int(input("Enter a number: "))    
factorial = 1    
if num < 0:    
   print(" Factorial does not exist for negative numbers")    
elif num == 0:    
   print("The factorial of 0 is 1")    
else:    
   for i in range(1,num + 1):    
       factorial = factorial*i    
   print("The factorial of",num,"is",factorial)   
   
   
  output : Enter a number: 5
           The factorial of 5 is 120
           
```

---

### Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
A) 

```
principle = int(input("enter principle amount: "))
rate = float(input("enter  rate of interest %: "))
time = float(input("enter  time: "))

print(principle*rate*time/100)

output : enter principle amount: 500
         enter principle rate: 15
         enter principle time: 2
         150.0
         
```

---

### Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
A) 

```
def compound_interest(principle, rate, time):
 
    
    Amount = principle * (pow((1 + rate / 100), time))
    CI = Amount - principle
    print("Compound interest is", CI)
 
 

compound_interest(10000, 10.25, 5)


output : Compound interest is 6288.946267774416
```

---

### Q79. Write a Python program to check if a number is prime or not.
A)
```
num = int(input("enter a number: "))


if num > 1:
    for i in range(2,num): 
        # print(f"{num}/{i}") 
        if num % i == 0:
            print("not prime")
            break
    else:
        print("it is prime")
        
  output : enter a number: 29
           it is prime
           
```

---

### Q80. Write a Python program to check Armstrong Number.
A)

```

num = int(input("Enter a number: "))


sum = 0


temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10


if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
   
  output : Enter a number: 23
          23 is not an Armstrong number 
 ```
 
---

### Q81. Write a Python program to find the n-th Fibonacci Number.
A)
```
def solve(n):
   if n <= 2:
      return n - 1
   else:
      return solve(n - 1) + solve(n - 2)

n = 8
print(solve(n))

output : 13
```
---

### Q82. Write a Python program to interchange the first and last element in a list.
A) 

```
def swapList(newList):
	size = len(newList)
	
	
	temp = newList[0]
	newList[0] = newList[size - 1]
	newList[size - 1] = temp
	
	return newList
	

newList = [12, 35, 9, 56, 24]

print(swapList(newList))


output : [24, 35, 9, 56, 12]

```

---

### Q83. Write a Python program to swap two elements in a list.
A)

```
def swapPositions(list, pos1, pos2):
     
    list[pos1], list[pos2] = list[pos2], list[pos1]
    return list
 

List = [23, 65, 19, 90]
pos1, pos2  = 1, 3
 
print(swapPositions(List, pos1-1, pos2-1))

output : [19, 65, 23, 90]

```
---

### Q84. Write a Python program to find N largest element from a list.
A)

```

list_1 = [10, 20, 4, 45, 99]


list_1.sort()


print("Largest element is:", list_1[-1])


output : Largest element is: 99

```

---

### Q85. Write a Python program to find cumulative sum of a list.
A)

```

def Cumulative(lists):
	cu_list = []
	length = len(lists)
	cu_list = [sum(lists[0:x:1]) for x in range(0, length+1)]
	return cu_list[1:]


lists = [10, 20, 30, 40, 50]
print (Cumulative(lists))

output : [10, 30, 60, 100, 150]

```

---

### Q86. Write a Python program to check if a string is palindrome or not.
A)

```


def isPalindrome(s):
	return s == s[::-1]



s = "malayalam"
ans = isPalindrome(s)

if ans:
	print("Yes")
else:
	print("No")
 
 
 output : yes
 
 ```
 
 ---
 
 ### Q87. Write a Python program to remove i'th element from a string.
 A)
 
 ```
def remove(string, i):

	for j in range(len(string)):
		if j == i:
			string = string.replace(string[i], "", 1)
	return string
	

if __name__ == '__main__':
	
	string = "iNeuron"
	
	# Remove nth index element
	i = 0
	

	print(remove(string, i))

output : Neuron

```

---

### Q88. Write a Python program to check if a substring is present in a given string.
A)

```
my_string = "Big data bootcamp at iNeuron"
 
if "at" in my_string:
    print("Yes, it is present in the string")
else:
    print("No, it is not present")

output : Yes, it is present in the string

```
---

### Q89. Write a Python program to find words which are greater than given length k.
A)

```
sentence = "Big Data Bootcamp at iNeuron"
length = 3
print([word for word in sentence.split() if len(word) > length])


output : ['Data', 'Bootcamp', 'iNeuron']

```

---

### Q90. write a python program to extract unique values dictionary values.
A) 

```
my_dict = {'hi' : [5,3,8, 0],
   'there' : [22, 51, 63, 77],
   'how' : [7, 0, 22],
   'are' : [12, 11, 45],
   'you' : [56, 31, 89, 90]}



my_result = list(sorted({elem for val in my_dict.values() for elem in val}))

print("The unique values are : ", my_result)

output : The unique values are :  [0, 3, 5, 7, 8, 11, 12, 22, 31, 45, 51, 56, 63, 77, 89, 90]

```

---

### 


