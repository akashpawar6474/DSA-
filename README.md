# DSA-
solutions to graze over
1. Even Odd tree => simple level order problem with slight modifications
2. All paths from source to end => simple graph backtracking problem which can be solved easliy using recursion template for backtracking
3. Mother vertex in directed graph => good dfs problem idea is to do dfs and remember last finished node as candidate of mother vertex. then do dfs from candidate and see if all other nodes are visited are not.
4.  Find the peak element => classic BS problem with good observations skills
5.  Find peak element in 2d array => full observation based and involved thought process
6.  Min Deletions to make char freq unique => simple greedy problem invloves map for preprocessing then set for calculating unique frequencies and remaining manipulations
7.  Minimum Number of Vertices to Reach All Nodes => DAG problem very simple involves IN/OUT degrees with including why? as we can only visit any vertex which has indegree 0 manually
8.  Maximum Length of a Concatenated String with Unique Characters => backtraking solution where we consider all combinations
9.  Find N Unique Integers Sum up to Zero => Math and observations based problem only task is to find how to fill the array
10. Regions Cut By Slashes => simple problem when we deduce this the number of islands problem just trick is to upscale the grid 3 times so we can easily do a dfsORBfs
11. Jump Game => recursive approach is very simple but time and space consuming Iterative is very efficient but involves thought process and neat observations
12. Jump Game 2 => same logic just extraa calculations to know min jumps
13. Jump Game 3 => bfs problem moving level by level and see if any idx(node) satisfy the condition
14. meeting room => find if person can attend all meetings simple sorting and observation to see if no interval overlap each other
15. meeting room2 => finding min rooms for arranging all the meeting brute force is O(n ^ 2) but using minHeap we can reduce it upto O(nlogn)
16. Count Good Nodes in Binary Tree => preorder passing value from parent to childern
17. Sign of the Product of an Array => idea is to avoid overflow and without doing prod determine sign based on no of -ve integers
18. Find Minimum in Rotated Sorted Array => similar to finding peak element little bit observations based using < in BS
19.  Reorder Routes to Make All Paths Lead to the City Zero => Idea is to create Adj list for both in/out degrees then do dfs and count all the edges whom are in out degree.
20.  Find largest Alphabet in string => simple problem can be solved using hashtable
21.  Redundant Connection => finding the edge which is causing cycle in undirected graph UNION AND FIND really good question
22.  Pacific Atlantic water flow => simple graph bfs dfs problem with traversing from boundary of matrix flood fill algo from ocean reverse thinking involved with some neat observations.
23. Palindromic Substrings => counting no of palindrome substrings New Concept even and odd palindrome easy one 
24. Longest Palindromic subsequece => same logic as LPSubstrig just diff is we dont look for remaing length when st and end ch matches 
25. Number of Operations to Make network connected => use fact that in connected graph of n nodes there is n - 1 edges and simple dfs
26. count primes => brute => better => best Sieve of Eratosthenes
27. Find Elements in a Contaminated Binary Tree => simple dfs with simple math of complete binary tree and set for remembering
