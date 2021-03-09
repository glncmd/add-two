# add-two
A small python project where: given two non-empty linked lists representing two non-negative integers; The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.

Assume the two numbers do not contain any leading zero, except the number 0 itself.

Sample output:
```python
#Input: l1 = [2,4,3], l2 = [5,6,5]
l1 = ListNode(2, ListNode(4, ListNode(3, None)))
l2 = ListNode(5, ListNode(6, ListNode(5, None)))

#Output: [7, 0, 9]
ListNode(7, ListNode(0, ListNode(9, None)))
```

Learnings:
* Linked Lists
* Chained assignments
* divmod() method

Problem from: https://leetcode.com/problems/add-two-numbers/
