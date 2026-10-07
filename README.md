# HackerRank-3rdSem-Algorithm-Portfolio
# HackerRank Algorithms & GitHub Coding Portfolio

## Student Information

* **Name:** Elakkya A S
* **SRN:** R25EF080
* **Semester:** 3rd Semester
* **Language Used:** C
* **HackerRank Profile:** https://www.hackerrank.com/profile/elakkyaas22
* **GitHub Repository:** https://github.com/ElakkyaAS/HackerRank-3rdSem-Algorithm-Portfolio

## Introduction

This repository contains my solutions to five HackerRank algorithm problems completed as part of my 3rd Semester coding portfolio. The problems focus on fundamental programming concepts, sorting, searching, arrays, and problem-solving techniques.

The solutions are implemented in **C**, with an emphasis on understanding the algorithm, writing clean code, and analyzing time and space complexity.

## Problems & Approaches

### 1. Mini-Max Sum

**Approach:**
The problem requires finding the minimum and maximum sums obtained by adding exactly four out of five integers. I first calculate the total sum of all five numbers. The minimum sum is obtained by subtracting the largest number from the total, while the maximum sum is obtained by subtracting the smallest number.

**Time Complexity:** `O(n)`
**Space Complexity:** `O(1)`

---

### 2. Birthday Cake Candles

**Approach:**
I find the tallest candle by keeping track of the maximum height. Whenever a candle has the same height as the maximum, I increase the count. If a taller candle is found, I update the maximum and reset the count.

**Time Complexity:** `O(n)`
**Space Complexity:** `O(1)`

---

### 3. Insertion Sort – Part 1

**Approach:**
The last element is stored separately because it is the element that needs to be inserted into the already sorted portion of the array. I compare it with elements from right to left and shift larger elements one position to the right until the correct position is found.

**Time Complexity:** `O(n)`
**Space Complexity:** `O(1)`

---

### 4. Binary Search

**Approach:**
Binary Search works on a sorted array. I repeatedly find the middle element and compare it with the target. If the target is smaller, I search the left half; if it is larger, I search the right half. This continues until the target is found or the search range becomes empty.

**Time Complexity:** `O(log n)`
**Space Complexity:** `O(1)`

---

### 5. Mark and Toys

**Approach:**
I sort the toy prices in ascending order and start purchasing from the cheapest toy. I continue buying while the total cost remains within the given budget. This maximizes the number of toys that can be purchased.

**Time Complexity:** `O(n log n)`
**Space Complexity:** `O(1)`

## Repository Structure


HackerRank-3rdSem-Algorithm-Portfolio/
│
├── README.md
│
├── 01-Mini-Max-Sum/
│   └── solution-1.c
│
├── 02-Birthday-Cake-Candles/
│   └── solution-2.c
│
├── 03-Insertion-Sort-Part-1/
│   └── solution-3.c
│
├── 04-Binary-Search/
│   └── solution-4.c
│
└── 05-Mark-and-Toys/
    └── solution-5.c

Each folder contains the C solution for the corresponding HackerRank problem.
