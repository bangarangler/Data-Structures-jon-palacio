Answer the following questions for each of the data structures you implemented as part of this project.

## Queue

1. What is the runtime complexity of `enqueue`? O(1)
O(1) or constant

2. What is the runtime complexity of `dequeue`? O(1)
O(1) or constant

3. What is the runtime complexity of `len`? O(1)
O(1) or constant

## Binary Search Tree

1. What is the runtime complexity of `insert`?
O(n) or linear

2. What is the runtime complexity of `contains`?
O(n) or linear

3. What is the runtime complexity of `get_max`?
O(n) or linear

## Heap

1. What is the runtime complexity of `_bubble_up`?
O(log(n)) or logarithmic

2. What is the runtime complexity of `_sift_down`?
O(log(n)) or logarithmic

3. What is the runtime complexity of `insert`?
O(log(n)) or logarithmic

4. What is the runtime complexity of `delete`?
O(log(n)) or logarithmic

5. What is the runtime complexity of `get_max`?
O(1) or constant

## Doubly Linked List

1. What is the runtime complexity of `ListNode.insert_after`?
O(1) or constant

2. What is the runtime complexity of `ListNode.insert_before`?
O(1) or constant

3. What is the runtime complexity of `ListNode.delete`?
O(1) or constant

4. What is the runtime complexity of `DoublyLinkedList.add_to_head`?
O(1) or constant

5. What is the runtime complexity of `DoublyLinkedList.remove_from_head`?
O(1) or constant

6. What is the runtime complexity of `DoublyLinkedList.add_to_tail`?
O(1) or constant

7. What is the runtime complexity of `DoublyLinkedList.remove_from_tail`?
O(1) or constant

8. What is the runtime complexity of `DoublyLinkedList.move_to_front`?
O(1) or constant

9. What is the runtime complexity of `DoublyLinkedList.move_to_end`?
O(1) or constant

10. What is the runtime complexity of `DoublyLinkedList.delete`?
O(1) or constant

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the JS `Array.splice` method. Which method generally performs better?
    js array splice method worst case runtime would be O(n) so doubly linked
    list delete would be better. having to recreate the array for js makes it a
    bit slower
