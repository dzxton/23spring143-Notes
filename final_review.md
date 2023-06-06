Which of the following statements about Stack and Queue ADT is FALSE?

(A) Stack is First-In-Last-Out
(B) Queue is First-In-First-Out
(C) Stack can be used to implement a recursive algorithm iteratively
(D) Stack can only be implemented with array, and therefore its size is limited by the initial capacity

**Answer:** D


6.1 Explain why the entry value of the variable sortedMap is a Set, instead of a String.
```java

```

(15pt) Based on the following tree

          25
        /    \
       19    33
      / \    / 
     11  3  1  
What is the pre-order, in-order and post-order traversal of the above tree

pre-order: 25, 19, 11, 3, 33, 1


In-order: 1,3,11,19,25,33


post-order: 11, 3, 19, 1, 33, 25

Is this a binary search tree? How many nodes do you have to change to make it a binary search tree?
**Answer**: no, not a binary search tree because of the one on the right side. You would just have to change that node. 

Given the following code:
```java
    public static void print(ListNode list) {
        Stack<Integer> stack = new LinkedListStack<>(); // create new Stack

        ListNode ptr = list.next; // declares a pointer, initializing with next node
        while (ptr != null) { 
            stack.push(ptr.val); // push a value into the Stack till pointer is null
            ptr = ptr.next;
        }

        while (stack.size() != 0) {
      	    System.out.println(stack.pop()); // print out the reverse of the stack, first in last out
        }
    }
```
What does this code do?
**Answer:** prints the stack in reverse order.




