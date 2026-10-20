Linked-List Assignment: Merge Two Sorted Lists

1. Overview

This project solves LeetCode Problem #21, Merge Two Sorted Lists, using Java.

2. Problem Description

Given two sorted linked lists, "list1" and "list2", merge them into one sorted linked list and return its head.

3. Approach

This solution uses recursion to merge the two lists.

- If one list is empty, return the other list.
- Compare the values of the first nodes in both lists.
- Select the smaller value and recursively merge the remaining nodes.
- Return the head of the merged list.

4. Programming Language

- Java

5. Example

Input:

- List 1: "1 → 2 → 4"
- List 2: "1 → 3 → 4"

Output:
"1 → 1 → 2 → 3 → 4 → 4"

6. Complexity Analysis

- Time Complexity: O(n + m), where n and m are the lengths of the two linked lists.
- Space Complexity: O(n + m) in the worst case due to recursive function calls.

7. How to Run

1. Copy the Java solution into your Java project or LeetCode editor.
2. Ensure the "ListNode" class is defined correctly.
3. Run the solution with two sorted linked lists as input.

8. Assignment Details

- Topic: Merge Two Sorted Lists
- Platform: LeetCode
- Problem Number: 21
- Language: Java