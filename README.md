# Binary Search Tree (BST)

A C++ program that implements a Binary Search Tree (BST) with various operations like insertion, deletion, searching, and traversals.

---

## Features

- **Insertion**: Add elements to the BST while maintaining its properties.
- **Deletion**: Remove elements while ensuring the tree remains a valid BST.
- **Search**: Efficiently find elements in the tree.
- **Traversals**:
  - In-order: Retrieves elements in sorted order.
  - Pre-order: Retrieves elements in root-left-right order.
  - Post-order: Retrieves elements in left-right-root order.
  - Level-order: Traverses the tree level by level.

---

## Code Structure

### Classes and Functions
- **`TreeNode` Class**:
  - Represents a node in the tree with pointers to its left and right children and stores its value.

- **Core Functions**:
  - `insert(int value)`: Inserts a value into the BST.
  - `deleteNode(int value)`: Deletes a node with the specified value.
  - `search(int value)`: Searches for a value in the BST and returns its location.
  - `inOrderTraversal()`: Prints the BST elements in sorted order.
  - `preOrderTraversal()`: Prints the BST elements in pre-order.
  - `postOrderTraversal()`: Prints the BST elements in post-order.
  - `levelOrderTraversal()`: Prints the BST elements level by level.

---

## How It Works

1. **Insertion**:
   - Adds a node to the tree.
   - Ensures the left subtree contains only nodes with values less than the root.
   - Ensures the right subtree contains only nodes with values greater than the root.

2. **Search**:
   - Traverses the tree from the root to find a specific value.
   - Returns `true` if found, otherwise `false`.

3. **Deletion**:
   - Handles three cases:
     1. Node with no children (leaf).
     2. Node with one child.
     3. Node with two children (replaces the node with its in-order successor).

4. **Traversals**:
   - Different methods to visit and print nodes for various use cases.

---

## How to Run

1. **Clone or Download the Repository**
   ```bash
   git clone <repository-url>
