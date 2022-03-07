# Problem

Write a function that reverses characters in (possibly nested) parentheses in the input string.
Input strings will always be well-formed with matching `()`s.

## Examples

For inputString = "(bar)", the output of `solution(inputString)` should be `"rab"`

For inputString = "foo(bar)baz", the output of `solution(inputString)` should be `"foorabbaz"`

For inputString = "foo(bar)baz(blim)", the output of `solution(inputString)` should be `"foorabbazmilb"`

For inputString = "foo(bar(baz))blim", the output of `solution(inputString)` should be `"foobazrabblim"`.

*Because `"foo(bar(baz))blim"` becomes `"foo(barzab)blim"` and then `"foobazrabblim"`.*

## Input/Output
[input] string inputString

A string consisting of lowercase English letters and the characters ( and ). It is guaranteed that all parentheses in inputString form a regular bracket sequence.

[output] string
Return `inputString`, with all the characters that were in parentheses reversed.
