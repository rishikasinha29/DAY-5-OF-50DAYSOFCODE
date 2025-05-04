🔹 1. Palindrome Linked List
🧩 Problem:
 Given the head of a singly linked list, determine whether it forms a palindrome (i.e., reads the same forward and backward).
🧠 Approach:
First, find the middle of the linked list using the fast and slow pointer technique.
Reverse the second half of the linked list.
Compare the first half with the reversed second half node-by-node. If all values match, it’s a palindrome.
✅ Time Complexity: O(N) – We traverse the list a few times, but never more than twice.
 ✅ Space Complexity: O(1) – In-place reversal and comparison using only a few pointers.

🔹 2. Valid Perfect Square
🧩 Problem:
 Given a positive integer num, determine whether it is a perfect square without using any built-in square root functions.
🧠 Approach:
Apply binary search between 1 and num.
For each mid-point, square it and compare it with num.
If mid² equals num, it’s a perfect square. If mid² is greater, search the left half; otherwise, search the right half.
✅ Time Complexity: O(log N) – Binary search efficiently reduces the search space.
 ✅ Space Complexity: O(1) – Uses only a few integer variables.
