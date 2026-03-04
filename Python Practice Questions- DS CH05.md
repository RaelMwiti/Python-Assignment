## **Python Practice Questions**

### **Variables & Data Types**

1. Create a variable `name` and assign it your name as a string.

2. Create two variables `a` and `b`. Assign `a = 10` and `b = 3.14`. Print both and their types.

3. Define a boolean variable `is_student = True`. Print a sentence like “Am I a student? True”.

4. Create a variable `x = None`. Print it and check its type.

5. Swap the values of two variables `m = 5` and `n = 8` without using a third variable.

**Tutorial** for variables & data types:

* Built-in data types: [W3Schools – Python Data Types](https://www.w3schools.com/python/python_datatypes.asp) ([W3Schools](https://www.w3schools.com/python/python_datatypes.asp?utm_source=chatgpt.com))

* Also good: [GeeksforGeeks – Python Data Types](https://www.geeksforgeeks.org/python/python-data-types/) ([GeeksforGeeks](https://www.geeksforgeeks.org/python/python-data-types/?utm_source=chatgpt.com))

---

### **Conditional Statements (if / if-else)**

6. Ask the user (via `input`) to enter a number. If it's positive, print “Positive”, else print “Non-Positive”.

7. Write a program that checks if a number is even or odd.

8. Ask the user for their age. If age ≥ 18, print “You are an adult”, else print “You are a minor”.

9. Given three variables `x`, `y`, `z`, check which one is the greatest and print it.

10. Ask the user to input a temperature in Celsius. If the temperature is \> 30, print “Hot”, if it’s between 15 and 30 (inclusive), print “Warm”, else print “Cold”.

**Tutorial** for conditionals:

* Basic if/else: [Programiz – Python if…else Statement](https://www.programiz.com/python-programming/if-elif-else) ([programiz.com](https://www.programiz.com/python-programming/if-elif-else?utm_source=chatgpt.com))

* Deeper: [DigitalOcean – How to Use If/Else Statements in Python](https://www.digitalocean.com/community/tutorials/if-else-statements-in-python) ([DigitalOcean](https://www.digitalocean.com/community/tutorials/if-else-statements-in-python?utm_source=chatgpt.com))

---

### **Lists**

11. Create a list `fruits = ["apple", "banana", "cherry"]`. Print the first and last fruit.

12. Add a new fruit “orange” to the list.

13. Remove “banana” from the list.

14. Given a list of numbers `[1, 2, 3, 4, 5]`, calculate and print their sum.

15. Given a list of strings `["hello", "world"]`, join them into a single string with a space: “hello world”.

16. Reverse a list (without using the built-in reverse method).

17. Given a list `[1, 2, 3, 2, 1]`, count how many times `2` appears.

18. Write a program that takes a list of numbers from the user (comma separated), converts them into a list of integers, and prints only the even numbers.

**Tutorial** for lists:

* [Programiz – Python List](https://www.programiz.com/python-programming/list) ([programiz.com](https://www.programiz.com/python-programming/list?utm_source=chatgpt.com))

* Also: [AfterNerd – Python Lists (for absolute beginners)](https://www.afternerd.com/blog/python-lists-for-absolute-beginners/) ([afternerd.com](https://www.afternerd.com/blog/python-lists-for-absolute-beginners/?utm_source=chatgpt.com))

---

### **Tuples**

19. Create a tuple `t = (10, 20, 30, 40)`. Print its first element.

20. Try to change one element of the tuple (e.g., `t[0] = 5`) and observe what error you get.

21. Unpack the tuple `t = (1, 2, 3)` into three variables `a, b, c`.

22. Given a tuple of mixed types `("Alice", 25, True)`, print each element and its type.

**Tutorial** for tuples:

* [W3Schools – Python Tuples](https://www.w3schools.com/python/python_tuples.asp) ([W3Schools](https://www.w3schools.com/python/python_tuples.asp?utm_source=chatgpt.com))

* Additional data structures reference: [Dataquest – Python Data Structures (Lists, Dicts, Sets, Tuples)](https://www.dataquest.io/blog/data-structures-in-python/) ([Dataquest](https://www.dataquest.io/blog/data-structures-in-python/?utm_source=chatgpt.com))

---

### **Dictionaries**

23. Create a dictionary `student = {"name": "Alice", "age": 21, "major": "Math"}`. Print the student’s name.

24. Add a new key-value pair: `"GPA": 3.8`.

25. Change the `"age"` value to `22`.

26. Remove the `"major"` key from the dictionary.

27. Iterate over the dict and print keys and values in the form: `key -> value`.

28. Write a program that counts how many times each word appears in a list of words: `["apple", "banana", "apple", "cherry", "banana", "banana"]`.

**Tutorial** for dictionaries:

* [Real Python – Common Python Data Structures](https://realpython.com/python-data-structures/) ([Real Python](https://realpython.com/python-data-structures/?utm_source=chatgpt.com))

* Also covers dicts: [Dataquest – Python Data Structures: Lists, Dictionaries, Sets, Tuples](https://www.dataquest.io/blog/data-structures-in-python/) ([Dataquest](https://www.dataquest.io/blog/data-structures-in-python/?utm_source=chatgpt.com))

---

### **Sets**

29. Create a set `s = {1, 2, 3, 4}`. Try adding `2` again and print the set.

30. Given a list with duplicates `[1, 2, 2, 3, 3, 3]`, convert it to a set to remove duplicates.

31. Create another set `t = {3, 4, 5}`. Print the union, intersection, and difference (`s - t`).

32. Given a set `letters = {"a", "b", "c"}`, check if `"d"` is in the set, and print a message accordingly.

**Tutorial** for sets:

* [DataCamp – Python Sets vs Lists and Tuples](https://www.datacamp.com/tutorial/sets-in-python) ([DataCamp](https://www.datacamp.com/tutorial/sets-in-python?utm_source=chatgpt.com))

* And again refer to [Dataquest – Python Data Structures](https://www.dataquest.io/blog/data-structures-in-python/) ([Dataquest](https://www.dataquest.io/blog/data-structures-in-python/?utm_source=chatgpt.com))

---

### **Mixed Data Structures \+ Conditionals**

33. Given a dictionary `inventory = {"apples": 5, "bananas": 2, "oranges": 0}`, write code to print “We are out of oranges” if the count is 0, and otherwise print how many there are.

34. Create a list of dictionaries, e.g., `people = [{"name":"Alice","age":30}, {"name":"Bob","age":17}]`. Loop through it and print for each person whether they are adult or minor.

35. Given a tuple of numbers `nums = (5, 10, 15, 20)`, write a loop that checks: if the number is divisible by 10, print “Divisible by 10”, else “Not divisible by 10”.

36. Ask user to input three numbers and store them in a list. Then, convert the list to a set and check if any duplicates were removed; tell the user if there were duplicates.

37. Create a dictionary `grades = {"Alice": 85, "Bob": 72, "Charlie": 90}`. Loop through it and print: “Alice passed” or “Alice failed” assuming passing is ≥ 80\.

38. Given two lists `a = [1,2,3,4]` and `b = [3,4,5,6]`, use sets to find and print the common elements.

39. Given a list of numbers, ask the user to input the numbers, then compute: number of positive, negative, and zero values using conditionals.

40. Write a small program that asks the user to input their name, age, and a list of 3 favorite fruits (comma-separated). Store their data in a dictionary like `{"name": ..., "age": ..., "fruits": [...]}` and then print a summary: “Name: …, Age: …, Fruits: …”.

**Tutorial** (mixed concepts):

* Use the above tutorials together (lists, dicts, sets, conditionals) — e.g., [Dataquest – Python Data Structures](https://www.dataquest.io/blog/data-structures-in-python/) ([Dataquest](https://www.dataquest.io/blog/data-structures-in-python/?utm_source=chatgpt.com))

* For conditionals \+ data structures review: [DigitalOcean – If/Else Statements in Python](https://www.digitalocean.com/community/tutorials/if-else-statements-in-python) ([DigitalOcean](https://www.digitalocean.com/community/tutorials/if-else-statements-in-python?utm_source=chatgpt.com))

---

