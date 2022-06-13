# Linked List

Linked List is group of nodes which contains data and the address of pointer.

# Uses of Linked List

List do not always have to be present in the memory. A node can be anywhere in memory and then can be linked to make a list.

The List size is dependent on the memory size.

We can store more then basic type.

# Why use linked list over array?

The memory is dynamically assigned. All the nodes are linked with pointer.
There is no problem with sizing, because the list grow as per the programs demand.

# Singly linked list or One way chain

In Singly linked list has a node which contains 2 parts: The Data part and the link part.
In Singly linked list the direction is only forward.

# Operations on Singly Linked List


### Node Creation
```c
struct node // Declaration of Node
{  
    int data; // Data Type
    struct node *next; // Address of next node
};  
struct node *head, *ptr;   // Declaration of head
ptr = (struct node *)malloc(sizeof(struct node *));  // Allocate memory

```

### Insertion

1. Insertion at the beginnig
2. Insertion at end of the list
3. Insertion after specified node

### Deletion and Traversing
1. Deletion at beginning
2. Deletion at the end of the list
3. Deletion after specified node
4. Traversing
5. Searching