# guard-ds
Wrapper around fundamental data structure Array and Linked List.
Guard thread will do the row level locking of the underlying data structure and manage all read/write operations.
Idea is that multiple threads should be able to effectively work on the underlying data structure.