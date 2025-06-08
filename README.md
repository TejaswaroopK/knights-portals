# 🛡️ Knights and Portals - Shortest Path Finder

A visual and interactive tool to find the shortest path in a grid-based world where walls, empty cells, and a single-use teleport mechanic exist. The goal is to reach the bottom-right corner from the top-left with the least steps, optionally teleporting between two empty cells exactly once.

---

## 🚀 Overview

This project provides a browser-based interface to solve a grid pathfinding problem using Breadth-First Search (BFS) with a twist — one allowed teleport between any two open cells (`1`). The user enters a grid using space-separated `1`s (empty) and `0`s (walls), and the tool calculates the minimum number of steps required.

---

## 🧠 Problem Statement

Given:
- A `n x m` matrix where:
  - `1` = empty cell (you can walk or teleport here)
  - `0` = wall (cannot pass)
- Start at the **top-left** cell `(0,0)`
- End at the **bottom-right** cell `(n-1,m-1)`
- **One teleport** is allowed between any two distinct empty cells
- Return the shortest number of steps to reach the end using normal moves (up/down/left/right) and at most one teleport

---

## ✨ Features

- 📋 Clean input interface with example preloaded
- 🔍 Real-time validation for incorrect/malformed grid input
- 📦 Teleportation logic built using 0-1 BFS for correctness
- 🧾 Results appear with detailed output (success or failure)
- 📱 Fully responsive and browser-based (no server/backend needed)

---

## 💻 Technologies Used

- **HTML5** – Structure
- **CSS3** – Styling and layout
- **JavaScript (Vanilla)** – BFS algorithm and logic

---
