# Programming Pearls

Exercises from the famous Programming Pearls by Jon Bentley.

***
# Current content

# Column 1

* Fast system sort implementation using a **bitmap** data structure along with an efficient algorithm for 
sampling `k` unique elements in range `[1, n]`, for which I used the **floyd's random sampling algorithm.** The problem is to design an efficient algorithm to sort a list of 
`1,000,000` distinct positive elements all lesser than `10,000,000` using lesser than `2 MB` storage. The sorting 
algorithm designed here beats the Java system sort by a factor of `4`.


# Column 2 - Algorithms

* Group anagrams in a list of words. Solved by assigning each word a **signature** that is its sorted form 
and grouping all words with the same signature together.
* Rotate a vector by `i` positions in-place. Boils down to changing vector `ab` to `ba` where `a` and `b`
represent a contiguous block of elements. This is elegantly solved by employing a bunch of `reverse` operations
on the array. 

