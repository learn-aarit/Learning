  
# 📊 Data Structures & Algorithms (DSA) – Array Patterns

Welcome to my **DSA learning journey** 🚀  
This repository contains **clear, structured notes and problem-solving patterns** focused on **Arrays**, one of the most fundamental data structures in computer science.

The goal of this repository is not to memorize solutions, but to **understand patterns**, build **strong logic**, and become confident in solving DSA problems from scratch.

---

## 🧠 What is an Array?

An **array** is:

- A way to store **multiple values of the same data type** in a single variable
- A **linear (sequential) data structure**
- **Fixed in size**
- Stores elements in **contiguous memory locations**
- An **ordered collection of elements**

### 🔢 Indexing Rule
- Index starts from **0**
- Ends at **n − 1**, where `n` is the size of the array


---

## 🎯 Why Learn Array Patterns?

Most DSA problems follow **repeatable patterns**.

If you master these patterns:
- ❌ You won’t blindly memorize solutions  
- ✅ You’ll recognize problems faster  
- ✅ You’ll write efficient and clean code  
- ✅ You’ll improve your thinking approach  

---

# 🧩 Array Problem Patterns in DSA

Below are the **most important array patterns** every beginner should learn.

---

## 1️⃣ Sliding Window

### 🔍 Definition
A technique where a **window of fixed or variable size** slides across the array to process subarrays efficiently.

### 💡 Key Idea
Reuse previous computations instead of recalculating values for every window.

### 🧠 When to Use
- Continuous subarray or substring problems
- Fixed or variable window size

### 📌 Examples
- Maximum sum subarray of size `k`
- Longest substring without repeating characters
- Minimum window substring

---

## 2️⃣ Two Pointers

### 🔍 Definition
Use **two indices** moving through the array to find pairs or ranges that satisfy a condition.

### 💡 Key Idea
Often applied on **sorted arrays** where one pointer starts from the beginning and the other from the end.

### 🧠 When to Use
- Pair problems
- In-place array modification
- Range-based conditions

### 📌 Examples
- Two Sum (sorted array)
- Trapping Rain Water
- Remove duplicates from sorted array

---

## 3️⃣ Fast & Slow Pointers (Tortoise & Hare)

### 🔍 Definition
Two pointers move at **different speeds** through the data structure.

### 💡 Key Idea
If a cycle exists, the fast pointer will eventually meet the slow pointer.

### 🧠 When to Use
- Cycle detection
- Finding middle elements

### 📌 Examples
- Detect cycle in linked list
- Find middle of linked list
- Happy number problem

---

## 4️⃣ Prefix Sum / Difference Array

### 🔍 Definition
Precompute **cumulative results** to efficiently answer range queries.

### 💡 Key Idea
Subarray sums can be calculated in **O(1)** time after preprocessing.

### 🧠 When to Use
- Range sum queries
- Subarray sum problems

### 📌 Examples
- Subarray sum equals `k`
- Range sum queries
- Difference array for range updates

---

## 5️⃣ Kadane’s Algorithm

### 🔍 Definition
A **dynamic programming** approach to find the maximum subarray sum.

### 💡 Key Idea
At each step, decide whether to:
- Extend the current subarray  
- Start a new subarray  

### 📌 Examples
- Maximum subarray sum
- Maximum circular subarray sum

---

## 6️⃣ Binary Search on Answer

### 🔍 Definition
Binary search applied on the **range of possible answers**, not directly on the array.

### 💡 Key Idea
Guess an answer, check if it’s feasible, then adjust the search range.

### 🧠 When to Use
- Optimization problems
- Minimum / maximum value constraints

### 📌 Examples
- Allocate minimum pages
- Aggressive cows
- Minimum capacity to ship packages

---

## 7️⃣ Sorting + Greedy

### 🔍 Definition
Sort the array and apply **greedy decisions** to get optimal results.

### 💡 Key Idea
Sorting simplifies constraints and greedy choices lead to optimal solutions.

### 📌 Examples
- Minimum platforms problem
- Meeting room scheduling
- Activity selection

---

## 8️⃣ Merge Intervals

### 🔍 Definition
Merge overlapping intervals into consolidated ranges.

### 💡 Key Idea
Sorting intervals ensures overlapping intervals are adjacent.

### 📌 Examples
- Merge intervals
- Insert interval
- Employee free time

---

## 9️⃣ Hashing / Frequency Count

### 🔍 Definition
Use hash maps to store **counts, frequencies, or positions** of elements.

### 💡 Key Idea
Provides **O(1)** average-time lookup.

### 🧠 When to Use
- Counting occurrences
- Duplicate detection
- Subarray problems

### 📌 Examples
- Majority element
- Subarray with given sum
- Longest consecutive sequence

---

## 🛠️ Learning Strategy

- Understand the **pattern first**
- Visualize the logic
- Dry-run examples
- Write code only after clarity
- Revise patterns regularly

---

## 🎯 Final Thought

> “DSA is not about solving more problems.  
> It’s about solving problems **the right way**.”

This README will evolve as I grow from **beginner → intermediate → advanced** in DSA.

Happy Coding 💻🔥  
**— Aarit**
