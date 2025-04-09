
# Module `BinaryTree`

## Classes `Node` et `BinaryTree`

```python
class Node:
    def __init__(self, value): ...
    self.left = None
    self.right = None

class BinaryTree:
    def __init__(self): ...
    def insert(self, value): ...
    def inorder_traversal(self, node) -> List[Any]: ...
    def display(self) -> List[Any]: ...
```    