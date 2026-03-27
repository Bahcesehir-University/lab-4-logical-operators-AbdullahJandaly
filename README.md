# Lab: Relational & Logical Operators — Conditional Statements

## Course Information

| Field       | Detail                                              |
|-------------|-----------------------------------------------------|
| Course      | CMP1001 – Introduction to Programming (C++)         |
| Lab Topic   | Relational operators, logical operators, conditional statements |
| Duration    | 60 minutes                                          |
| File        | `MainProgram.cpp` (single-file lab)                 |

## Objective

By the end of this lab you will be able to:

- Use all six relational operators (`==`, `!=`, `<`, `>`, `<=`, `>=`) to compare values.
- Combine conditions with logical operators (`&&`, `||`, `!`).
- Write `if`, `else if`, and `else` blocks to control program flow.
- Use nested conditional statements to solve multi-layered problems.
- Validate user input before processing it.

## Prerequisites

Before starting this lab you should be comfortable with:

- Declaring variables (`int`, `double`, `char`, `string`).
- Reading input with `cin` and printing output with `cout`.
- Basic arithmetic expressions.
- Compiling and running a C++ program from the terminal.

## What You Will Learn

1. How relational operators evaluate to `true` or `false`.
2. How `&&` (AND), `||` (OR), and `!` (NOT) let you build compound conditions.
3. The structure and flow of `if / else if / else` chains.
4. When and how to nest one conditional inside another.
5. A practical pattern for input validation before computation.

## Lab Structure

The lab file is divided into four progressive sections:

| Section | Title               | Time     | Description |
|---------|----------------------|----------|-------------|
| 1       | Warm-Up              | 5–10 min | Review `cin`/`cout`, variables, arithmetic. |
| 2       | Core Concepts        | 10–15 min| Mini-reference + small exercises on `if/else` and operators. |
| 3       | Guided Exercises     | 25–30 min| Five exercises of increasing difficulty covering even/odd, grading, leap years, triangle classification, and ticket pricing. |
| 4       | Challenge            | 10 min   | Two open-ended problems: a mini login system and a BMI advisor. |

Each exercise is marked with `// TODO:` comments. Write your code where indicated.

## How to Compile & Run

Open a terminal in the folder containing `MainProgram.cpp` and run:

```bash
g++ MainProgram.cpp -o lab
./lab
```

Compile **often** — after finishing each exercise — so you catch errors early.

> **Tip:** On Windows with MinGW use `.\lab.exe` instead of `./lab`.

## Submission Instructions

1. Make sure your program **compiles without errors**.
2. Test every section with reasonable inputs.
3. Rename or keep the file as `MainProgram.cpp`.
4. Push your work to the GitHub Classroom repository **before the deadline**.
5. Verify your submission by checking the repository on GitHub.

**Do not** add extra files. Everything must stay in `MainProgram.cpp`.

## Grading Criteria

| Criterion       | Weight | Details |
|-----------------|--------|---------|
| Correctness     | 50%    | Exercises produce the expected output for valid and edge-case inputs. |
| Code Quality    | 20%    | Readable formatting, meaningful variable names, consistent style. |
| Completion      | 20%    | All TODO sections attempted (Sections 1–3 required). |
| Challenge       | 10%    | Section 4 problems attempted and substantially correct. |

**Total: 100%**

## Estimated Time Breakdown

| Activity                        | Minutes |
|---------------------------------|---------|
| Read instructions & warm-up     | 5–10    |
| Core concepts exercises         | 10–15   |
| Guided exercises (3.1 – 3.5)   | 25–30   |
| Challenge problems              | 10      |
| **Total**                       | **~60** |

## Tips for Students

- **Compile after every exercise.** Small, frequent builds are much easier to debug than one big compilation at the end.
- **Test edge cases.** For example, what happens when the score is exactly 0, 60, 90, or 100?
- **Read the comments carefully.** The hints are there to save you time.
- **Use parentheses generously.** When combining `&&` and `||`, parentheses make your intent clear and prevent bugs.
- **Start simple.** Get the basic `if/else` working first, then add extra conditions.
- **Don't be afraid to experiment.** Changing a `<` to `<=` and re-running teaches you more than reading about it.

Good luck and happy coding!
