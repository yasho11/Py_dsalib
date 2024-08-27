Here is a basic example demonstrating how to use various components of the dsalib library:

Arrays


from dsalib.arrays import Array

arr = Array(5, 3, 8, 1)
print(arr)
print(arr.bubble_sort())


Linked Lists

from dsalib.linked_lists import LinkedList

ll = LinkedList()
ll.append(1)
ll.append(2)
print(ll.display())


Stacks


from dsalib.stacks import Stack

stack = Stack()
stack.push(1)
print(stack.pop())

Queues
from dsalib.queues import Queue

queue = Queue()
queue.enqueue(1)
print(queue.dequeue())


Trees
from dsalib.trees import BinaryTree

bt = BinaryTree()
bt.insert(5)
print(bt.in_order_traversal(bt.root))


Graphs
from dsalib.graphs import DirectedGraph

graph = DirectedGraph()
graph.add_edge(1, 2)
print(graph.display())


Heaps
from dsalib.heaps import MinHeap

heap = MinHeap()
heap.insert(3)
print(heap.extract_min())


Tries
from dsalib.tries import Trie

trie = Trie()
trie.insert("hello")
print(trie.search("hello"))
print(trie.search("world"))


Hash Tables

from dsalib.hash_tables import HashTable

hash_table = HashTable()
hash_table.insert("key", "value")
print(hash_table.search("key"))
hash_table.delete("key")
print(hash_table.search("key"))


Disjoint Sets

from dsalib.disjoint_sets import DisjointSet

ds = DisjointSet(5)
ds.union(0, 1)
print(ds.find(1))


Contributing


Contributions to the dsalib library are welcome! If you have suggestions or improvements, please follow these steps:

Fork the repository.
Create a new branch for your feature or fix.
Make your changes and commit them.
Push your branch to your fork.
Open a pull request.
