#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) bc how many times the loop runs is dependent only on what N is.


b) O(n^2)


c) O(n) though it is recursive, it still only runs based on how many bunnies there are.

## Exercise II

bc the floors would already be in order, you could use a binary search to find the correct output. Start in the middle with an egg. If it breaks, eliminate the floors above and move to half of the remaining floors to use another egg. If the original egg does not break eliminate the lower floors and move to the upper half of the floors to try again. This is the most efficient use and to my understanding will use the least amt of eggs. The runtime complexity worst case would be O(log n).
