# Percolation

This project is a Go implementation designed to visualize the porosity of a material and how fluid connections form within it. It uses a **Union-Find data structure** (also known as Disjoint Set Union) to efficiently solve connectivity problems in undirected graphs. The project highlights the flow of liquid through the material and demonstrates the formation of connected components within a grid.

---
<img width="297" alt="Captura de pantalla 2024-11-26 a la(s) 10 29 28 p  m" src="https://github.com/user-attachments/assets/9b5a8eda-066b-4a65-a284-7846f19b2ba9">

## **Union-Find Structure**

The **Union-Find** data structure is derived from binary trees and is widely used for efficiently solving connectivity problems. Its key operations include:

- **Union**: Merging two connected components in \( O(1) \) time.
- **Find**: Checking if two nodes are connected in \( O(1) \) time.

---

## **Visualization and Integration**

The project uses **CGO** to integrate **C** libraries with Go, enabling advanced graphical functions. A C-based library is utilized to render the grid visualization, while the Go code handles the algorithmic logic and integrates the visualization layer. 

### Key Features:

- A **grid-based visualization** that displays the material's porosity.

- **Real-time rendering** of fluid connections and component unions.
- Demonstrations of how different Union-Find optimizations impact the structure.


## **Technologies Used**

- **Programming Language**: Go
- **Graphics Library**: Raylib (integrated through CGO with a C implementation)




