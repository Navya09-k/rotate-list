# rotate-list
The program rotates a linked list to the right by k positions. It first counts the nodes, connects the last node to the first to form a circle, and then breaks the circle at the correct position. Using k modulo the list length avoids unnecessary rotations. The solution runs in O(n) time and O(1) space.
