# 0x09. Island Perimeter

## 📍 Project Description

This project is part of the **ALX Software Engineering** program. The goal is to calculate the **perimeter of an island** described in a 2D grid (list of lists) where:
- `1` represents land
- `0` represents water

The island is surrounded by water and doesn't have any "lakes" (water inside the island not connected to the water around the island).

---

## 🧠 Learning Objectives

By completing this project, you will understand:
- How to represent and manipulate 2D grid structures in Python
- How to analyze the borders and neighbors of elements in a matrix
- How to efficiently calculate the perimeter of shapes in grids

---

## 📄 Files

| Filename | Description |
|----------|-------------|
| `0-island_perimeter.py` | Contains the function `island_perimeter(grid)` that returns the perimeter of the island described in `grid`. |
| `0-main.py` | Test file to run and validate the implementation. |

---

## 🔧 Function Prototype

```python
def island_perimeter(grid: list[list[int]]) -> int:

