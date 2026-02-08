# Data Structures (2025–2026)

### Table of Contents
1. [Array](#1-array)
2. [String](#2-string)
3. [Hash Map](#3-hash-map)
4. [Set](#4-set)
5. [Stack](#5-stack)
6. [Queue](#6-queue)
7. [Linked List](#7-linked-list)
8. [Tree](#8-tree)
9. [Heap](#9-heap)
10. [Graph](#10-graph)

## 1. **Array**
Stores multiple values in one variable in an ordered way.
```jsx
const numbers = [10, 20, 30];
console.log(numbers[1]); // 20
```
<br>

## 2. **String**
A sequence of characters or text.
```jsx
const name = "Vishal";
console.log(name.length); // 6
```
<br>

## 3. **Hash Map**
Stores data as key value pairs for fast access.
```jsx
const user = {
  name: "Vishal",
  age: 25
};

console.log(user.name); // Vishal
```
<br>

## 4. **Set**
Stores only unique values.
```jsx
const nums = new Set([1, 2, 2, 3]);
console.log(nums); // {1, 2, 3}
```
<br>

## 5. **Stack**
Works on last in first out principle.
```jsx
const stack = [];
stack.push(1);
stack.push(2);
stack.pop(); // removes 2
```
<br>

## 6. **Queue**
Works on first in first out principle.
```jsx
const queue = [];
queue.push(1);
queue.push(2);
queue.shift(); // removes 1
```
<br>

## 7. **Linked List**
A collection of nodes where each node points to the next.
```jsx
const list = {
  value: 1,
  next: {
    value: 2,
    next: null
  }
};
```
<br>

## 8. **Tree**
Data structure where each node can have children.
```jsx
const tree = {
  value: "A",
  children: [
    { value: "B", children: [] },
    { value: "C", children: [] }
  ]
};
```
<br>

## 9. **Heap**
Special tree where highest or lowest value is always on top.
```jsx
const heap = [1, 3, 5]; // min heap representation
```
<br>

## 10. **Graph**
Collection of nodes connected by edges.
```jsx
const graph = {
  A: ["B", "C"],
  B: ["A", "D"],
  C: ["A"]
};
```
<br>
