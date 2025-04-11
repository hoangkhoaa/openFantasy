```markdown
# Understanding Data Structures: A Beginner's Guide

This guide aims to provide a basic understanding of common data structures. We'll cover their definitions, common operations, and when to use them.

## What are Data Structures?

Data structures are ways of organizing and storing data in a computer so that it can be used efficiently. They define the relationship between the data elements. Choosing the right data structure can significantly impact the performance of your code.

## Common Data Structures

*   **Arrays:** A contiguous block of memory used to store elements of the same type.
    *   **Operations:** Access (O(1)), Insertion (O(n)), Deletion (O(n))
    *   **Use Cases:** Storing ordered lists, implementing other data structures.

*   **Linked Lists:** A sequence of nodes, where each node contains data and a pointer to the next node.
    *   **Operations:** Insertion (O(1)), Deletion (O(1)), Access (O(n))
    *   **Use Cases:** Implementing stacks, queues, graphs.

*   **Stacks:** A LIFO (Last-In, First-Out) data structure.
    *   **Operations:** Push (O(1)), Pop (O(1)), Peek (O(1))
    *   **Use Cases:** Function call stack, expression evaluation.

*   **Queues:** A FIFO (First-In, First-Out) data structure.
    *   **Operations:** Enqueue (O(1)), Dequeue (O(1)), Peek (O(1))
    *   **Use Cases:** Task scheduling, breadth-first search.

*   **Trees:** A hierarchical data structure consisting of nodes connected by edges.
    *   **Operations:** Varies depending on the type of tree (e.g., binary search tree, AVL tree).
    *   **Use Cases:** Representing hierarchical data, searching, sorting.

*   **Hash Tables:** A data structure that uses a hash function to map keys to values.
    *   **Operations:** Insertion (O(1) average case), Deletion (O(1) average case), Access (O(1) average case)
    *   **Use Cases:** Implementing dictionaries, caching.

## Example: Implementing a Stack in Python

```python
class Stack:
    def __init__(self):
        self.items = []

    def push(self, item):
        self.items.append(item)

    def pop(self):
        if not self.is_empty():
            return self.items.pop()
        else:
            return None

    def peek(self):
        if not self.is_empty():
            return self.items[-1]
        else:
            return None

    def is_empty(self):
        return len(self.items) == 0

# Example Usage
my_stack = Stack()
my_stack.push(1)
my_stack.push(2)
my_stack.push(3)

print(my_stack.pop())  # Output: 3
print(my_stack.peek()) # Output: 2
```

## Conclusion

This guide provides a brief introduction to some common data structures. Understanding these structures is crucial for writing efficient and effective code. Explore these further and practice implementing them to deepen your knowledge.
```

```zh
# 理解数据结构：初学者指南

本指南旨在提供对常见数据结构的基本理解。我们将涵盖它们的定义、常见操作以及何时使用它们。

## 什么是数据结构？

数据结构是在计算机中组织和存储数据的方式，以便可以有效地使用它。它们定义了数据元素之间的关系。选择正确的数据结构可以显着影响代码的性能。

## 常见数据结构

*   **Arrays（数组）：** 用于存储相同类型元素的连续内存块。
    *   **Operations（操作）：** Access（访问）(O(1))，Insertion（插入）(O(n))，Deletion（删除）(O(n))
    *   **Use Cases（用例）：** Storing ordered lists（存储有序列表），implementing other data structures（实现其他数据结构）。

*   **Linked Lists（链表）：** 一系列节点，每个节点包含数据和指向下一个节点的指针。
    *   **Operations（操作）：** Insertion（插入）(O(1))，Deletion（删除）(O(1))，Access（访问）(O(n))
    *   **Use Cases（用例）：** Implementing stacks（实现栈）, queues（队列）, graphs（图）。

*   **Stacks（栈）：** 一种 LIFO（后进先出）数据结构。
    *   **Operations（操作）：** Push（入栈）(O(1))，Pop（出栈）(O(1))，Peek（查看栈顶）(O(1))
    *   **Use Cases（用例）：** Function call stack（函数调用栈）, expression evaluation（表达式求值）。

*   **Queues（队列）：** 一种 FIFO（先进先出）数据结构。
    *   **Operations（操作）：** Enqueue（入队）(O(1))，Dequeue（出队）(O(1))，Peek（查看队首）(O(1))
    *   **Use Cases（用例）：** Task scheduling（任务调度）, breadth-first search（广度优先搜索）。

*   **Trees（树）：** 一种分层数据结构，由边连接的节点组成。
    *   **Operations（操作）：** Varies depending on the type of tree（根据树的类型而异） (e.g., binary search tree（例如，二叉搜索树）, AVL tree（AVL 树）).
    *   **Use Cases（用例）：** Representing hierarchical data（表示分层数据）, searching（搜索）, sorting（排序）。

*   **Hash Tables（哈希表）：** 一种使用哈希函数将键映射到值的数据结构。
    *   **Operations（操作）：** Insertion（插入）(O(1) average case（平均情况）), Deletion（删除）(O(1) average case（平均情况）), Access（访问）(O(1) average case（平均情况）)
    *   **Use Cases（用例）：** Implementing dictionaries（实现字典）, caching（缓存）。

## Example: Implementing a Stack in Python（示例：用 Python 实现栈）

```python
class Stack:
    def __init__(self):
        self.items = []

    def push(self, item):
        self.items.append(item)

    def pop(self):
        if not self.is_empty():
            return self.items.pop()
        else:
            return None

    def peek(self):
        if not self.is_empty():
            return self.items[-1]
        else:
            return None

    def is_empty(self):
        return len(self.items) == 0

# Example Usage（使用示例）
my_stack = Stack()
my_stack.push(1)
my_stack.push(2)
my_stack.push(3)

print(my_stack.pop())  # Output: 3
print(my_stack.peek()) # Output: 2
```

## Conclusion（结论）

This guide provides a brief introduction to some common data structures（本指南简要介绍了​​一些常见的数据结构）. Understanding these structures is crucial for writing efficient and effective code（理解这些结构对于编写高效且有效的代码至关重要）. Explore these further and practice implementing them to deepen your knowledge（进一步探索这些结构并练习实现它们以加深您的知识）。
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._