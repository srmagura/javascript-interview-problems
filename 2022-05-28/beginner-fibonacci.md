# 2022-05-28 Beginner Problem: The Fibonacci Sequence

**React:** Prohibited

The Fibonacci sequence is an intriguing integer sequence in which the next term is calculated by adding the previous two terms. The terms of the sequence are called Fibonacci numbers. These numbers appear in surprising places in nature, like in the number of petals on a flower!

This is a classic programming problem that I have been asked in an interview.

## Problem Description

The Fibonacci sequence can be formally defined as

```text
F_0 = 0
F_1 = 1
F_i = F_{i-1} + F_{i-2}    for i >= 2
```

### Part 1

Write a function called `iterativeFibonacci` which takes in a positive integer `n >= 2` and returns the `n`-th Fibonacci number `F_n`. Your function must use iteration (i.e. a loop).

Use `iterativeFibonacci` to print `F_20` to the console. You should get 6,765.

### Part 2

Write a function called `recursiveFibonacci` which takes in a positive integer `n` and returns the `n`-th Fibonacci number `F_n`. Your function must use recursion.

Use `recursiveFibonacci` to print `F_10` to the console. You should get 55.

### Part 3

Use DOM APIs to display `F_0` through `F_20` in a bulleted list, like this:

- F_0 = 0
- F_1 = 1
- F_2 = 1
- (and so on)

If the Fibonacci number is divisble by 3, make the text green and bold. All other list items will use the default text color.

## Reference Solution

**Do not view the solution before the end of the meetup!**

https://codesandbox.io/s/beginner-fibonacci-dnbdlz?file=/src/index.ts
