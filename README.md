# LINKED-LIST-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAUMYA SINGH

*INTERN ID*: CT08SDY

*DOMAIN*: C LANGUAGE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

#DESCRIPTION#

TASK:- TO CREATE A PROGRAM TO IMPLEMENT A SINGLY LINKED LIST WITH OPERATIONS LIKE INSERTION,DELETION,AND TRAVERSAL

A Singly linked list is a linear data structure in which each element is a saperate object, known as a node.
OPERATIONS:-
          INSERTION: inserting a new node at the beginning end or at a specific posiitons in the list.
          DELETION:  deleting a node from the list
          TRAVERSAL: Traversing the list to access or modify the nodes.
          SEARCHING: Searching for a specific node in the list.
In this we have used varioys steps for the implementation i.e.,
STEP1: defining the node structure
      In this we define node to represent each element in the linked list.Node consist of two memebers:DATA and NEXT. 
      
STEP2: define linked list structure
      In this we define linkedlist to represent entire linked list. It consist of one member:HEAD
      
STEP3: implementing node creation function.
      We implemented createNode to create a new node with the given data. The function involves
- Allocation of memory for a new node using malloc
- Initialization of the data member with the given value
- Sets the next member to NULL
- Returns a pointer to the newly created node.

STEP4: implementing insertion function.
      We implement insertAtBeginning to insert a new node at the beginning of the linked list. The function involves
- Creating of a new node using the createNode function
- Sets the next member of the new node to the current head node
- Updates the head member of the linked list to point to the new node

STEP5: implementing printing function.
      We implemented a function called printList to print the contents of the linked list. The function:
- Starts at the head node and traverses the linked list
- Prints the data member of each node
- Continues until it reaches the end of the linked list 
STEP6: implementing freeing function.
     We implemented a function called freeList to free the memory allocated for the linked list. The function:
- Starts at the head node and traverses the linked list
- Frees the memory allocated for each node using free
- Continues until it reaches the end of the linked list (i.e., NULL)
- Sets the head member of the linked list to NULL.
