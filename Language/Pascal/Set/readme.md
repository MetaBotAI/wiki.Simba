# type: Set
https://en.wikipedia.org/wiki/Pascal_(programming_language)#Set_types
- relation: https://en.wikipedia.org/wiki/Bit_array

>A set is a fundamental concept for modern mathematics, and they may be used in many algorithms. Such a feature is useful and may be faster than an equivalent construct in a language that does not support sets. For example, for many Pascal compilers:
>
>`if i in [5..10] then ...`
>executes faster than:
>
>`if (i > 4) and (i < 11) then ...`
>Sets of non-contiguous values can be particularly useful, in terms of both performance and readability:
>
>`if i in [0..3, 7, 9, 12..15] then ...`
