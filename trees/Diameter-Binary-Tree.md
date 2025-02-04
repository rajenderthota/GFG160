Difficulty: Medium 

Given a binary tree, the diameter (also known as the width) is defined as the number of edges on the longest path between two leaf nodes in the tree. This path may or may not pass through the root. Your task is to find the diameter of the tree.

Examples:

Input: root[] = [1, 2, 3]

![Untitled](https://github.com/user-attachments/assets/4fcf8956-49de-4a1a-9935-7a1b20591a91)


Output: 2
Explanation: The longest path has 2 edges (node 2 -> node 1 -> node 3).

Input: root[] = [5, 8, 6, 3, 7, 9]
![Untitled](https://github.com/user-attachments/assets/1563ce24-c084-407e-bb02-aaff89481c72)

Output: 4
Explanation: The longest path has 4 edges (node 3 -> node 8 -> node 5 -> node 6 -> node 9).
![Untitled](https://github.com/user-attachments/assets/78f8074c-46f9-4bef-afe8-ee9b03820413)

Constraints:
1 ≤ number of nodes ≤ 105
0 ≤ node->data ≤ 105
