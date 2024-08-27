USAGES.md
markdown
Copy code
# dsalib Usage Documentation

## LinkedList

`LinkedList` provides methods to manipulate a linked list.

- **`append(value)`**: Adds an element to the end of the list.
  ll = LinkedList()

  ll.append(1)

**`display()`**: Returns a list of all elements in the linked list.

print(ll.display())

## Stack
`Stack` implements a Last-In-First-Out (LIFO) stack.

**`push(value)`**: Adds an element to the top of the stack.

stack = Stack()

stack.push(1)

**`pop()`**: Removes and returns the top element of the stack.

print(stack.pop())

## Queue

`Queue` implements a First-In-First-Out (FIFO) queue.

**`enqueue(value)`**: Adds an element to the rear of the queue.

queue = Queue()

queue.enqueue(1)

**`dequeue()`**: Removes and returns the front element of the queue.

print(queue.dequeue())

## Array

`Array` provides methods for handling an array of elements.

**`__init__(*values)`**: Initializes the array with given values.

arr = Array(5, 3, 8, 1)

**`bubble_sort()`**: Sorts the array using the bubble sort algorithm.

print(arr.bubble_sort())

## BinaryTree
`BinaryTree` provides methods for binary tree operations.

**`insert(value)`**: Inserts a value into the binary tree.

bt = BinaryTree()

bt.insert(5)

**`in_order_traversal(node)`**: Performs in-order traversal of the tree.


print(bt.in_order_traversal(bt.root))


## DirectedGraph

`DirectedGraph` implements a directed graph.

**`add_edge(start, end)`**: Adds a directed edge from start to end.

graph = DirectedGraph()

graph.add_edge(1, 2)

**`display()`**: Returns a representation of the graph.

print(graph.display())

## MinHeap

MinHeap implements a min-heap data structure.

**`insert(value)`**: Inserts a value into the heap.

heap = MinHeap()
heap.insert(3)

**`extract_min()`**: Removes and returns the smallest element from the heap.

print(heap.extract_min())

## Trie

`Trie` provides methods for managing a prefix tree (trie).

**`insert(word)`**: Inserts a word into the trie.

trie = Trie()

trie.insert("hello")

**`search(word)`**: Searches for a word in the trie.

print(trie.search("hello"))


## HashTable
`HashTable` implements a hash table with basic operations.

**`insert(key, value)`**: Inserts a key-value pair into the hash table.

hash_table = HashTable()

hash_table.insert("key", "value")

**`search(key)`** : Searches for a value associated with a key.

print(hash_table.search("key"))

**`delete(key)`**: Deletes a key-value pair from the hash table.


hash_table.delete("key")


## DisjointSet

`DisjointSet` provides methods for union-find operations.

**`__init__(size)`**: Initializes a disjoint set with a given size.

ds = DisjointSet(5)

**`union(x, y)`**: Unites the sets containing x and y.

ds.union(0, 1)

**`find(x)`**: Finds the representative of the set containing x.

print(ds.find(1))







