### Stack

A stack is a linear data structure that follows the Last-In-First-Out (LIFO) principle. Elements are added to (pushed onto) and removed from (popped from) the top of the stack.

#### Operations and Time Complexity

1. **Push (Insert at the top)**:
   - **Array-based implementation**: O(1)
   - **Linked-list implementation**: O(1)

2. **Pop (Remove from the top)**:
   - **Array-based implementation**: O(1)
   - **Linked-list implementation**: O(1)

3. **Peek (Access the top element)**:
   - **Array-based implementation**: O(1)
   - **Linked-list implementation**: O(1)

#### Use Cases
- **Real-World Example**: Undo functionality in text editors, where the last action can be undone.
- **Real-World Example**: Expression evaluation and syntax parsing in compilers, where operators and operands are processed in LIFO order.

### Summary Table

| Operation                      | Stack (Array) | Stack (Linked List)  |
|--------------------------------|---------------|----------------------|
| Push (Insert at the top)       | O(1)          | O(1)                 |
| Pop (Remove from the top)      | O(1)          | O(1)                 |
| Peek (Access the top element)  | O(1)          | O(1)                 |


### When to Use Each Type

- **Array-based Stack**: Use when you have a fixed size of elements or can predict the maximum size of the stack. Example: implementing call stack in a program where maximum depth is known.
- **Linked List-based Stack**: Use when the number of elements is dynamic and you want to avoid the overhead of resizing the underlying array. Example: managing function calls in a recursive algorithm where the depth of recursion is unknown.

Both array-based and linked-list-based stacks have their advantages and are suitable for different scenarios based on the specific requirements of the application.
