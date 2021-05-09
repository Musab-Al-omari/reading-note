# Linked Lists

when a linked list is born, it doesn’t need 7 bytes of memory all in one place. One byte could live somewhere, while the next byte could be stored in another place in memory altogether! Linked lists don’t need to take up a single block of memory; instead, the memory that they use can be scattered throughout.
this is the greatest difference between the array and the link list


## A node only knows about what data it contains, and who its neighbor is


# Linked List consist of 
* Linked List -
   A data structure that contains nodes that links/points to the next node in the list.
* Singly
   Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
* Doubly 
 Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
* Node - 
  Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
* Next -
   Each node contains a property called Next. This property contains the reference to the next node.
* Head -
   The Head is a reference of type Node to the first node in a linked list.
* Current -
   The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.