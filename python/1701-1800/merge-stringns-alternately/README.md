| #    | Name                                                                                                                                             | Difficulty |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- |
| 1768 | [Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/description/?envType=study-plan-v2&envId=programming-skills) | Easy       |

---
You are given two strings word1 and word2. Merge the strings by adding letters in alternating order, starting with word1. If a string is longer than the other, append the additional letters onto the end of the merged string.

Return the merged string.

---

## Example 1
<pre>
Input: word1 = "abc", word2 = "pqr"
Output: "apbqcr"
Explanation: The merged string will be merged as so:
word1:  a   b   c
word2:    p   q   r
merged: a p b q c r
</pre>
---

## Example 2
<pre>
Input: word1 = "ab", word2 = "pqrs"
Output: "apbqrs"
Explanation: Notice that as word2 is longer, "rs" is appended to the end.
word1:  a   b 
word2:    p   q   r   s
merged: a p b q   r   s
</pre>
---

## Constraints
- 1 <= word1.length, word2.length <= 100
- word1 and word2 consist of lowercase English letters.