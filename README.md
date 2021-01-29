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
Input: nums1 = [1,3], nums2 = [2]
Output: 2.00000
Explanation: merged array = [1,2,3] and median is 2.
```
**Test Case 2:**
```
Input: nums1 = [1,2], nums2 = [3,4]
Output: 2.50000
Explanation: merged array = [1,2,3,4] and median is (2 + 3) / 2 = 2.5.
```
**Test Case 3:**
```
Input: nums1 = [0,0], nums2 = [0,0]
Output: 0.00000
```
**Test Case 4:**
```
Input: nums1 = [], nums2 = [1]
Output: 1.00000
```
Constraints:
- `nums1.length == m`
- `nums2.length == n`
- `0 <= m <= 1000`
- `0 <= n <= 1000`
- `1 <= m + n <= 2000`
- `-10^6 <= nums1[i], nums2[i] <= 106`

### 5. Longest Palindromic Substring

Given a string `s`, return the longest palindromic substring in `s`.

**Test Case 1:**
```
Input: s = "babad"
Output: "bab"
Note: "aba" is also a valid answer.
```
**Test Case 2:**
```
Input: s = "cbbd"
Output: "bb"
```
**Test Case 3:**
```
Input: s = "a"
Output: "a"
```
**Test Case 4:**
```
Input: s = "ac"
Output: "a"
```
Constraints:
- `1 <= s.length <= 1000`
- `s` consist of only digits and English letters (lower-case and/or upper-case)

### 6. Integer to Roman

Roman numerals are represented by seven different symbols: `I, V, X, L, C, D and M`.

```
Symbol       Value
I             1
V             5
X             10
L             50
C             100
D             500
M             1000
```

For example, `2` is written as `II` in Roman numeral, just two one's added together. `12` is written as `XII`, which is simply `X + II`. The number `27` is written as `XXVII`, which is `XX + V + II`.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not `IIII`. Instead, the number four is written as `IV`. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as `IX`. There are six instances where subtraction is used:

`I` can be placed before `V` (5) and `X` (10) to make 4 and 9. 
`X` can be placed before `L` (50) and `C` (100) to make 40 and 90. 
`C` can be placed before `D` (500) and `M` (1000) to make 400 and 900.
Given an integer, convert it to a roman numeral.

**Test Case 1:**
```
Input: num = 3
Output: "III"
```
**Test Case 2:**
```
Input: num = 4
Output: "IV"
```
**Test Case 3:**
```
Input: num = 9
Output: "IX"
```
**Test Case 4:**
```
Input: num = 58
Output: "LVIII"
Explanation: L = 50, V = 5, III = 3.
```
**Test Case 5:**
```
Input: num = 1994
Output: "MCMXCIV"
Explanation: M = 1000, CM = 900, XC = 90 and IV = 4.
```

Constraints:
- `1 <= num <= 3999`

### 7. Valid Parenthesis

Given a string `s` containing just the characters `'(', ')', '{', '}', '[' and ']'`, determine if the input string is valid.

An input string is valid if:

Open brackets must be closed by the same type of brackets.
Open brackets must be closed in the correct order.

**Test Case 1:**
```
Input: s = "()"
Output: true
```
**Test Case 2:**
```
Input: s = "()[]{}"
Output: true
```
**Test Case 3:**
```
Input: s = "(]"
Output: false
```
**Test Case 4:**
```
Input: s = "([)]"
Output: false
```
**Test Case 5:**
```
Input: s = "{[]}"
Output: true
```

Constraints:
- `1 <= s.length <= 10^4`
- s consists of parentheses only '`()[]{}'`.

### 8. Group Anagrams

Given an array of strings strs, group the anagrams together. You can return the answer in any order.

An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.

**Test Case 1:**
```
Input: strs = ["eat","tea","tan","ate","nat","bat"]
Output: [["bat"],["nat","tan"],["ate","eat","tea"]]
```
**Test Case 2:**
```
Input: strs = [""]
Output: [[""]]
```
**Test Case 3:**
```
Input: strs = ["a"]
Output: [["a"]]
```

Constraints:
- `1 <= s.length <= 10^4`
- `0 <= strs[i].length <= 100`
- `strs[i]` consists of lower-case English letters.

### 9. Search Insert Position

Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.

**Test Case 1:**
```
Input: nums = [1,3,5,6], target = 5
Output: 2
```
**Test Case 2:**
```
Input: nums = [1,3,5,6], target = 2
Output: 1
```
**Test Case 3:**
```
Input: nums = [1,3,5,6], target = 7
Output: 4
```
**Test Case 4:**
```
Input: nums = [1,3,5,6], target = 0
Output: 0
```
**Test Case 5:**
```
Input: nums = [1], target = 0
Output: 0
```

Constraints:
- `1 <= s.length <= 10^4`
- `-10^4 <= nums[i] <= 10^4`
- `nums` contains distinct values sorted in ascending order.
- `-10^4 <= target <= 10^4`

### 10. Implement strStr()

Implement `strStr()`.

Return the index of the first occurrence of needle in haystack, or `-1` if needle is not part of haystack.

**Clarification:**

What should we return when `needle` is an empty string? This is a great question to ask during an interview.

For the purpose of this problem, we will return 0 when `needle` is an empty string. This is consistent to C's `strstr()` and Java's `indexOf()`.

**Test Case 1:**
```
Input: haystack = "hello", needle = "ll"
Output: 2
```
**Test Case 2:**
```
Input: haystack = "aaaaa", needle = "bba"
Output: -1
```
**Test Case 3:**
```
Input: haystack = "", needle = ""
Output: 0
```

Constraints:
- `0 <= haystack.length, needle.length <= 5 * 10^4`
- `haystack` and `needle` consist of only lower-case English characters.







