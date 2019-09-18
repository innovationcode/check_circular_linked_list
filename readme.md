# Problem :----

- Given a singly linked list, write a function which takes in the first node in a singly linked list and returns a boolean indicating if the linked list contains a "CYCLE".
- A cycle is when a node's next point actually points back to a previous node in the list. This is also known as a circularly linked list.

# Solution :----

- To solve this problem, will have two markers traversing through the list ```marker1``` and ```marker2```. We will habe both markers begin at the first node of the list and traverse through the linked list. However the second marker, ```marker2```, will move two nodes ahead for evry one node that ```marker1``` moves.

```
```
If the linked list has no cycle, then ```maeger2``` should be able to continue on until the very end, never equaling the first marker.

