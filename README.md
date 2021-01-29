# Apocalyptic Coding Challenge

Get as many of the challenges completed before the ~~challenge~~ world ends at 12:50PM.

- Console log the challenge number and the outputs of the predefined test cases so we can test for the winner
- Winner is measured by the person or squad who correctly solves the most challenges 
- Collaborating with others? +5 points
- Turn in your answers to the #coding-challenge Slack channel
- Winner will be announced Monday; get the most points here and get the most points on Engage!

### 1. Two Sum

Given an array of integers `nums` and an integer `target`, return _indices of the two numbers such that they add up to_ `target`.

You may assume that each input would have _exactly one solution_, and you may not use the same element twice.

You can return the answer in any order.

**Test Case 1:**
```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Because nums[0] + nums[1] == 9, we return [0, 1].
```
**Test Case 2:**
```
Input: nums = [3,2,4], target = 6
Output: [1,2]
```
**Test Case 3:**
```
Input: nums = [3,3], target = 6
Output: [0,1]
```

### 2. Add Two Numbers

You are given two **non-empty** linked lists representing two non-negative integers. The digits are stored in **reverse order**, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.

You may assume the two numbers do not contain any leading zero, except the number 0 itself.

![Nodes](addtwonumber1.jpg)

**Test Case 1:**
```
Input: l1 = [2,4,3], l2 = [5,6,4]
Output: [7,0,8]
Explanation: 342 + 465 = 807.
```
**Test Case 2:**
```
Input: l1 = [0], l2 = [0]
Output: [0]
```
**Test Case 3:**
```
Input: l1 = [9,9,9,9,9,9,9], l2 = [9,9,9,9]
Output: [8,9,9,9,0,0,0,1]
```
**Constraints:**

- The number of nodes in each linked list is in the range [1, 100].
- 0 <= Node.val <= 9
- It is guaranteed that the list represents a number that does not have leading zeros.

### 3. Longest Substring Without Repeating Characters

Given a string s, find the length of the longest substring without repeating characters.

**Test Case 1:**
```
Input: s = "abcabcbb"
Output: 3
Explanation: The answer is "abc", with the length of 3.
```
**Test Case 2:**
```
Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.
```
**Test Case 3:**
```
Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.
```
**Test Case 4:**
```
Input: s = ""
Output: 0
```
Constraints:
-0 <= s.length <= 5 ** 104
-s consists of English letters, digits, symbols and spaces.

### 4. Median of Two Sorted Arrays

Given two sorted arrays `nums1` and `nums2` of size `m` and `n` respectively, return the **median** of the two sorted arrays.

**Follow up:** The overall run time complexity should be `O(log (m+n))`.

**Test Case 1:**
```
Input: s = "abcabcbb"
Output: 3
Explanation: The answer is "abc", with the length of 3.
```
**Test Case 2:**
```
Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.
```
**Test Case 3:**
```
Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.
```
**Test Case 4:**
```
Input: s = ""
Output: 0
```
Constraints:
-0 <= s.length <= 5 ** 104
-s consists of English letters, digits, symbols and spaces.


