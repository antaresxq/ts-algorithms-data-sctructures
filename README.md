# Common algorithms and data structures

Written in Node + TypeScript, tests in Jest.

## Basic
+ [Binary search](src/base/binary-search.ts) [[test](src/base/__test/binary-search.test.ts)]
+ [Factorial (+ memoized version)](src/base/factorial.ts) [[test](src/base/__test/factorial.test.ts)]
+ [Fibonacci (+ memoized version)](src/base/fibonacci.ts) [[test](src/base/__test/fibonacci.test.ts)]

## Sorts
+ [Bubble sort](src/sorts/bubble-sort.ts) [[test](src/sorts/__test/sorts.test.ts)]
+ [Selection sort](src/sorts/select-sort.ts) [[test](src/sorts/__test/sorts.test.ts)]
+ [Insertion sort](src/sorts/insertion-sort.ts) [[test](src/sorts/__test/sorts.test.ts)]
+ [Merge sort](src/sorts/merge-sort.ts) [[test](src/sorts/__test/sorts.test.ts)]
+ [Quick sort](src/sorts/quick-sort.ts) [[test](src/sorts/__test/sorts.test.ts)]

## Data structures
+ [Linked list](src/data-structures/DoubleLinkedList) [[test](src/data-structures/DoubleLinkedList/__test__/double-linked-list.test.ts)]
+ [Stack](src/data-structures/Stack/Stack.ts) [[test](src/data-structures/Stack/__test__/stack.test.ts)]
+ [Queue](src/data-structures/Queue/Queue.ts) [[test](src/data-structures/Queue/__test__/queue.test.ts)]
+ [Hash table](src/data-structures/HashTable/HashTable.ts) [[test](src/data-structures/HashTable/__test__/hash-table.test.ts)]
+ [Graph](src/data-structures/Graph/Graph.ts) [[test](src/data-structures/Graph/__test__/graph.test.ts)]

## Graph algorithms
### Iteration methods
+ [Breadth first search Iterator](src/data-structures/Graph/iterator/GraphIteratorBFS.ts)
+ [Depth first search Iterator](src/data-structures/Graph/iterator/GraphIteratorDFS.ts)
+ [Dijkstra method Iterator](src/data-structures/Graph/iterator/GraphIteratorDijkstra.ts)
### Searching algorithms
+ [Has path (BFS/DFS)](src/graph-search/has-path.ts) [[test](src/graph-search/has-path.ts)]
+ [Shortest path (BFS/DFS/Dijkstra)](src/graph-search/shortest-path.ts) [[test](src/graph-search/shortest-path.ts)]
