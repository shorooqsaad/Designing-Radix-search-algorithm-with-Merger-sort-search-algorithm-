# Designing-Radix-search-algorithm-with-Merger-sort-search-algorithm-
* Designing Radix with Merger sort-(Comparison method). Which is a Stable algorithm 
and we can make sure in each case the running time will be the same.
* Radix calling merge:
-getmax(): O(n) 
-toCharArray(): O(1)
 -Loop for calling sort() in O(d) times in max number of digit.
-For dividing, conquer and combine O(nlogn) recursively.
In final calculation, O(d*nlogn) assuming d= O(1).Therefore Running time is O(nlogn).
c) Radix with merge sort O(N log N), Radix with counting sort O(n). We can observe that 
Radix_Merge has a faster growth rate than Radix_Counting rate.
