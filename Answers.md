/*Answers for these questions
1. What are the order of insertions/removals for the following data structures? Stack / Queue 

Answers: 
For Stack: add on to the end, and remove from the end. Like piling books, you add one on at the top, and if you want to get one, remove the one you just added on the top;
         
For Quese: add on to the end, and remove from the beginning. Like waiting in a line. A person join the line from the end, and another person goes through from the beginning of the line;


2. What is the retreival time complexity for the following data structures? Linked List / Hash Table / Binary Search Trees

Answers:
For Linked List: The search time complexity for Linked List is O(1), because all these nodes have head and/or tail pointers to connect all the nodes one to another.

For Hash Table: Basically the search time complexity for hash talbe is O(1). A input will be processed by hash function, and saved in bucket. But when there are collisions, more than one input will be saved in the same bucket, or when the hash table needs to be resized, the search time complexity will change to O(n);

For Binary Search Trees: Binary search tree is really efficient, each node could have two children, either one or the other, so every time search through Binary Search Tree, half the tests are cut off. The time complexity is O(log(n)).


3. What are some advantages to using a Hash Tables over an array in JavaScript?

Answer: For a simple hash table, one input gets an index from hash function. So the hash table could point to the specific input through the index directly. Time complexity for Hash Table is O(1). For array, every time you want to find something, you have to iterate through the whole array, cause item saved in array is not pointed to each other. Time complexity for Array is O(n). Efficiency for search, insert and remove items is one advantages to use Hash Table. 

*/