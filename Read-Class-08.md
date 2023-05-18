# Stacks and Queues
The provided text explains the concepts of stacks and queues. Here's a summary:

### Stacks:
- A stack is a data structure that follows the FILO (First In Last Out) or LIFO (Last In First Out) principle.
- It consists of nodes, where each node references the next node in the stack but not the previous one.
- Common operations:
  - Push: Add a node to the top of the stack.
  - Pop: Remove the node from the top of the stack.
  - Peek: View the value of the top node without removing it.
  - IsEmpty: Check if the stack is empty.
- Pushing a node onto a stack is an O(1) operation.
- Popping a node from a stack is also an O(1) operation.
- Peeking and checking if the stack is empty are O(1) operations.

### Queues:
- A queue is a data structure that follows the FIFO (First In First Out) or LILO (Last In Last Out) principle.
- It consists of nodes, where each node references the next node in the queue.
- Common operations:
  - Enqueue: Add a node to the rear of the queue.
  - Dequeue: Remove the node from the front of the queue.
  - Peek: View the value of the front node without removing it.
  - IsEmpty: Check if the queue is empty.
- Enqueuing a node into a queue is an O(1) operation.
- Dequeuing a node from a queue is also an O(1) operation.
- Peeking and checking if the queue is empty are O(1) operations.

### Analogy
Here's an analogy to help understand stacks and queues:
Imagine you are at a cafeteria with a tray in your hand, and there are people standing in line behind you.

1. Stack Analogy: 
   - The tray represents a stack. You can add plates, one on top of another, to the tray.
   - When you want to remove a plate, you can only take the one on the top of the stack.
   - The last plate you put on the tray will be the first one you remove. It's like a stack of plates where the first plate you put down is at the bottom, and the last plate you put down is on top.
   - This is similar to how a stack works, where the last item added (pushed) is the first item removed (popped).

2. Queue Analogy:
   - The line of people behind you represents a queue. Each person is waiting for their turn to order food.
   - When a new person arrives, they join the back of the line (enqueue).
   - When it's your turn to order, you are served and move to the front of the line (dequeue).
   - The person at the front of the line is the first one to be served (first in) and the person at the back of the line is the last one to be served (last in).
   - This is similar to how a queue works, where the first item added (enqueued) is the first item removed (dequeued).

Using these analogies, you can understand the basic principles of stacks and queues and how they differ in terms of the order of adding and removing items.

### "Why, What, How" structure:

Here's a breakdown of stacks and queues using a "Why, What, How" structure:

**Stacks:**

Why:
- Stacks are used to manage data in a Last In First Out (LIFO) manner.
- They are designed to prioritize the most recently added items.

What:
- A stack is a data structure that consists of nodes.
- Each node has a reference to the next node in the stack, forming a chain.
- The topmost node represents the current top of the stack.
- Common operations on stacks include push (adding a node to the top), pop (removing the top node), peek (viewing the top node), and checking if the stack is empty.

How:
- To push a node onto a stack, you create a new node and assign its next reference to the current top. Then, you update the top to the newly added node.
- To pop a node from a stack, you reassign the top to the next node in the stack and return the value of the original top.
- Peeking involves accessing the value of the top node without modifying the stack.
- Checking if the stack is empty is done by verifying if the top node is null.

**Queues:**

Why:
- Queues are used to manage data in a First In First Out (FIFO) manner.
- They are designed to maintain the order in which items are added.

What:
- A queue is a data structure that consists of nodes.
- Each node has a reference to the next node in the queue, forming a linked list.
- The front node represents the current front of the queue, and the rear node represents the current rear.
- Common operations on queues include enqueue (adding a node to the rear), dequeue (removing the front node), peek (viewing the front node), and checking if the queue is empty.

How:
- To enqueue a node, you create a new node and assign its reference to the next property of the rear node. Then, you update the rear to the newly added node.
- To dequeue a node, you reassign the front to the next node in the queue and return the value of the original front.
- Peeking involves accessing the value of the front node without modifying the queue.
- Checking if the queue is empty is done by verifying if the front node is null.

By understanding the purpose, structure, and operations of stacks and queues, you can effectively manage and manipulate data according to the desired order of retrieval or removal.
