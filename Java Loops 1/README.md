# Java Loops 1

A beginner-level Java program that uses a `for` loop to generate and print the first 10 multiples of a given integer.

## 📌 About

This program takes an integer `N` as input and prints its first 10 multiples.

Each multiple is displayed in the following format:

```text
N x i = result
```

For example, if the input is `2`, the program prints:

```text
2 x 1 = 2
2 x 2 = 4
...
2 x 10 = 20
```

This problem is based on the **Loops** section of HackerRank and helps practice using `for` loops and basic arithmetic in Java.

## ⚙️ How It Works

The program follows these steps:

1. Create a `Scanner` object to read input.
2. Read an integer `N` from the user.
3. Use a `for` loop starting from `1` and ending at `10`.
4. Multiply `N` by the current loop value.
5. Print the result in the required format.

### Loop Logic

```java
for (int i = 1; i <= 10; i++) {
    System.out.println(N + " x " + i + " = " + (N * i));
}
```

The loop runs **10 times**, once for each multiple from `1` to `10`.

## 💻 Complete Code

```java
import java.util.*;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt();

        for (int b = 1; b <= 10; b++) {
            System.out.println(a + " x " + b + " = " + (a * b));
        }
    }
}
```

## 🧪 Example

### Input

```text
2
```

### Output

```text
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
```

## 🧠 Concepts Practiced

* Java `Scanner`
* Taking integer input
* `for` loops
* Loop counters
* Multiplication
* Arithmetic expressions
* String concatenation
* `System.out.println()`
* Formatted output

## ▶️ How to Run

Save the program as:

```text
Java Loops 1.java
```

Compile:

```bash
javac "Java Loops 1.java"
```

Run:

```bash
java Solution
```

> If you are submitting directly to HackerRank, keep the class name as `Solution`, as required by the platform.

## 📂 Project Structure

```text
Java-Loops-1/
│
├── Java Loops 1.java
└── README.md
```

## 🎯 Learning Goal

The goal of this exercise is to understand how `for` loops can be used to repeat an operation a fixed number of times.

It provides practice with a simple but important programming pattern:

```text
Initialize → Check Condition → Execute → Update
```

In this program, the loop starts at `1`, continues while the value is less than or equal to `10`, and increases the counter by `1` after every iteration.
