# 💻 C Programming – Learning Journey

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c" />
  <img src="https://img.shields.io/badge/Level-Beginner-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Programming%20Fundamentals-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Actively%20Learning-orange?style=for-the-badge" />
</p>

<p align="center">
  <i>A journey towards mastering programming fundamentals, strengthening logical thinking, and developing problem-solving skills through C.</i>
</p>

---

## 📌 About This Repository

Welcome to my **C Programming Learning Journey!**

This repository represents my journey of learning **C programming from scratch**, documenting every concept, coding exercise, and practical implementation along the way.

As part of my programming journey, I am focusing on building a strong foundation in programming concepts and improving my ability to solve problems through logical thinking.

### 🎯 Objectives

- Understand the fundamentals of C programming.
- Develop strong logical and analytical thinking.
- Practise coding through hands-on exercises.
- Improve problem-solving and debugging skills.
- Build confidence in writing and understanding programs.
- Maintain a structured record of my programming progress.

**Every concept is supported by explanations, source code, practical examples, and sample outputs.**

---

## 📚 Table of Contents

1. [Introduction to C Programming](#1-introduction-to-c-programming)
2. [Features of C](#2-features-of-c)
3. [Structure of a C Program](#3-structure-of-a-c-program)
4. [Variables and Constants](#4-variables-and-constants)
5. [Data Types](#5-data-types)
6. [Operators](#6-operators)
7. [Input and Output](#7-input-and-output)
8. [Conditional Statements](#8-conditional-statements)
9. [Looping Statements](#9-looping-statements)
10. [Pattern Programming](#10-pattern-programming)
11. [Arrays](#11-arrays)
12. [Practical Programs](#12-practical-programs)
13. [Repository Structure](#13-repository-structure)
14. [Learning Progress](#14-learning-progress)
15. [Skills Developed](#15-skills-developed)
16. [Future Learning Goals](#16-future-learning-goals)
17. [Connect With Me](#17-connect-with-me)

---

## 1. Introduction to C Programming

**C** is a general-purpose, procedural programming language developed by **Dennis Ritchie** at Bell Laboratories.

It is widely used in system programming, operating systems, embedded systems, and application development.

**Topics Covered:**
- History and introduction to C.
- Importance of programming languages.
- Compilation and execution.
- Basic programming concepts.

## 2. Features of C

C is one of the most popular programming languages because of its efficiency, flexibility, and simplicity.

**Key Features:**

- Simple and efficient.
- Portable across different platforms.
- Structured programming approach.
- Fast execution.
- Rich set of operators.
- Supports low-level memory operations.
- Extensive standard library support.

## 3. Structure of a C Program

A C program follows a standard structure that allows the compiler to understand and execute instructions.

**Example:**

```c
#include <stdio.h>

int main()
{
    printf("Hello World");

    return 0;
}
```

**Concepts Learned:**
- Header files.
- `main()` function.
- Statements and expressions.
- Curly braces `{ }`.
- Semicolons.
- Return statement.

## 4. Variables and Constants

A **variable** is a named memory location used to store data that can change during program execution.

A **constant** is a fixed value that cannot be changed during program execution.

**Concepts Covered:**
- Variable declaration.
- Variable initialization.
- Naming conventions.
- Assigning values.
- Constants using `const`.

## 5. Data Types

Data types specify the kind of information a variable can store.

| Data Type | Description | Example |
|---|---|---|
| `int` | Integer values | `int age = 20;` |
| `float` | Decimal values | `float price = 25.5;` |
| `double` | Higher-precision decimal values | `double value = 45.678;` |
| `char` | Single character | `char grade = 'A';` |

**Concepts Covered:**
- Basic data types.
- Variable declaration.
- Assigning values.
- Understanding data storage.

## 6. Operators

Operators are special symbols used to perform operations on variables and values.

**Types of Operators:**

**1. Arithmetic Operators**

Used for mathematical calculations.

`+` Addition | `-` Subtraction | `*` Multiplication | `/` Division | `%` Modulus

**2. Relational Operators**

Used to compare two values.

`==` | `!=` | `>` | `<` | `>=` | `<=`

**3. Logical Operators**

Used to combine multiple conditions.

`&&` Logical AND | `||` Logical OR | `!` Logical NOT

**4. Assignment Operators**

Used to assign or update variable values.

`=` | `+=` | `-=` | `*=` | `/=`

**5. Increment and Decrement Operators**

Used to increase or decrease a variable by one.

`++` Increment | `--` Decrement

## 7. Input and Output

Input and output functions allow users to interact with a C program.

| Function | Purpose |
|---|---|
| `printf()` | Displays output |
| `scanf()` | Accepts user input |

**Example:**

```c
#include <stdio.h>

int main()
{
    int age;

    printf("Enter your age: ");
    scanf("%d", &age);

    printf("Your age is %d", age);

    return 0;
}
```

## 8. Conditional Statements

Conditional statements help a program make decisions based on specified conditions.

**Topics Covered:**
- `if` statement.
- `if-else` statement.
- Nested `if`.
- `else-if` ladder.
- `switch` statement.

**Practical Applications:**
- Checking even or odd numbers.
- Finding the largest number.
- Checking positive or negative values.
- Grade calculation.

## 9. Looping Statements

Loops are used to execute a block of code repeatedly until a particular condition is satisfied.

**Types of Loops:**
- `for` loop.
- `while` loop.
- `do-while` loop.
- Nested loops.

**Loop Control Statements:**
- `break`.
- `continue`.

## 10. Pattern Programming

Pattern programming involves arranging stars, numbers, or characters using loops.

It helps improve logical thinking and understanding of nested loops.

**Patterns Practised:**
- Square star pattern.
- Right-angled triangle.
- Inverted triangle.
- Number triangle.
- Pyramid pattern.
- Diamond pattern.

**Example:**

```c
#include <stdio.h>

int main()
{
    int row, col;

    for(row = 0; row < 5; row++)
    {
        for(col = 0; col <= row; col++)
        {
            printf("* ");
        }

        printf("\n");
    }

    return 0;
}
```

**Sample Output:**

```text
*
* *
* * *
* * * *
* * * * *
```

## 11. Arrays

An array is a collection of elements of the same data type stored in consecutive memory locations.

**Concepts Covered:**
- Array declaration.
- Array initialization.
- Accessing array elements.
- One-dimensional arrays.
- Basic array operations.

**Example:**

```c
#include <stdio.h>

int main()
{
    int arr[5] = {10, 20, 30, 40, 50};

    for(int i = 0; i < 5; i++)
    {
        printf("%d ", arr[i]);
    }

    return 0;
}
```

**Output:**

```text
10 20 30 40 50
```

## 12. Practical Programs

This repository includes practical coding exercises to apply the concepts learned.

**Programs Practised:**

| No. | Program |
|---|---|
| 01 | Hello World |
| 02 | Addition of Two Numbers |
| 03 | Basic Arithmetic Operations |
| 04 | Even or Odd Number |
| 05 | Positive or Negative Number |
| 06 | Largest of Two Numbers |
| 07 | Largest of Three Numbers |
| 08 | Multiplication Table |
| 09 | Factorial of a Number |
| 10 | Sum of Natural Numbers |
| 11 | Star Pattern Programs |
| 12 | Number Pattern Programs |
| 13 | Basic Array Programs |

Each program is maintained with its source code and sample output wherever applicable.

---

## 13. Repository Structure

```text
C-Learning-Journey/
│
├── README.md
│
├── Day-01/
│   ├── README.md
│   ├── hello_world.c
│   ├── variables.c
│   ├── datatypes.c
│   ├── operators.c
│   └── basic_programs.c
│
├── Day-02/
│   └── README.md
│
├── Patterns/
│   ├── square_pattern.c
│   ├── triangle_pattern.c
│   └── number_pattern.c
│
└── Arrays/
    ├── array_input.c
    └── array_output.c
```

*The repository structure will continue to expand as I explore and practise new programming concepts.*

---

## 14. Learning Progress

I believe in tracking progress consistently and improving one concept at a time.

| No. | Topic | Status |
|---|---|---|
| 01 | Introduction to C | ✅ Completed |
| 02 | Structure of C Program | ✅ Completed |
| 03 | Variables and Constants | 🔄 Learning |
| 04 | Data Types | 🔄 Learning |
| 05 | Operators | 🔄 Learning |
| 06 | Input and Output | 🔄 Learning |
| 07 | Conditional Statements | ⏳ Upcoming |
| 08 | Looping Statements | ⏳ Upcoming |
| 09 | Pattern Programming | ⏳ Upcoming |
| 10 | Arrays | ⏳ Upcoming |

*Progress will be updated as I complete each topic and practical exercise.*

---

## 15. Skills Developed

Through this learning journey, I aim to strengthen the following skills:

- **Programming Fundamentals** – Understanding the basics of writing programs.
- **Logical Thinking** – Developing step-by-step problem-solving approaches.
- **Problem Solving** – Converting problems into programming solutions.
- **Debugging** – Identifying and correcting programming errors.
- **Algorithmic Thinking** – Understanding the logic behind program execution.
- **Practical Coding** – Gaining hands-on programming experience.

---

## 16. Future Learning Goals

My upcoming learning goals include:

- Strengthening C programming fundamentals.
- Solving more logical programming problems.
- Practising advanced pattern programs.
- Exploring two-dimensional arrays.
- Learning basic string operations.
- Understanding functions and pointers.
- Exploring structures and file handling.
- Building small projects using C.

---

## 17. Connect With Me

<p align="center">
  <b>Ayushi Pandey</b>
  <br/>
  <i>Cybersecurity Student | Aspiring Cybersecurity Professional | Programming Learner</i>
  <br/><br/>
  <a href="https://github.com/ayushipandey2007-hub">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github" />
  </a>
</p>

**Learning Focus:** C Programming | Cybersecurity | Problem Solving | Programming Fundamentals

---

<p align="center">
  <b>✨ Learning one concept at a time. Improving one program at a time. ✨</b>
  <br/>
  <i>Consistency is the key to progress!</i>
</p>
