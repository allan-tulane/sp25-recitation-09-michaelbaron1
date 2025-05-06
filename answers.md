# CMPS 2200 Recitation 09

## Answers

**Name:**Michael Baron
**Name:**Troy Freed


Place all written answers from `recitation-09.md` here for easier grading.



- **2)**
for K = nodes and E = edges total then worst case work would be O(E + KlogK)
- e for each edge that is processed once during frontier 
- klogk becasue each node get procesed once, while checking each of it neighbors logk times as they are stored in priority queue order 
- **4)**
O(n^2 * logn)
- logn to for same as previous
- for each city, n, there are n * (n-1) pairs = n^2 - n which is n^2 for work
