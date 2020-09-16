#<h1> Linked List

## <h2> Summary
Linear data structure not stored in contigous memory locations. Each element are linked together using a pointer. It consists of data and point. First element is called a head.
https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png

##<h2> Cheat sheet
####<h4> Arrays vs Linked list
* Dynamic size ( not fixed size )
* Easy insert and deletion O(1), O(n)
* No random access - have to access elements sequentially
* Extra memory space for pointer
* Not cache friendly - no locality of reference since elements are not in contiguous locations
* considered non primitive data structures stores nodes
* Array elements belong to indices vs linkedlist need to start from the head and traverse list
* Array memory is assigned in compile vs linked list memory is allocated during execution / runtine
* memory utilization is inefficient in arrays vs linked list


Adding Node
First O(1) node.next -> head , head -> node
Middle O(1) insert O(n) find. node.next = prev.next, prev.next = node
Last O(n) find, prev.next = node


Deleting Node
Find previous node, change next of previous, free memory


Circular LinkedList
All nodes are connected to form a circle
* Any nodes can be starting points
* Useful for implementing a queue


Doubling LinkedList
* pointer to both prev and next
