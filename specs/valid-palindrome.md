# Valid Palindrome

A phrase is a palindrome if converting all uppercase letters into lowercase, and removing all letters and numbers, it reads the same forward and backward.

Given a string `x`, return `true` if it is a palindrome, or `false` otherwise.

**Example 1:**

```
Input: `x = "A man, a plan, a canal: Panama"`
Output: `true`
Explanation: "amanaplanacanalpanama" is a palindrome.
```

**Example 2:**

```
Input: `x = "race a car"`
Output: `false`
Explanation: "raceacar" is not a palindrome.
```

**Example 3:**

```
Input: `x = " "`
Output: `true`
Explanation: x is an empty string "" after removing non-alphanumeric characters.
Since an empty string reads the same forward and backward, it is a palindrome.
```

**Constraints:**

+ `1 <= s.length <= 2 * 10<sup>5</sup>`
+ `x` consists only of printable ASCII characters.
