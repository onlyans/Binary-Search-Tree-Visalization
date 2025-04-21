## Project Documentation: Virtualization of Binary Search Tree

**Askaruly Orken, Saukynbay Ansar, Muratov Aldiyar, and Daniyal Temirlan**

## PROJECT LINK:
**https://github.com/onlyans/Binary-Search-Tree-Visalization** 



## What is a BST?
A Binary Search Tree (BST) data structure contains a maximum of two children for each node. Every element in the right subtree is greater than the node's value, and every element in the left subtree is less than the node's value.
In a balanced BST, this invariant enables us to perform efficient operations like search, insertion, and deletion with an average time complexity of O(log n).
How did we implemented our BST
Using HTML, CSS, and JavaScript, the project uses the element to enable real-time drawing and animations.

**1. TreeNode Class:**

- For drawing, every node contains coordinates (x, y), a value (element), and left and right child pointers.
- A second 'width' attribute is calculated recursively to control horizontal spacing and tree layout.

**2. BST Class:**

- On top of basic function implementation like insert, search, and delete, the BST class holds onto the root.
- A path for visually displaying node addition is returned by insertion.
- Finding an in-order predecessor and establishing proper tree connections is part of removal.

**3. Animation Functions**

- Animations are used to show search paths and traversals.
- Async/await is used to achieve these using color switches and waits.
- Highlight effects are used to graphically depict step-by-step in-order, pre-order, and post-order traversals.

**4. Coordinate Calculation:**

- Widths of every subtree are computed to display nodes at proper positions.
- To provide enough space and prevent overlap, X and Y coordinates are assigned recursively using subtree widths and levels.

**5. Drawing**

- Canvas routines are used to draw nodes and edges: arcs for nodes and lines for edges.
- Color maps are passed to the drawing procedures for dynamic highlighting.

**6. Scaling:**

- The canvas dynamically changes its zoom factor (scale) based on the depth of the tree so that it fits in the screen.
  
 Project Features:
- Field to enter numerical values.
- Insert, delete, and search buttons for values.
- Buttons to trigger in-order, pre-order, and post-order traversals.
- Real-time canvas drawings and animated visualizations.
- Interactive notifications for missing nodes or duplicate insertion.
- Neon green and matrix-style appearance with dark feel.
- Adaptive scaling depending on screen size and tree depth. 

## Educational Value
For developers and students, this image is a great teaching tool for learning the dynamics and structure of binary search trees.
Animations give abstract ideas a concrete form and allow understanding.
