Palindrome checker.

https://leetcode.com/problems/palindrome-number/

```apl
pal ← (⌽⍕)≡⍕
pal 'racecar' ⍝ 1
pal 'racecars' ⍝ 0
pal 10 ⍝ 0
pal 101 ⍝ 1
```