# Advanced Data Structures: Analysis and Implementation

This repository contains a comprehensive collection of theoretical proofs and implementation architectures for advanced data structures. The focus is on analyzing the complexity, amortized costs, and structural properties of modern algorithmic containers.

## 🎓 Theoretical Analysis (LaTeX)

The `/docs/latex` directory contains detailed mathematical proofs and algorithmic breakdowns for:
- **Quake Heaps**: Analysis of the "Quake" operation and comparison with Fibonacci Heaps.
- **Splay Trees**: Proof of amortized log n time and local-access properties.
- **Skip Lists**: Forward search optimization and probabilistic height analysis.
- **Treaps**: Random priority distribution and expected height.
- **Scapegoat Trees**: Balancing through the $\alpha$-weight-balance property.
- **B-Trees & B+ Trees**: Disk-optimized multi-way search trees.
- **Spatial Data Structures**: Quadtrees (Point vs. PR) and K-D Trees for range searching.

## 🛠️ Implementation Skeletons

The `/src/skeletons` directory contains C++ header and implementation drafts for complex structures like the **Quake Heap**. These files outline the intended architecture:
- **Surrogate Locators**: Encapsulating internal node pointers for safe external manipulation.
- **Templated Priority Queues**: Supporting generic key-value pairs for flexible data ingestion.

## 📂 Project Structure
- **/docs/latex**: Original TeX source files for statistical and algorithmic analysis.
- **/reports**: Rendered PDF reports summarizing findings and proofs.
- **/src/skeletons**: C++ structural designs for advanced containers.

---
*Developed as part of Advanced Data Structures coursework at FGV.*
