## MCQ - 41 Mcq - Any 35 - (35 Marks)

1. What will be the output of `print({1, 2, 3} & {2, 3, 4})`?
   - A) `{1, 2, 3, 4}`
   - B) `{2, 3}`
   - C) `{1, 4}`
   - D) `Error`

2. What does the following code output: `list(enumerate([1,2,3,4,5,6,7]))`?
   - A) `[(1, 3), (2, 4), (None, 5)]`
   - B) `[(1,1),(2,2),(3,3),(4,4),(5,5),(6,6),(7,7)]`
   - C) `[(0,1),(1,2),(2,3),(3,4),(4,5),(5,6),(6,7)]`
   - D) `Error`

3. Which statement about Python tuples is incorrect?
   - A) Tuples are immutable.
   - B) Tuples can contain duplicate elements.
   - C) Tuples are unhashable.
   - D) Tuples maintain order.

4. Given `a = [1, 2, 3, 4]`, what does `a[-3:]` return?
   - A) `[1, 2, 3]`
   - B) `[2, 3, 4]`
   - C) `[3, 4]`
   - D) `[2, 3]`

5. What is the output of the following code: `d = {"a": 1}; d["b"]`?
   - A) `None`
   - B) `Error`
   - C) `KeyError`
   - D) `{}`

6. What will the code `a = {1: "A"}; a.setdefault(1, "B")` return?
   - A) `{"1": "B"}`
   - B) `None`
   - C) `A`
   - D) `Error`

7. What will the following code output: `x = (1, 2, [3, 4]); x[2][0] = 5`?
   - A) `(1, 2, [5, 4])`
   - B) `TypeError`
   - C) `(1, 2, (5, 4))`
   - D) `Error`

8. What does the following code print: `for x in range(1, 5, 2): print(x)`?
   - A) `1, 3, 5`
   - B) `1, 3`
   - C) `2, 4`
   - D) `Error`

9. What is the difference between `set([1, 2, 3, 1])` and `{1, 2, 3, 1}`?
   - A) No difference
   - B) `set([1, 2, 3, 1])` is unordered
   - C) `{1, 2, 3, 1}` gives an error
   - D) `set([1, 2, 3, 1])` is a list

10. In Python, how does `deepcopy()` differ from `copy()`?
   - A) `deepcopy()` only copies immutable elements
   - B) `deepcopy()` copies nested elements
   - C) Both are the same
   - D) `copy()` is recursive

11. Which method adds an element to a dictionary if the key does not already exist?
   - A) `update()`
   - B) `add()`
   - C) `append()`
   - D) `setdefault()`

12. What will `print("".join(["hello", "world"]))` output?
   - A) `"hello world"`
   - B) `"helloworld"`
   - C) `"hell oworld"`
   - D) `Error`

13. Which of these is a mutable type?
   - A) Tuple
   - B) Integer
   - C) Set
   - D) String

14. What will `sum(range(5), 10)` return?
   - A) `10`
   - B) `20`
   - C) `15`
   - D) `25`

15. What does the `enumerate` function return?
   - A) Pairs of index and element
   - B) Keys and values
   - C) Length of list
   - D) Index of an element

16. What will the following code output?
   ```python
   a = [1, 2, 3]
   b = a
   b[0] = 10
   print(a)
   ```
   - A) `[10, 2, 3]`
   - B) `[1, 2, 3]`
   - C) `Error`
   - D) `[0, 2, 3]`

17. What does `d = {"a": 1}; d.pop("b")` return?
   - A) `1`
   - B) `None`
   - C) `KeyError`
   - D) `{}`

18. What will the output be for `s = {1, 2, 3}; s.discard(4)`?
   - A) `Error`
   - B) `{1, 2, 3}`
   - C) `{1, 2}`
   - D) `{1, 3, 4}`

19. Which of these methods is NOT available in a dictionary?
   - A) `update()`
   - B) `append()`
   - C) `pop()`
   - D) `get()`

20. Which of the following statements will raise an error?
   - A) `{1, 2, 3} | {4, 5}`
   - B) `frozenset([1, 2]).add(3)`
   - C) `set("abc")`
   - D) `frozenset([1, 2])`

21. What will `print({True: "A", 1: "B", False: "C", 0: "D"})` output?
   - A) `{"A", "B", "C", "D"}`
   - B) `{True: "A", False: "C"}`
   - C) `{"A": "True", "B": "1", "C": "False", "D": "0"}`
   - D) `{"B", "D"}`

