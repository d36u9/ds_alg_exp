# Algorithms Design Tips

## 1 DON'T SORT
DO it IFF you run out of ideas to avoid it

## 2 Data Structures First
Data Structures determine what algorithms can be applied and their performance.<br>
Take space and Time tarde offs into consideration when we design/use data structures.

## 3 IO is a key factor
Faster Algorithms can be slower than slower algorithms on slower IO oprations.
e.g. Bubble sort (in memory) vs Merge sort (external network disk)

## Big-O notation is only a guidance
It's math. Not a reality in most cases.
e.g. Bubble sort can consistently beat quick sort (when the number of elements < 32 or 64)

...to be continued