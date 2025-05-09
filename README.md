
# Data Structures Python

this Python thingy on data structures, it's a project by CHRIST SAGOMBAYE (AMMI/AIMS). Basically, it's supposed to be a learning tool – a Python package that has all the main data structures coded up (like Arrays, Stacks, Queues, Linked Lists, Binary Trees, Graphs and stuff). The whole point is to give anyone who's into coding a helpful resource for learning.

# Goals
Gotta learn and actually code these basic data structures in Python.
Need to get my head around Object-Oriented Programming (OOP) principles.
Wanna figure out how to package this thing up and put it on PyPI.
Planning to make some docs that people can actually use, probably with a website using MkDocs or Jekyll.
Project Structure


# Data Structures Python


# Data Structures Python

[![PyPI version](https://img.shields.io/pypi/v/data-structures-py.svg)](https://pypi.org/project/data-structures-py/) [![License](https://img.shields.io/pypi/l/data-structures-py.svg)](LICENSE)

A Python educational package implementing fundamental data structures for learning from scratch:
Arrays, Stacks, Queues, Linked Lists, Binary Trees, and Graphs.
---

## Table des matières

- [Installation](#installation)  
- [Exemples d’utilisation](#exemples-dutilisation)  
  - [Pile (Stack)](#pile-stack)  
  - [File (Queue)](#file-queue)  
  - [Liste chaînée (LinkedList)](#liste-chaînée-linkedlist)  
  - [Arbre binaire (BinaryTree)](#arbre-binaire-binarytree)  
  - [Graphe (Graph)](#graphe-graph)  
- [Documentation](#documentation)  
- [Contribuer](#contribuer)  
- [Licence](#licence)  

---

## Installation

Install the latest version from PyPI:

```bash
pip install data-structures-py


git clone https://github.com/CodeWithSagomb/data-structures-python.git
cd data-structures-python
python -m pip install -e .


USE CASE

from data_structures.stack import Stack

s = Stack()
s.push(10)
s.push(20)
print(s.pop())      # 20
print(s.peek())     # 10
print(s.is_empty()) # False


from data_structures.queue import Queue

q = Queue()
q.enqueue('A')
q.enqueue('B')
print(q.dequeue())  # 'A'
print(q.peek())     # 'B'


from data_structures.linked_list import LinkedList

ll = LinkedList()
ll.append(1)
ll.prepend(0)
print(ll)           # 0 -> 1
ll.delete(1)
print(ll.find(1))   # False


from data_structures.tree import BinaryTree

bt = BinaryTree()
for v in [10, 5, 15, 3, 7]:
    bt.insert(v)
print(bt.display()) # [3, 5, 7, 10, 15]




from data_structures.graph import Graph

g = Graph()
g.add_edge('A', 'B')
g.add_edge('A', 'C')
g.display()
# A --> ['B', 'C']
# B --> ['A']
# C --> ['A']


