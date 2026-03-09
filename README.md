<!-- 🔥 Animated Gradient Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ff512f,100:dd2476&height=240&section=header&text=Java%20%2B%20DSA&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>

<h1 align="center">☕ Java Data Structures & Algorithms</h1>

<!-- ✨ Come & Go Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=2500&pause=1000&color=FF6F00&center=true&vCenter=true&width=900&lines=Mastering+Java+Step+by+Step;Data+Structures+%26+Algorithms;Arrays+%7C+Recursion+%7C+OOP;Sorting+%7C+Searching+%7C+Trees+%7C+Graphs;Consistency+%2B+Practice+%3D+Success+🚀">
</p>

---

## 📌 About This Repository

This repository contains my **Java + DSA programs written topic-wise** to build strong problem-solving skills and a solid programming foundation.



It includes:
- Core Java fundamentals  
- Data Structures implementation  
- Sorting & Searching algorithms  
- Tree & Graph concepts  
- Recursion & complexity practice  

<p align="center">
  <img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="400"/>
</p>

---

## ☕ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java" height="70"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-red?style=for-the-badge&logo=java"/>
  <img src="https://img.shields.io/badge/Focus-DSA-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Practice-Daily-blue?style=for-the-badge"/>
</p>

---

# 📂 Topics Covered

## 🔹 Arrays
- 1D & 2D Arrays  
- Traversal  
- Searching  
- Sorting  

---

## 🔎 Searching Algorithms
<p align="center">
  <img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="350"/>
</p>

- Linear Search  
- Binary Search  

---

## 🔄 Sorting Algorithms
- Bubble Sort  
- Selection Sort  
- Insertion Sort  
- Merge Sort  
- Quick Sort  


---

## 🌳 Trees
- Binary Tree  
- BST  
- Tree Traversals  
- Recursion  
<p align="center">
  <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" width="420"/>
</p>
---

## 📊 Graphs

- Graph Representation  
- BFS  
- DFS  

---

## 🧠 Sample Code (Binary Search)

```java
class BinarySearch {
    static int search(int arr[], int target) {
        int left = 0, right = arr.length - 1;

        while(left <= right) {
            int mid = (left + right) / 2;

            if(arr[mid] == target)
                return mid;
            else if(arr[mid] < target)
                left = mid + 1;
            else
                right = mid - 1;
        }
        return -1;
    }

    public static void main(String[] args) {
        int arr[] = {10,20,30,40,50};
        System.out.println(search(arr, 30));
    }
}
