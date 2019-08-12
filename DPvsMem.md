# Dynamic Programming (DP) VS Memorization (MEM)

# Terminology 
DP a programming method\
MEM optimization, but usually refer to a method of Memorization + Recursion

## Difference in thinking:
DP bottom up\
MEM top down

## Implementation:
DP iteration/tabulation, can use memorization as well.\
MEM recursion

## Performance:
In most cases, their running time complexity (on paper) is almost the same (if they are both implemented optimally).\
The major difference on performance comes from recursive invokes(MEM) and iteration/tabulation (DP). In reality, DP usually has advantage here: locality. 

MEM does have one conditional advantage:\
If your solution doesn't need to visit all the inputs (e.g. a range/scope-limited search), MEM may take a leap. Thanks to its top down design, it only visits the inputs which affect the results.
