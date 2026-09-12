# Java If-Else

A Java program that determines whether a given integer is **Weird** or **Not Weird** based on a set of conditional rules.

This problem is part of my **HackerRank Java practice** and focuses on understanding conditional statements and logical decision-making in Java.

---

## 📌 About the Problem

The program reads a positive integer `N` and determines whether it should be classified as **Weird** or **Not Weird**.

The classification depends on whether the number is odd or even and, for even numbers, which range it belongs to.

---

## 📝 Problem Rules

The number `N` is classified as follows:

| Condition | Output |
|---|---|
| `N` is odd | `Weird` |
| `N` is even and between `2` and `5` | `Not Weird` |
| `N` is even and between `6` and `20` | `Weird` |
| `N` is even and greater than `20` | `Not Weird` |

These conditions allow the program to make a decision based on the value of `N`.

---

## ⚙️ How It Works

### 1. Read the Integer

The program reads the input using:

```java
Scanner scanner = new Scanner(System.in);
int N = scanner.nextInt();
