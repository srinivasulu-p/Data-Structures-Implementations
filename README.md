# Data-Structures-Implementations
Own implementation of Data Structures in Java.
Here are the details of methods implemented in each of the data structure implemented

"LinkedList" file contains implementation of LinkedList with following methods:
 - add(E newElement)            --- add element at end to list.
 - add(int index, E newElement) --- Overloading of add method is seen here.
 - get(int index)               --- retieve specific index element from list
 - delete(int index)            --- delete specific index element from list
 - size()                       --- return current size(no.of elements) in the list
 - isEmpty()                    --- return whether Linkedlist is empty or not
 - clear()                      --- clear the LinkedList
 - print()                      --- print elements from head to tail
 - printRec()                   --- Recursively printing elements from head to tail
 - printRevRec()                --- Recursively printing elements from tail to head
 - reverse()                    --- reverse the elements in LinkedList
 - reverseRec()                 --- Recursively reversing the elements in LinkedList
 - reverseUsingStack()          --- Reversing the elements in LinkedList using stack

"DoubleLinkedList" file containd implementation of DoublelinkedList with following methods
 - add(E newElement)            --- add element at end to list
 - add(int index, E newElement) --- overloaded method for add method is seen here.
 - get(int index)               --- retieve specific index element from list
 - delete(int index)            --- delete specific index element from list
 - size()                       --- return current size(no.of elements) in the list
 - isEmpty()                    --- return whether DoubleLinkedlist is empty or not
 - remove()                     --- clear the DoubleLinkedList
 - printForward()               --- print elements from head to tail
 - printReverse()               --- print elements from tail to head
 
"BinarySearchTree" file contains implementation of BinarySearchTree with following methods:
 - find(int data)     --- returns true if given value is present in BST else false.
 - insert(int data)   --- inserts given int value in the BST
 - delete(int data)   --- deletes the given integer data from BST if present.
 - display()          --- prints all the node values in-order(ascending)
 - findMin()          --- returns minimum value node in the BST using iterative technique
 - findMinRec()       --- returns minimum value node in the BST using Recursion technique
 - findMax()          --- returns maximum value node in the BST using iterative technique
 - findHeight()       --- returns maximum height of the BST using Recursion technique.
 
"QueueUsingLinkedList" file contains implementation of Queue using LinkedList with following methods
 - isEmpty				      	    --- returns true if queue is empty else false
 - enQueue(int newData)		--- adds new element to queue
 - deQueue()				         --- deletes first inserted element.
 
"CircularQueue" file contains implementation of circular queue using Array with following methods.
 - isEmpty				      	    --- returns true if queue is empty else false
 - front()					          --- returns front(first inserted) element in the queue
 - enQueue(int newData)		--- adds new element to queue if it doesn't extend the size limit
 - deQueue()		      		   --- removes the firstly inserted value in the CircularQueue
 
"StackUsingLinkedList" file contains implementation of Stack using LinkedList with following methods
- isEmpty					--- returns true if stack is empty else false
- push(int newData)		--- adds new element to stack
- pop()					--- returns and deletes lastly inserted element in the stack.
- peek()					--- returns lastly inserted element but doesn't delete the element
- print() 					--- print the elements in the stack from bottom to top.


    
