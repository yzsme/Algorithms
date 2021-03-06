cmake_minimum_required(VERSION 3.7)
project(BinarySearchTree)
project(RedBlackTree)
project(HashSet)
project(LinkedList)
project(MaximumSubarray)
project(FibonacciSequenceDynamicProgramming)
project(KMP)
project(Heap)

set(CMAKE_CXX_STANDARD 11)

add_executable(BinarySearchTree BinarySearchTreeTest.cpp DataStructure/BinarySearchTree.cpp)
add_executable(RedBlackTree RedBlackTreeTest.cpp DataStructure/RedBlackTree.cpp)
add_executable(HashSet HashSetTest.cpp DataStructure/HashSet.cpp)
add_executable(LinkedList LinkedListTest.cpp DataStructure/LinkedList.cpp)
add_executable(MaximunSubarray MaximumSubarrayTest.cpp Algorithms/MaximumSubarray.cpp)
add_executable(FibonacciSequenceDynamicProgrammingTest FibonacciSequenceDynamicProgrammingTest.cpp Algorithms/FibonacciSequenceDynamicProgramming.cpp)
add_executable(KMP KMPTest.cpp Algorithms/KMP.cpp)
add_executable(Heap HeapTest.cpp DataStructure/Heap.cpp)
