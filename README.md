# DataStructures
Project 3 takes a prefix(!), postfix(#), or infix(@) expression as input, builds a binary tree, and outputs to the console:  
1. The expression converted to prefix (using a preorder traversal)  
2. The expression converted to infix with proper parentheses (using an inorder traversal)  
3. The expression converted to postfix (using a postorder traversal)  
4. A level order traversal of the expression  
5. A graphic of the binary tree  

This program implements a Queue and Stack class that use a Single Linked List (all built from scratch).

Example input:  
@2+3+4\*5  

Example output:  
\+ \+ 2 3 * 4 5  
((2 + 3) + (4 * 5))  
2 3 + 4 5 * +  
\+ \+ * 2 3 4 5  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; +  
&nbsp;&nbsp; + &nbsp;&nbsp; *  
&nbsp; 2 3 4 5  
