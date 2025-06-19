# Data-Types-and-Structures
Data Types and Structures
1)	What are data structures, and why are they important?
Ans) Data structures are ways to organize and store data so we can use it efficiently. They help make programs faster and easier to understand.
________________________________________
2)	Explain the difference between mutable and immutable data types with examples.
Ans) Mutable means you can change the data (like a list).
        Example: my_list = [1, 2, 3] → You can do my_list[0] = 10
  Immutable means you can't change the data (like a tuple or string).
   Example: my_str = "hello" → You can't change just one letter.
________________________________________
3)	What are the main differences between lists and tuples in Python?
Ans) Feature	List	Tuple
Changeable	 Yes	 No
Syntax	[1, 2, 3]	(1, 2, 3)
Speed	Slower	Faster
Use case	When data changes	When data stays the same
________________________________________
4)	 Describe how dictionaries store data.
Ans) Dictionaries store data as key-value pairs.
Example: {"name": "Anand", "age": 25}
Each key (like "name") maps to a value (like "Anand").
________________________________________
5)	Why might you use a set instead of a list in Python?
Ans) Sets remove duplicates automatically.
They are faster for checking if something exists.
________________________________________
6)	What is a string in Python, and how is it different from a list?
Ans) A string is a sequence of characters (like "hello").
 A list can hold anything: numbers, strings, other lists.
 You can't change a string, but you can change a list.
________________________________________
7)	How do tuples ensure data integrity in Python?
Ans)  Tuples can't be changed, so once created, the data stays safe. This helps when you don’t want the data to accidentally change.
________________________________________
8)	What is a hash table, and how does it relate to dictionaries in Python?
Ans) A hash table is a system to store data for quick access.
Python dictionaries use hash tables to find values by their keys very fast.
________________________________________
9)	Can lists contain different data types in Python?
Ans) Yes, a list can have different data types.
Example: [1, "hello", True]
________________________________________
10)	 Explain why strings are immutable in Python.
Ans) Strings are immutable to make them safe and fast.
Changing them would be slow and could cause bugs in programs.
________________________________________
11)	What advantages do dictionaries offer over lists for certain tasks?
Ans) Fast lookup using keys
 Easy to label data (like "name": "Anand")
________________________________________
12)	 Describe a scenario where using a tuple would be preferable over a list.
Ans) Use a tuple when:
•	The data shouldn't change (e.g., days of the week)
•	You want to use it as a key in a dictionary
________________________________________
13)	 How do sets handle duplicate values in Python?
Ans) Sets ignore duplicate values automatically.
Example: set([1, 2, 2, 3]) → {1, 2, 3}
________________________________________
14)	 How does the “in” keyword work differently for lists and dictionaries?
Ans) In a list, in checks if a value is present.
   "apple" in ["apple", "banana"] →  True
In a dictionary, in checks if a key exists.
 "name" in {"name": "Anand"} → True
________________________________________
15)	 Can you modify the elements of a tuple? Explain why or why not?
Ans) No, you can’t change a tuple after it’s created. Tuples are immutable.
________________________________________
16)	 What is a nested dictionary, and give an example of its use case?
Ans) A nested dictionary is a dictionary inside another dictionary.
 Example:
student = {
 "name": "Anand",
  "marks": {"math": 90, "science": 85}
}
________________________________________
17)	 Describe the time complexity of accessing elements in a dictionary.
Ans) It’s usually O(1) — very fast, because of the hash table behind it.
________________________________________
18)	 In what situations are lists preferred over dictionaries?
As) Use a list when:
•	You just need ordered items
•	You don’t need key-value pairs
________________________________________
19)	Why are dictionaries considered unordered, and how does that affect data retrieval?
Ans) Before Python 3.7, dictionaries were unordered (no fixed order).
Now they keep insertion order, but you still access items by key, not by position.
________________________________________
20)	Explain the difference between a list and a dictionary in terms of data retrieval.
Ans) List: Access by position → my_list[0]
 Dictionary: Access by key → my_dict["name"]