22. What does `a = (5); type(a)` return?
   - A) `tuple`
   - B) `int`
   - C) `list`
   - D) `set`

23. How can you convert a list to a tuple in Python?
   - A) `tuple([1, 2, 3])`
   - B) `(1, 2, 3).tuple()`
   - C) `convert((1, 2, 3))`
   - D) `to_tuple([1, 2, 3])`

24. Which Python object does not support item assignment?
   - A) List
   - B) Set
   - C) Dictionary
   - D) Tuple

25. What will be the output of `print({1, 2, 3, 1})`?
   - A) `{1, 2, 3}`
   - B) `{1, 1, 2, 3}`
   - C) `{1, 2, 3, 1}`
   - D) `Error`

26. What is the output of the following code?
    ```python
    x = [1, 2, 3]
    print(x * 2)
    ```
    - A) `[1, 2, 3, 1, 2, 3]`
    - B) `[2, 4, 6]`
    - C) `Error`
    - D) `(1, 2, 3, 1, 2, 3)`

27. What will `print({x: x*x for x in range(3)})` output?
    - A) `{0: 1, 1: 4, 2: 9}`
    - B) `{0: 0, 1: 1, 2: 4}`
    - C) `{0: 0, 1: 1, 2: 2}`
    - D) `{0: 0, 1: 1, 2: 4}`

28. What will `print("Python"[::-1])` output?
    - A) `Python`
    - B) `nohtyP`
    - C) `Error`
    - D) `nohty P`

29. What is the output of the code below?
    ```python
    def func(x=[]):
        x.append(1)
        return x
    print(func())
    print(func())
    ```
    - A) `[1] [1]`
    - B) `[1, 1] [1, 1]`
    - C) `[1] [1, 1]`
    - D) `Error`

30. Which statement correctly initializes a dictionary with keys `1`, `2`, and `3`, and default value `0`?
    - A) `dict.fromkeys([1, 2, 3], 0)`
    - B) `{1: 0, 2: 0, 3: 0}`
    - C) `defaultdict(int, [1, 2, 3])`
    - D) `a = {1, 2, 3: 0}`

31. What is the output of the following code?
    ```python
    a = (1, 2, 3)
    a += (4, 5)
    print(a)
    ```
    - A) `(1, 2, 3)`
    - B) `(1, 2, 3, 4, 5)`
    - C) `(4, 5)`
    - D) `Error`

32. What is the output of `print(bool(set()))`?
    - A) `True`
    - B) `False`
    - C) `None`
    - D) `Error`

33. What will the following code output?
    ```python
    a = [1, 2, 3]
    print(len(a) and a[0])
    ```
    - A) `1`
    - B) `3`
    - C) `True`
    - D) `Error`

34. What will `print({1, 2, 3}.issuperset({2, 3, 4}))` return?
    - A) `True`
    - B) `False`
    - C) `None`
    - D) `Error`

35. Which code snippet will merge two dictionaries, `d1 = {'a': 1}` and `d2 = {'b': 2}`?
    - A) `d1 + d2`
    - B) `d1 | d2`
    - C) `{**d1, **d2}`
    - D) `merge(d1, d2)`

36. What does `sorted(["hello", "world"], key=len)` return?
    - A) `["hello", "world"]`
    - B) `["world", "hello"]`
    - C) `["hello"]`
    - D) `Error`

37. Which method removes an item from a dictionary by key?
    - A) `delete()`
    - B) `discard()`
    - C) `remove()`
    - D) `pop()`

38. What will `print(any([0, "", None, False]))` output?
    - A) `True`
    - B) `False`
    - C) `None`
    - D) `Error`

39. Which Python function can reverse a list in place?
    - A) `reversed()`
    - B) `reverse()`
    - C) `[::-1]`
    - D) `revert()`

40. What is the result of `a = [1, 2, 3]; print(a[3:])`?
    - A) `[]`
    - B) `Error`
    - C) `[1, 2, 3]`
    - D) `None`

41. What will the output be for the following code?
    ```python
    a = {1, 2, 3}
    b = frozenset([3, 4, 5])
    print(a | b)
    ```
    - A) `{1, 2, 3, 4, 5}`
    - B) `{3, 4, 5}`
    - C) `Error`
    - D) `{1, 2, 3, 4, 5, 3, 4, 5}`
   
Coding Questions : ( Any 7 ) - 35 Marks

