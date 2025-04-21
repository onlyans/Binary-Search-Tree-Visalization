
## Project Documentation: Binary Search Tree Visualization

**Askaruly Orken, Daniyal Temirlan, Muratov Aldiyar, Saukynbay Ansar** 

## What is a BST?

A **Binary Search Tree (BST)** is a type of binary tree where:
- All elements in the **left subtree** of a node are **less than** the node’s value.
- All elements in the **right subtree** are **greater than** the node’s value.

This structure allows for efficient operations like **search**, **insertion**, and **deletion** with an average time complexity of `O(log n)`.

## How We Implemented the BST

This project is implemented using **HTML**, **CSS**, and **JavaScript**, featuring live visualization on an HTML `<canvas>`. The core components include:

- **TreeNode Class**: Represents each node with properties `element`, `left`, `right`, `x`, `y`, and `width`.
- **BST Class**: Manages the core functionality including:
  - `insert` – to add new values
  - `pathTo` – to trace a search path
  - `removeWithAnimation` – to delete nodes with visual feedback
  - `getReplacementPath` – to handle complex deletions

- **Rendering Functions**:
  - `drawTree`, `drawNode`, `drawLine` – handle visual drawing of nodes and connections.
  - `assignCoordinates`, `updateCoordinates`, `computeWidths` – calculate node positions for balanced layout.

- **Animations**:
  - Search and tree traversals (`inorder`, `preorder`, `postorder`) are animated with color transitions.
  - Insertions and deletions include smooth motion and highlighting.

## Project Features

- **Interactive UI**:
  - Input field for entering numbers.
  - Buttons to `Insert`, `Delete`, and `Search`, plus controls for different tree traversals.

- **Live Visualization**:
  - Color-coded highlights show active operations.
  - Nodes and branches are drawn dynamically on the canvas.

- **Responsive Design**:
  - The canvas automatically adjusts scale based on tree depth and screen size.

- **Thematic Aesthetic**:
  - Dark “Matrix-style” visuals with neon green highlights.
  - Binary-code background image enhances the techy atmosphere.
