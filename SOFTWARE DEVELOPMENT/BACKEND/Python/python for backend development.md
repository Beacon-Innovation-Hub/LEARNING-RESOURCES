# Python Foundations

> Learn Python through videos, documentation, coding games, and logic-based problems drawn from economics, transport, trade, business, and everyday systems.

**Level:** Beginner → Intermediate  
**Prerequisite:** Basic computer literacy  
**Learning Model:** Watch → Read → Play → Reason → Code → Build → Defend  
**Next Stage:** Python for Backend Development

---

## Learning Philosophy

This pathway does not teach Python as a list of syntax rules.

Each concept should be connected to a problem that requires logical reasoning.

```text
REAL PROBLEM
     ↓
Identify Inputs
     ↓
Identify Rules
     ↓
Choose Data Structure
     ↓
Design Logic
     ↓
Write Python
     ↓
Test Cases
     ↓
Improve Solution
```

Typical problem domains include:

- Economics
- Transport
- Trade
- Logistics
- Retail
- Education
- Banking
- Public services
- Business operations

---

## Learning Path

1. [Python Setup & Basic Syntax](#1-python-setup--basic-syntax)
2. [Variables, Data Types & Operators](#2-variables-data-types--operators)
3. [Conditionals & Loops](#3-conditionals--loops)
4. [Functions](#4-functions)
5. [Core Data Structures](#5-core-data-structures)
6. [Exceptions & File Handling](#6-exceptions--file-handling)
7. [Modules, Packages & Environments](#7-modules-packages--environments)
8. [Object-Oriented Programming](#8-object-oriented-programming)
9. [Intermediate Python](#9-intermediate-python)
10. [Data Structures & Algorithms](#10-data-structures--algorithms)
11. [Typing, Testing & Code Quality](#11-typing-testing--code-quality)
12. [Python Foundations Competence Project](#12-python-foundations-competence-project)
13. [Next Learning Stage](#13-next-learning-stage)

---

# 1. Python Setup & Basic Syntax

**Level:** Beginner

## Learning Objectives

Understand:

- What Python is
- Installing Python
- Python interpreter
- Running `.py` files
- Indentation
- Comments
- `print()`
- `input()`
- Reading error messages
- Basic debugging

## Video Resource

[![Learn Python - Full Course for Beginners](https://img.youtube.com/vi/rfscVS0vtbw/maxresdefault.jpg)](https://www.youtube.com/watch?v=rfscVS0vtbw)

**[▶ Watch: Learn Python — Full Course for Beginners](https://www.youtube.com/watch?v=rfscVS0vtbw)**

For this section, focus on:

```text
Introduction
Installing Python
Hello World
Variables
Input
Basic calculator
```

## Documentation

- [Python Tutorial](https://docs.python.org/3/tutorial/)
- [Python Documentation](https://docs.python.org/3/)

## Game-Based Practice

### CodeCombat

**[Play CodeCombat →](https://codecombat.com/)**

Use Python to control a character by writing actual code.

At this stage, focus on:

- instructions
- sequencing
- variables
- simple expressions
- reading errors

---

## Logic Lab — Transport Fare Calculator

A local transport company charges passengers according to distance.

Assume:

```text
Base fare = R12
Cost per kilometre = R2.50
```

Write a program that asks for the travel distance and calculates the fare.

### Think Before Coding

```text
INPUT
Distance travelled

PROCESS
Base fare + distance × rate

OUTPUT
Total fare
```

Do not begin by writing Python.

First write the logic in plain English or pseudocode.

---

## Logic Lab — Currency Exchange

A trader purchases goods using South African rand but pays a supplier in another currency.

Your program should accept:

```text
Amount in ZAR
Exchange rate
```

and calculate the converted amount.

Then answer:

> What information would be required if the exchange rate changed every day?

---

# 2. Variables, Data Types & Operators

## Video Resource

Use the following sections of the main Python course:

**[▶ Variables & Data Types](https://www.youtube.com/watch?v=rfscVS0vtbw&t=923s)**  
**[▶ Working with Strings](https://www.youtube.com/watch?v=rfscVS0vtbw&t=1643s)**  
**[▶ Working with Numbers](https://www.youtube.com/watch?v=rfscVS0vtbw&t=2298s)**  
**[▶ Getting Input from Users](https://www.youtube.com/watch?v=rfscVS0vtbw&t=2906s)**

## Learn

```text
int
float
str
bool
None
```

Understand:

- Variables
- Naming conventions
- Assignment
- Type conversion
- `type()`
- Arithmetic operators
- Comparison operators
- Logical operators
- Membership operators

---

## Logic Lab — Economics: Profit & Loss

A small trader purchases 50 products at R80 each and sells each item at R110.

Calculate:

```text
Total cost
Total revenue
Profit
Profit per item
Profit percentage
```

Then modify the program so that the user supplies:

```text
Quantity
Purchase price
Selling price
```

### Higher-Order Question

What happens if some products are not sold?

Which additional variables would the program require?

---

## Logic Lab — Trade: Import Cost

A business imports products.

The total landed cost consists of:

```text
Product cost
+ Transport
+ Customs duty
+ Insurance
```

Write a program that calculates the final landed cost.

Then calculate the minimum selling price required to achieve a chosen profit margin.

---

# 3. Conditionals & Loops

## Video Resources

**[▶ If Statements](https://www.youtube.com/watch?v=rfscVS0vtbw&t=6006s)**  
**[▶ While Loops](https://www.youtube.com/watch?v=rfscVS0vtbw&t=8053s)**  
**[▶ For Loops](https://www.youtube.com/watch?v=rfscVS0vtbw&t=9144s)**

## Learn

```python
if
elif
else

for
while
range()
break
continue
```

## Game-Based Practice

### CheckiO

**[Play Python CheckiO →](https://py.checkio.org/)**

CheckiO provides Python missions that require learners to solve problems rather than simply repeat syntax.

Start with beginner missions involving:

- strings
- integers
- lists
- dictionaries
- conditions

### CodinGame

**[Explore CodinGame Python Challenges →](https://www.codingame.com/learn)**

Use beginner puzzles after understanding basic conditionals and loops.

---

## Logic Lab — Transport Ticket Pricing

A transport company uses the following rules:

```text
Age < 6          → Free
Age 6–17         → 30% discount
Age 18–59        → Normal fare
Age 60+          → 25% discount
```

Write a program that determines the passenger fare.

### Extension

Add:

```text
Student discount
Peak-hour surcharge
Weekend discount
```

You must decide how conflicting rules should be handled.

---

## Logic Lab — Economics: Progressive Tax

Create a simplified tax system:

```text
Income ≤ R5 000       → 0%
R5 001 – R10 000      → 10%
R10 001 – R20 000     → 15%
Above R20 000         → 20%
```

Determine the tax payable.

### Reasoning Question

Is applying one percentage to the entire income the same as a true progressive tax system?

Explain before changing the program.

---

## Logic Lab — Trade Inventory

A shop begins with 100 units.

Sales for five days are:

```python
sales = [12, 18, 7, 24, 15]
```

Use a loop to display the stock remaining after each day.

Trigger a warning when stock falls below 30 units.

---

# 4. Functions

## Video Resources

**[▶ Python Functions](https://www.youtube.com/watch?v=rfscVS0vtbw&t=5055s)**  
**[▶ Return Statements](https://www.youtube.com/watch?v=rfscVS0vtbw&t=5651s)**

## Learn

- Defining functions
- Parameters
- Arguments
- Return values
- Default arguments
- Keyword arguments
- Scope
- Docstrings

---

## Logic Principle

A function should usually represent a clear responsibility.

Instead of:

```text
do_everything()
```

think:

```text
calculate_fare()
calculate_tax()
calculate_profit()
validate_quantity()
```

---

## Logic Lab — Logistics Cost Engine

Create separate functions:

```python
calculate_transport_cost()
calculate_insurance()
calculate_customs_duty()
calculate_total_landed_cost()
```

The final function should reuse the others.

### Higher-Order Question

Why is this easier to test than placing every calculation inside one large function?

---

## Logic Lab — Route Fare Function

Create:

```python
def calculate_fare(distance, rate, base_fare):
    ...
```

Test it with at least five routes.

Include a zero-distance case and an invalid negative-distance case.

---

# 5. Core Data Structures

## Video Resources

**[▶ Lists](https://www.youtube.com/watch?v=rfscVS0vtbw&t=3790s)**  
**[▶ Tuples](https://www.youtube.com/watch?v=rfscVS0vtbw&t=4695s)**  
**[▶ Dictionaries](https://www.youtube.com/watch?v=rfscVS0vtbw&t=7633s)**

## Additional Video

**[▶ Corey Schafer — Lists, Tuples and Sets](https://www.youtube.com/watch?v=W8KRzm-HUcc)**

## Learn

### Lists

Use when you need an ordered, changeable collection.

### Tuples

Use when a sequence should not normally change.

### Sets

Use when uniqueness or membership matters.

### Dictionaries

Use when information is naturally represented as key-value pairs.

---

## Game Practice

Continue with:

- [CheckiO](https://py.checkio.org/)
- [CodinGame](https://www.codingame.com/learn)

Do not select a data structure randomly.

For each problem ask:

```text
Do I need order?
Do I need duplicates?
Will values change?
Do I need fast lookup by a key?
Do I need uniqueness?
```

---

## Logic Lab — Transport Network

Represent routes:

```python
routes = {
    "Empangeni-RichardsBay": 22,
    "Empangeni-Eshowe": 45,
    "RichardsBay-Durban": 170
}
```

Build a program that:

1. Displays available routes.
2. Allows the user to select one.
3. Retrieves the distance.
4. Calculates the fare.

---

## Logic Lab — Trade Orders

Represent orders using a list of dictionaries:

```python
orders = [
    {
        "product": "Laptop",
        "quantity": 3,
        "unit_price": 8500
    },
    {
        "product": "Router",
        "quantity": 10,
        "unit_price": 950
    }
]
```

Calculate:

- value of each order
- total trade value
- highest-value order
- total quantity of products

---

## Logic Lab — Duplicate Customers

A business has:

```python
customers_a = {"A", "B", "C", "D"}
customers_b = {"C", "D", "E", "F"}
```

Use sets to determine:

- customers appearing in both datasets
- customers appearing only in the first
- all unique customers

Explain why a set is more appropriate than a list for this problem.

---

# 6. Exceptions & File Handling

## Video Resources

**[▶ Try / Except](https://www.youtube.com/watch?v=rfscVS0vtbw&t=11057s)**  
**[▶ Reading Files](https://www.youtube.com/watch?v=rfscVS0vtbw&t=11561s)**  
**[▶ Writing Files](https://www.youtube.com/watch?v=rfscVS0vtbw&t=12086s)**

## Learn

```python
try
except
else
finally
raise
```

Understand:

```text
TypeError
ValueError
KeyError
IndexError
FileNotFoundError
```

Practice:

```text
TXT
CSV
JSON
```

---

## Logic Lab — Trade Transaction File

Create:

```text
transactions.csv
```

containing:

```text
transaction_id,product,quantity,unit_price
T001,Rice,10,120
T002,Oil,5,95
T003,Sugar,abc,40
```

Your program should:

```text
Read
 ↓
Validate
 ↓
Calculate
 ↓
Separate Invalid Records
 ↓
Report
```

The invalid quantity must not crash the entire application.

### Reasoning Question

Should the invalid record be deleted, ignored, corrected automatically, or reported?

Defend your decision.

---

# 7. Modules, Packages & Environments

## Video Resource

**[▶ Modules & Pip](https://www.youtube.com/watch?v=rfscVS0vtbw&t=12508s)**

## Learn

```python
import
from ... import ...
```

Understand:

- Built-in modules
- Custom modules
- Packages
- `__name__`
- `__main__`
- PyPI
- `pip`
- `venv`
- `requirements.txt`
- `pyproject.toml`

## Documentation

- [Python Modules](https://docs.python.org/3/tutorial/modules.html)
- [Python venv](https://docs.python.org/3/library/venv.html)
- [Python Packaging User Guide](https://packaging.python.org/)

---

## Logic Lab — Logistics Application Refactor

Take a previous transport/trade program and split it into:

```text
logistics/
├── main.py
├── fares.py
├── routes.py
├── validation.py
└── reports.py
```

Each module must have a clear responsibility.

### Reasoning Question

If the fare calculation changes, how many files should normally need modification?

---

# 8. Object-Oriented Programming

## Video Resources

**[▶ Classes & Objects](https://www.youtube.com/watch?v=rfscVS0vtbw&t=13436s)**  
**[▶ Inheritance](https://www.youtube.com/watch?v=rfscVS0vtbw&t=15163s)**

### Additional OOP Resource

**[▶ Real Python — Composition and Inheritance](https://www.youtube.com/watch?v=L4v9gKC7QxY)**

## Learn

- Classes
- Objects
- Attributes
- Methods
- Constructors
- `self`
- Encapsulation
- Inheritance
- Polymorphism
- Composition
- Class methods
- Static methods
- Dunder methods

---

## Logic Lab — Transport System

Design:

```text
Vehicle
Bus
Taxi
Route
Passenger
Trip
```

Before coding, determine relationships.

Ask:

```text
Is Bus a Vehicle?
Does a Trip have a Route?
Does a Trip have Passengers?
Should Passenger inherit from Vehicle?
```

Use inheritance only where an **is-a** relationship is logical.

Use composition where a **has-a** relationship is more appropriate.

---

## Logic Lab — International Trade

Create:

```text
Product
Supplier
Order
Shipment
Customer
```

A `Shipment` may contain multiple products.

An `Order` belongs to a customer.

A supplier can provide multiple products.

Model these relationships in Python.

---

# 9. Intermediate Python

## Recommended Topics

Study:

- List comprehensions
- Dictionary comprehensions
- Lambda functions
- Iterators
- Generators
- Decorators
- Context managers
- Regular expressions

## Documentation

- [Python Functional Programming HOWTO](https://docs.python.org/3/howto/functional.html)
- [Python Regular Expressions](https://docs.python.org/3/library/re.html)

---

## Logic Lab — Large Transport Dataset

Imagine one million transport records.

Compare:

```python
records = [process(row) for row in source]
```

with a generator-based approach.

Explain:

- memory implications
- when values are produced
- why generators can be useful

---

## Logic Lab — Trade Filtering

Given a list of transactions, use comprehensions to produce:

```text
High-value transactions
International transactions
Transactions above a chosen quantity
```

Then rewrite one comprehension as a normal loop.

Explain which version is easier to read.

---

# 10. Data Structures & Algorithms

## Video / Course Resource

**[▶ Codebasics — Data Structures & Algorithms in Python Playlist](https://www.youtube.com/playlist?list=PLeo1K3hjS3uu_n_a__MI_KktGTLYopZ12)**

The course combines data structures, algorithms, Big-O analysis, and exercises.

## Learn

- Arrays
- Linked lists
- Stacks
- Queues
- Hash tables
- Heaps
- Trees
- Binary search trees

Study:

- Linear search
- Binary search
- Sorting
- Recursion
- Time complexity
- Space complexity
- Big-O notation

---

## Game / Challenge Practice

### CheckiO

**[Solve Python Missions →](https://py.checkio.org/)**

### CodinGame

**[Solve Programming Puzzles →](https://www.codingame.com/learn)**

At this stage, do not only solve a challenge.

For selected problems, also explain:

```text
Input size
Chosen algorithm
Time complexity
Space complexity
Alternative approach
```

---

## Logic Lab — Transport Queue

Passengers arrive at a bus station in order.

Model boarding using a queue.

Questions:

1. Why is a queue appropriate?
2. What would go wrong if passengers were removed randomly?
3. What happens when the bus reaches capacity?

---

## Logic Lab — Trade Price Search

A company stores thousands of sorted product prices.

Compare:

```text
Linear Search
vs
Binary Search
```

Test both on increasingly large datasets.

Explain why the number of operations matters.

---

## Logic Lab — Delivery Route Priority

Deliveries have different urgency levels.

Use a priority queue concept so that urgent deliveries are processed before ordinary deliveries.

Discuss whether arrival order should still matter when priorities are equal.

---

# 11. Typing, Testing & Code Quality

## Learn

### Type Hints

```python
def calculate_average(scores: list[int]) -> float:
    return sum(scores) / len(scores)
```

Become familiar with:

```text
mypy
pyright
```

### Testing

Study:

```text
unittest
pytest
```

### Code Quality

Become familiar with:

```text
Black
Ruff
```

### Logging

Study:

```python
logging
```

## Documentation

- [Python unittest](https://docs.python.org/3/library/unittest.html)
- [pytest Documentation](https://docs.pytest.org/)
- [Python logging](https://docs.python.org/3/library/logging.html)
- [Python typing](https://docs.python.org/3/library/typing.html)

---

## Logic Lab — Test an Economic Model

Create:

```python
calculate_profit(cost, revenue)
```

Test:

```text
Normal profit
Zero profit
Loss
Zero cost
Negative input
Very large values
```

The objective is to learn that passing one test does not prove that a function is correct.

---

## Logic Lab — Transport Fare Boundary Testing

Suppose:

```text
Child discount applies below age 18.
Senior discount applies from age 60.
```

Test:

```text
17
18
59
60
```

Explain why boundary values are important.

---

# 12. Python Foundations Competence Project

## Scenario — Regional Trade & Transport Management System

A regional business purchases products from suppliers, transports them between towns, stores inventory, and sells products to customers.

Management currently performs calculations manually.

Build a **Python command-line application** that models the core operations.

Do not use Django, Flask, FastAPI or another web framework.

---

## Required Modules

### 1. Products

Store:

```text
Product ID
Name
Category
Purchase Price
Selling Price
Quantity
```

### 2. Suppliers

Store:

```text
Supplier ID
Name
Country / Region
Products Supplied
```

### 3. Transport

Store:

```text
Route
Distance
Vehicle
Cost per kilometre
Shipment weight
```

Calculate estimated transport cost.

### 4. Trade

Record:

```text
Purchase
Sale
Quantity
Price
Date
```

### 5. Economics

Calculate:

```text
Revenue
Cost
Gross profit
Profit margin
Inventory value
Transport expenditure
```

---

## Business Questions

The program should be able to answer:

1. Which product generates the highest revenue?
2. Which product generates the highest profit?
3. Which route costs the most?
4. Which supplier provides the greatest value of goods?
5. Which products need restocking?
6. What is the total inventory value?
7. What happens to profit if transport costs increase by 15%?
8. What happens if selling prices decrease by 10%?
9. Which orders should be prioritized?
10. Which records contain invalid information?

---

## Required Python Concepts

Your solution must appropriately demonstrate:

- Variables
- Data types
- Operators
- Conditionals
- Loops
- Functions
- Lists
- Tuples
- Sets
- Dictionaries
- File handling
- Exceptions
- Modules
- Classes
- Composition/inheritance where justified
- Comprehensions
- Type hints
- Automated tests
- Logging

---

## Repository Structure

```text
python-foundations-capstone/
├── src/
│   ├── main.py
│   ├── models.py
│   ├── trade.py
│   ├── transport.py
│   ├── economics.py
│   ├── storage.py
│   └── validation.py
├── data/
│   ├── products.json
│   ├── suppliers.json
│   └── transactions.csv
├── tests/
│   ├── test_trade.py
│   ├── test_transport.py
│   └── test_economics.py
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Competence Assessment

| Area | Weight |
|---|---:|
| Python fundamentals | 15% |
| Logical problem solving | 20% |
| Functions & program structure | 10% |
| Data structures | 10% |
| OOP | 10% |
| Files & exceptions | 10% |
| Testing & debugging | 10% |
| Code quality | 5% |
| Business/economic reasoning | 5% |
| Documentation | 5% |

**Recommended progression requirement: 70%**

---

# Technical Defence

The participant should be able to answer:

1. Why did you choose this data structure?
2. Why is this a dictionary instead of a list?
3. What happens if transport cost doubles?
4. How is profit calculated?
5. What happens when inventory reaches zero?
6. How are invalid transactions handled?
7. Why did you create this function?
8. Why did you create this class?
9. Where did you use composition?
10. Could inheritance be removed?
11. What happens when the transaction file contains 1 million rows?
12. Which algorithm becomes inefficient as data grows?
13. Which boundary cases did you test?
14. How would the application change if data came from a database?
15. What would you refactor before adding a web API?

---

# Recommended Game Progression

Use games as reinforcement, not as a replacement for projects.

| Stage | Platform | Purpose |
|---|---|---|
| First Python programs | [CodeCombat](https://codecombat.com/) | Syntax, sequencing and beginner logic |
| Conditions & collections | [CheckiO](https://py.checkio.org/) | Python problem-solving missions |
| Algorithms & problem solving | [CodinGame](https://www.codingame.com/learn) | Logic and programming puzzles |
| Intermediate practice | [CheckiO](https://py.checkio.org/) | More difficult Python missions |

Recommended cycle:

```text
WATCH
  ↓
CODE EXAMPLE
  ↓
PLAY 3–5 CHALLENGES
  ↓
SOLVE REAL-WORLD PROBLEM
  ↓
EXPLAIN YOUR LOGIC
  ↓
REFACTOR
```

---

# 13. Next Learning Stage

After demonstrating Python foundations competence:

```text
Python Foundations
        ↓
HTTP & Web Fundamentals
        ↓
Python Backend Foundations
        ↓
Django
        ↓
PostgreSQL
        ↓
REST APIs
        ↓
Authentication & Security
        ↓
Testing
        ↓
Production Backend Engineering
        ↓
BIH Junior Backend Developer
```

Do not rush into Django before being able to solve ordinary Python problems independently.

---

> **Learning Principle:** A learner should not ask only, “Which Python syntax do I need?” The stronger question is, “What is the problem, what are the rules, what data do I have, and what logic produces the correct result?”