1. **Function to Check Prime and Armstrong Number**

   Write a function that checks if a given number is both a prime number and an Armstrong number. The function should return a dictionary with the keys `"prime"` and `"armstrong"`, and their respective boolean values.

   **Sample Input:**
   ```python
   check_prime_armstrong(153)
   ```

   **Sample Output:**
   ```python
   {"prime": False, "armstrong": True}
   ```

---

2. **Class with Initialization and Methods**

   Create a class `Employee` with an `__init__` method that takes `name`, `age`, `salary`, and `designation` as arguments. Implement three methods:
   - `get_details()` - Returns a dictionary of employee details.
   - `update_salary(new_salary)` - Updates the employee's salary.
   - `is_senior()` - Returns `True` if the employee's age is 50 or above.

   **Sample Input:**
   ```python
   emp = Employee("Alice", 45, 60000, "Manager")
   print(emp.get_details())
   emp.update_salary(70000)
   print(emp.is_senior())
   ```

   **Sample Output:**
   ```python
   {"name": "Alice", "age": 45, "salary": 60000, "designation": "Manager"}
   False
   ```

---

3. **Function to Check Palindrome and Even/Odd**

   Write a function that takes an integer as input and checks if it is a palindrome and whether it is even or odd. The function should return a dictionary with the keys `"palindrome"` and `"even"`, and their respective boolean values.

   **Sample Input:**
   ```python
   check_palindrome_even(121)
   ```

   **Sample Output:**
   ```python
   {"palindrome": True, "even": False}
   ```

---

4. **Class for Bank Account Management**

   Create a class `BankAccount` with an `__init__` method that takes `account_number`, `name`, and `balance`. Implement three methods:
   - `deposit(amount)` - Adds the amount to the balance.
   - `withdraw(amount)` - Subtracts the amount from the balance if sufficient funds are available.
   - `get_balance()` - Returns the current balance.

   **Sample Input:**
   ```python
   account = BankAccount("12345678", "John Doe", 1000)
   account.deposit(500)
   account.withdraw(200)
   account.get_balance()
   ```

   **Sample Output:**
   ```python
   1300
   ```

---

5. **Function to Check Perfect Number and Divisibility by 10**

   Write a function that takes an integer as input and checks if it is a perfect number and divisible by 10. The function should return a dictionary with the keys `"perfect_number"` and `"divisible_by_10"`, and their respective boolean values.

   **Sample Input:**
   ```python
   check_perfect_divisible(28)
   ```

   **Sample Output:**
   ```python
   {"perfect_number": True, "divisible_by_10": False}
   ```

---

6. **Class for Student Management**

   Create a class `Student` with an `__init__` method that takes `name`, `age`, and `marks`. Implement three methods:
   - `get_grade()` - Returns the grade based on marks (A for 90+, B for 75-89, C for 50-74, and F below 50).
   - `is_pass()` - Returns `True` if marks are 50 or above.
   - `update_marks(new_marks)` - Updates the student's marks.

   **Sample Input:**
   ```python
   student = Student("Tom", 20, 85)
   print(student.get_grade())
   print(student.is_pass())
   student.update_marks(45)
   ```

   **Sample Output:**
   ```python
   "B"
   True
   ```

Here are six coding questions of hard difficulty, including the two you provided. Each question includes a sample input and output.

---

7. **Check if a Number is Prime and Armstrong**

   Write a function that checks if a given number is both a prime number and an Armstrong number. The function should return a dictionary with keys `"prime"` and `"Armstrong"` and values as Booleans.

   **Sample Input:**
   ```python
   check_number(153)
   ```

   **Sample Output:**
   ```python
   {"prime": False, "Armstrong": True}
   ```

---

2. **Class with Initialization and Multiple Methods**

   Write a class that initializes with name, age, salary, and designation. Add three methods: one to give a raise in salary, another to update the designation, and the third to display the employee's information.

   **Sample Input:**
   ```python
   emp = Employee("Alice", 30, 50000, "Engineer")
   emp.give_raise(5000)
   emp.update_designation("Senior Engineer")
   emp.display_info()
   ```

   **Sample Output:**
   ```python
   {"name": "Alice", "age": 30, "salary": 55000, "designation": "Senior Engineer"}
   ```

---

8. **Find All Anagrams in a List of Strings**

   Write a function that takes a list of strings and returns a list of groups, where each group contains strings that are anagrams of each other. Each group should only appear once in the result.

   **Sample Input:**
   ```python
   find_anagrams(["eat", "tea", "tan", "ate", "nat", "bat"])
   ```

   **Sample Output:**
   ```python
   [["eat", "tea", "ate"], ["tan", "nat"], ["bat"]]
   ```
