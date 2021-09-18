# interview-modules
📦 A collection of useful javascript data structures and classes I wrote that are not inlcuded in the standard library.

# Heap
- Takes an optional custom comparator (like sort())
    - Min-heap: (a, b) => b-a
   -  Max-heap: (a, b) => a-b
- Internally implemented using an array
  - root @ index = 0
  - left child @ (index*2)+1
  - right child @  (index*2)+2
