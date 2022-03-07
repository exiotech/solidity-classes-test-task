# Problem

Given a string s consisting of lowercase English letters, find and return the first instance of a non-repeating character in it. If there is no such character, return '_'.

## Examples

For `s = "abacabad"`, the output of `solution(s)` should be `c`
*There are 2 non-repeating characters in the string: 'c' and 'd'. Return c since it appears in the string first.*

For `s = "abacabaabacaba"`, the output of`solution(s)` should be `_`.
*There are no characters in this string that do not repeat.*

## Input/Output
[input] string s
A string that contains only lowercase English letters.

[output] char
The first non-repeating character in s, or '_' if there are no characters that do not repeat.
