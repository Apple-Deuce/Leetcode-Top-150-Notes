# Queues & Priority Queues

## Explanation

- Like a **Stack**, but first in, first out
- Can be implemented with an array
- To limit an array to only use **Queue** methods, you must create it yourself
- Unlike an array, where elements can be added at the beginning or the end, you can only add items to the end of a queue.
- Priority Queues are queues where you pass both the element as well as the priority of that element into the queue. (e.g. All elements passed into a **Max-Priority Queue** with a priority of 5 will be ahead of elements with a priority >= 4, regardless of when they were added. The opposite is true for a **Min-Priority Queue**)

### Examples

- Like waiting in a line or a print queue. The first person to get into line will be the first to leave the line.
- Priority Queues are similar to getting in line by boarding groups at an airport terminal.


## Functions

- **Enqueue** : Pushes the first item into a queue.
- **Dequeue** : Removes the first item from a queue. **Shift** method is used to pull off the first item from an array and returns it.
- **Front** : Returns the first item in an array without removing it.
- **Size** : Displays the length of elements in the array (in ES6, size is a prop instead of a method, so no parens should be added when calling it. e.g. Queue.size instead of Queue.size()).
- **IsEmpty** : Returns a boolean value of if there are any elements in the queue.



