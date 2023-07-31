# Algorithms and Data Structures

An algorithm is a sequence of instructions written by a computer programmer in order to guide a computer to solve a problem. As an analogy, consider recipes in the real world cuisine. A recipe is a list of instruction that a chef follows in order to cook a meal.

In order to write a good computer program, the algorithms employed (or created) must be correct, which means the steps must lead to the right solution without errors.

## How to write algorithms

Technically, algorithms are written in programming languages. However, for the sake of simplifying a solution without needing to worry about the nuances or complexity of code, algorithms may be represented as pseudocodes or flowcharts.

### Pseudocode

A pseudocode (or fake-code) is a close-to-english representation of an instruction. It allows you to write algorithms by listing the steps as plain english sentences without worry for syntax/code technicalities. A pseudocode may also be structured in a way to resemble actual code, but compared to actual code, a pseudocode is easier to read and understand. This is an example of a [structured] pseudocode, the algo syntax or format:

```
ALGORITHM addTwoNumbers

VAR
  firstNumber: INTEGER
  secondNumber: INTEGER

BEGIN
  Read(firstNumber)
  Read(SecondNumber)
  sum := firstNumber + secondNumber
  Write(sum)
END
```

> We specify the name of the algorithm (the first line), declaration of variables with respective datatypes indented under `VAR`, and the actual list of steps indented between `BEGIN` and `END`.

### Flowcharts

Flowcharts are diagrams (geometric shapes with arrows) used to explain the flow of a program or an algorithm. Programmers use flowcharts to present their algorithms in a more friendly way.

## Checkpoint solutions

> To make use of the solutions in this repository, please create a fork.

### Introduction to algorithms checkpoint

At this checkpoint, you are asked to write an algorithm that reads a sentence, which ends with a point, character by character, and to determine:

- The length of the sentence (the number of characters).
- The number of words in the sentence (assuming that the words are separated by a single space).
- The number of vowels in the sentence.

You have to keep in mind that:

- Each character will be treated separately.
- The last character is the point.
- Use three variables as counters.

### Data structures and procedural programming checkpoint

At this checkpoint you are asked to write an algorithm that fulfills the following description:

Problem 1

- Given two sets of elements, find the sum of all distinct elements from the set. In other words, find the sum of all elements which are present in either of the given set.
- Example:
  Set 1 : [3, 1, 7, 9], Set 2: [2, 4, 1, 9, 3]
- Output: 13 (distinct elements 4, 7, 2 )
- Give a solutions to this problem, using arrays

Problem 2
You are asked to write an algorithm that fulfill the following:

- Name: Dot product
- Description:
  1. Write a procedure, called dot_product which calculates in the variable ps, the dot(scalar) product of v1 and v2 (v1 and v2 are vectors of IR)
  2. Write an algorithm which determines, for n pairs of given vectors, whether two vectors of given IR are orthogonal, by calling the procedure defined in the previous question. The dot product of two orthogonal vectors is zero.
  3. Modify the previous algorithm if you use a dot_product function instead of a procedure.
