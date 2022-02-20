# DSA
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
28. Evaluate Division => this is undirected graph problem which includes math first task is to build graph adj lists then for every query find the path from source to target by multiplying edges.
29. Battleships in a Board => simple problem dfs like number of islands & this can be solved by just grazing on run
30. Distribute Coins in Binary Tree => this is postorder problem with lot of thought process where we will ask every child what do you want from parent
31. Lowest Common Ancestor of Deepest Leaves => problem can be solved in two steps first find deepes level left and right boundary then find lca using dfs
32. Delete Nodes And Return Forest => very good problem of dfs where we will graze while checking if curr node in target list or not
33. Reduce Array Size to The Half => first create frequency table then store frequencies in maxHeap then do the process
34. Maximum Score From Removing Stones => this is maxHeap problem push all the ip to maxHeap then pop untill we get the result
35. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold => this is simple sliding window problem where we can convert avg to total then count no of subarray of size k with sum gteq total
36. Satisfiability of Equality Equations => simple graph constructing then doing dfs to find the target in particular connected component
37. Time Needed to Buy Tickets => simple observation based algo involves little math 
38. Maximum Level Sum of a Binary Tree => simple level order problem
39. Maximal Network Rank => simple observation based indegrees adj matrix problem
40. Course Schedule IV => simple constructing the graph then doing individual dfs to finding the target
41. Minimize Maximum Pair Sum in Array => sorting then two pointer moving towards each other
42. Validate Binary Tree Nodes => tree root is child to no node so it is observation based problem doing level order with set to handle edge case where tree is graph
43. Next Permutation => this problem is observation based where it can be solved using algorithm VIMP problem (9th problem of sde sheet)
44. Two Furthest Houses With Different Colors => very simple problem which involves observation to get max distance we need to involve either end
45. Watering Plants => simple problem we have to simulate the process and some array specific math
46. Arithmetic Subarrays => problem is simple involves sorting logic and if we want to optimize in time then we need to make use of formula of finding diff bw two elements in arithmatic progression.
47. Find Center of Star Graph => this is very simple problem create freq table and return node which has val equal to nodes - 1
48. Minimum Number of Swaps to Make the String Balanced => this is totally observation based math problem but very easy if we get some insights
49.  Find All Groups of Farmland => bfs problem but if we observe it and figure out to graze over graph boundary then it is very simple problem
50.  Remove Colored Pieces if Both Neighbors are the Same Color => this is mind blowing problem can be solved using simple comman sense if we dont complicate it
51.  Check if All the Integers in a Range Are Covered => very simple problem to solve using brute force but there is trick to use prefix sum and solve it using linear time
52.  Maximum Product Difference Between Two Pairs => sorting problem or finding 2 min and max without sorting in one go
53.  Unique Length-3 Palindromic Subsequences => earlier this problem diverted me towards dp but this is observation based problem for odd palindromes
54.  Truncate Sentence => very simple straight forward simple problem
55.  Finding the Users Active Minutes => simple hashtable and set problem we just need to boil it down to basics
56.   Remove Stones to Minimize the Total => simple heap problem
57.  Check If String Is a Prefix of Array => implementation based very simple problem but description is little bit tricky
58.  Sum of All Odd Length Subarrays => this is classic array manipulation problem.
59.  Removing Minimum and Maximum From Array => simple array observation based problem
60.  Minimum Number of Buckets Required to Collect Rainwater from Houses => simple array visualization and simulation problem
61.  Minimum Cost Homecoming of a Robot in a Grid => simple array based greedy observation is very important
62.  Step-By-Step Directions From a Binary Tree Node to Another => finding the nodes then manipulate it this is very good observation based problem
63.  Check Whether Two Strings are Almost Equivalent => very simple hashmap problem with slice tempering of strings and ord function.
64.  Count Sorted Vowel Strings => simple pattern recognition observation based dp problem
65.  Floyd warshall algo finding shortest distance for all pairs of nodes => vimp problem asked in OA of clooktrack imp concept after dijkstra
66.  Reduction Operations to Make the Array Elements Equal => sorting and count simple problem
67.  Sum of Digits in Base K => very good basic math algorithmic problem
68.  Longest Substring Of All Vowels in Order => simple slinding window problem involving little bit observation to check if curr ele is less than previous
69.  First Missing Positive => very good problem brute force with the set and constant time with cyclic sort asked in yellow.ai
70.  Shuffle an Array => fisher yates algorithm going backwards logic partitions into array
71.  Find Good Days to Rob the Bank => preprocessing is necessary like largest histogram or trapping rainwater
72.  Rings and Rods => simple array manipulation problem
73.  Jewels and Stones => simple hashtable problem
74.  Increasing Order Search Tree => very very good problem with though process of inorder with head and tail pointers
75.  Range Sum of BST => first find source using bst prop then graze for that tree
76.  Missing Number => VIMP problem can be solved using set,math,xor and cyclic sort (1st problem of sde sheet)
77.  Sort Colors => sorting will solve this issue but dutch national flag algo comes to rescue for linear soln with intitution and edge case(2nd problem of sde sheet)
78.  Pow(x,n) => recursive and iterative VIMP problem (13th problem from sde sheet)
79.  Add Binary => very simple problem it can be solved using mod by 2 and divide by 2
80.  Maximum Subarray => this problem can be solved using brute force but this is famous for DP+Greed+Kadane algorithm(4th problme of sde sheet)
81.  Merge Intervals => very simple implementation based problem (5th problem of sde sheet)
82.  Set Matrix Zeroes => very simple implementaion based row and col header problem(7th problem of sde sheet)
83.  Find the Duplicate Number => freq table Or cyclic sort Or sorting Or tortoise and hare algo(cycle finding algo)(6th problem of sde sheet)
84.  integer to string => it is good example of use of % and / operator (asked in dolata capita,bombay)
85.  Minimum Absolute Difference => sorting and running logic problem asked by akshu
86.  Pascal Triangle => simple implementation based problem(8th problem of sde sheet)
87.  Reorder List => simple implementation based problem with logic of reversing half list like LL Palindrome problem(184th problem of sde sheet)
88.  Course Schedule II => topological sort problem with visited array and stack to find cycle in DAG simple problem to implement(131th problem of sde sheet)
89.  Best Time to Buy and Sell Stock => observation based iterative dp problem VIMP problem(10th problem of sde sheet)
90.  Search a 2D Matrix => this problem has 4 approaches Binary search problem(11th problem of sde sheet)
91.  Majority Element => Majority voting algorithm very simple and imp problem(14th problem of sde sheet)
92.  Majority Element II => Majorit voting algorithm very simplem but with some additional checks(15th problem of sde sheet)
93.  Binary Search => simple binary search problem to find target in sorted array
94.  First Bad Version => binary search problem where we have to shrink the boundaries Very good problem lot of time wasted to understand what is input
95.  Search Insert Position => binary search problem same as above to shrink the boundaries and couple of edge cases
96.  Rotate Image => transpose the matrix then reverse each row one thought and implementation based problem(12th problem of sde sheet)
97.  Two Sum => VIMP hashtable problem(18th problem of sde sheet)
98.  Unique Paths => Simple dp problem (17th problem of sde sheet)
99.  Determine if string is unique => witout map or set or char freq array of lenght 28 with bit manipulation VVIMP amazon,google,fb
100.  Squares of a Sorted Array => very simple problem two pointers moving in same direction 
101.  Rotate Array => VIMP and simple problem where reversing is logic
102.  Basic Calculator II => very imp problem not intuitive asked in google and fb
103.  Longest Consecutive Sequence => Set problem (20th problem of sde sheet)
104.  Reverse Linked List => simple standard interview problem(24th problem of sde sheet)
105.  Middle of the Linked List => tortoise and hare algorithm (25th problem of sde sheet)
106.  4Sum => Very Imp problem with visualization of how to skip the duplicates(19th problem of sde sheet)
107.  3Sum => very imp problem which is exact replica of above problem(39th problem of sde sheet)
108.  Longest Substring Without Repeating Characters => VIMP sliding window problem brute - better - best(23rd problem of sde sheet)
109.  Merge Two Sorted Lists => Very good two pointer problem with great visulalization VIMP(26th problem of sde sheet)
110.  Add Two Numbers => very simple problem(29th problem of sde sheet)
111.  Remove Nth Node From End of List => tortoise and hare algo with one edge case(27th problem of sde sheet)
112.  Linked List Cycle => Intuition behind floyd cycle detection algo (32nd problem of sde sheet)
113.  Linked List Cycle II => proof how can we get starting point of loop using floyd cycle detection algo(33rd problem of sde sheet)
114.  Intersection of Two Linked Lists => this can be solved using beautiful two ptr algorithm by switching heads at end(31st problem of sde sheet) 
115.  Palindrome Linked List => reversing half list(34th problem of sde sheet)
116.  Flatten a Multilevel Doubly Linked List => recursion based problem but easy to implement(35th problem of sde sheet)
117.  Rotate List => counting length + marking tail ptr + making k inbound + finding nth node from end VGP and VIMP (36th problem of sde sheet)
118.  Count Complete Tree Nodes => Perfect BT + math formulat to get Nodes of PBT + recursive soln + VIMP problem(40th problem of sde sheet)
119.  Max Consecutive Ones => simple brute force and greedy approach to track maxcount when ever count will be inreased(49th problem of sde sheet)
120.  Maximum Product of Three Numbers => finding max and min without sorting(50th problem of sde sheet)
121.  Remove Duplicates from Sorted Array => simple two ptr approach(42nd problem of sde sheet)
122.  Remove Duplicates from Sorted Array II => simple two ptr approach moving in same direction(48th problem of sde sheet)
123.  Move Zeroes => Very simple problem move non zero elements to start of array and add zeroes at remaining postions
124.  Two Sum II - Input Array Is Sorted => simple two pointer problem moving into opposite directions
125.  K Closest Points to Origin => like finding k smallest elements just modification of dist from origin
126.  Trapping Rain Water => VIMP two pointer problem (41st problem of sde sheet)
127.  Search in Rotated Sorted Array => VGP with some observation how array parts are sorted Binary Search problem(43rd problem from sde sheet)
128.  Subsets => VIMP Backtracking problem with 3 approaches(52nd problem of sde sheet)
129.  Reverse String => two pointer both recursive and iterative
130.  Reverse Words in a String III => String reverse simulation based problem with two pointers
131.  Number Complement => bit manipulation problem generate binary then flip bits then generate no
132.  Subsets II => VIMP followup question to subsets needs sorting and dup checkup(53rd problem of sde sheet)
133.  Non-decreasing Array => can we make array in increasing order by at most 1 replacement? VIIMP asked in mazon 1st interview not able to solve edge case yet
134.  Binary Tree to DLL => VIMP problem asked in mamazon with inplace no extraa space for list GFG (VIMP)
135.  Populating Next Right Pointers in Each Node => vimp level order problem but can be optimized in space using two pointers as it is PBT
136.  Permutation in String => Standard sliding window problem Vimp problem(150th problem of sde sheet)
137.  Reverse Pairs => This is very Imp problem using merge sort to count reverse pairs(16th problem of sde sheet)
138.  Longest Substring with At Most K Distinct Characters => asked in google VIMP sliding window and hashmap problem we can twist question make it equal to k distinct char by                                                              having check when when map has k keys then only keep track of length and reduce logic will be same as this question                                                              this is leetcode premium question so solved on GFG
139.  Smallest Integer Divisible by K => this is math problem with one edge case not sure how it is linked to pigeon hole principle
140.  Flood Fill => very simple dfs problem with one edge case (166th problem of sde sheet)
141.  Max Area of Island => very simple dfs problem MAANG favourite (165th problem of sde sheet)
142.  Combinations => this is standard backtracking problem
143.  Combination Sum => standard Backtraking problem with some crisp of dp(54th problem of sde sheet)
144.  Valid Sudoku => standard set problem(61st problem of sde sheet)
145.  Sqrt(x) => simple binary search problem(64th problem of sde sheet)
146.  Maximum Difference Between Node and Ancestor => preorder passing values from parent to childern
147.  Merge Two Binary Trees => simple preorder problem
148.  Rotting Oranges => very good multi source bfs problem(82nd problem of sde sheet)
149.  Find First and Last Position of Element in Sorted Array => this is simple bs problem(67th problem of sde sheet)
150.  Single Element in a Sorted Array => this is observation based binary search problem(66th problem of sde sheet)
151.  Magnetic Force Between Two Balls => exactly same as aggresive cows(71st problem of sde sheet)
152.  Implement Stack using Queues => simple problem can be solved using one queue(72nd problem of sde sheet)
153.  Implement Queue using Stacks => simple problem using input and output stacks(73rd problem of sde sheet)
154.  Sliding Window Maximum => this is standard deque and sliding window VIMP problem(80th problem of sde sheet)
155.  Min Stack => simple problem can be solved using two stacks(81st problem of sde sheet)
156.  Online Stock Span => this is very good stack problem similar lime Sliding window maximum(83rd problem of sde sheet)
157.  Roman to Integer => traversing from back is crux of this problem(88th problem of sde sheet)
158.  Integer to Roman => very simple mapping problem and reducing num untill gt 0(89th problem of sde sheet)
159.  Valid Parentheses => map and stack VIMP problem(74th problem of sde sheet)
160.  01 Matrix => similar to rotten oranges Multisource BFS problem(188th problem of sde sheet)
161.  Burst Balloons => One of the hard problem to digest the intuition including divide and conquer,sliding window and DP asked in google or fb
162.  Reverse Nodes in k-Group => this is simplest hard problem of linked list VIMP(33rd problem of sde sheet)
163.  Permutations => This is classic backtracking problem can be solved using both recursive and iterative way(58th problem of sde sheet)
164.  Largest Rectangle in Histogram => This is math and simulation based problem asked in Google FB Amazon(79th problem of sde sheet)
165.  Letter Case Permutation => standard backtracking problem very good
166.  Find the Town Judge => this is standard in and outdegree problem Very good GRAPH problem -- Google
167.  Climbing Stairs => VIMP dp problem asked in serviceNow(170th problem of sde sheet)
168.  House Robber => VIMP dp problem(174th problem of sde sheet)
169.  Complement of Base 10 Integer => brute force bit manipulation problem
170.  Triangle => this is classic dp problem and one of my favourite
171.  The kth Factor of n => very beautiful problem involves concept of converting linear solution to sqrt one using one observation
172.  Palindrome Partitioning => VIMP backtracking problem(56th problem of sde sheet)
173.  Power of Two => very good math problem can be solved using counting set bits
174.  Number of 1 Bits => it has core part of above problem
175.  Reverse Bits => this is brute force generate binary then build decimal
176.  Car Pooling => mix problem involves sorting then creation of map then simulation
177.  Contains Duplicate => brute -> sorting -> hashmap -> set very simple problem
178.  Linked List Random Node => brute force worked here but it is taking linear space to reduce it we have to know about concept of "Reservoir sampling".
179.  Intersection of Two Arrays II => very ambiguous question can be solved using sorting and two pointer
180.  Maximize number of 1s by flipping a subarray(sp) => VVVIMP problem can be solved using modification of kadanes algo
181.  Cherry Pickup II => very easy but thought full dp problem VIMP
182.  Range Sum Query - Immutable => VIMP problem can be solved using prefix sum
183.  Range Sum Query 2D - Immutable => VIMP problem can be solved using prefix matrix
184.  First Unique Character in a String => VIMP and simple problem can be solved using hashmap
185.  Reshape the Matrix => very simple simulation based problem
186.  Find original Array from given Prefix Sum Array => VVIMP basic question not on leetcode on gfg
187.  Maximum Points You Can Obtain from Cards => max sum of k elements from both ends circular sliding window problem VVVIMP
188.  Beggars Outside Temple (sp) => range queries to update donations VIMP prfix sum problem
189.  Maximum Sum Square SubMatrix (sp) => VIMP prefix sum matrix problem where top left is fixed and diff is given from top left to bottom right
190.  Minimum swaps required to bring all elements less than or equal to k together(sp - gfg) => this is classic observation based two pointer and sliding window problem VVVIMP
191.  Minimum number of swaps required to sort an array of first N number(sp - gfg) => brute force is to do selection sort(O(n ^ 2) but as question mention cyclic sort can                                                                                           solve this in linear time
192.  Given an array arr[], find the maximum j – i such that arr[j] > arr[i] OR Max Distance(sp - gfg) => brute force will take polynomial time so It is exactly same problem as                                                                                                          BUY and SELL STOCK problem we just have to club val and idx then sort                                                                                                           using values and apply same logic.
193.  Find Pivot Index (lc - sp - gfg) => very simple problem can be solved using prefix and suffix sum
194.  Valid Anagram => very simple problem can be solved using freq table
195.  Ransom Note => very similar hashmap problem
196.  Sum of Root To Leaf Binary Numbers => this is same problem as "sum of root to leaf(lc)" which can be solved using backtracking
197.  Sum of Subarrays(gfg - sp) => RAN ALL TC IN GFG BUT FAILED DESPITE OF WORKING SOLUTION VIMP can be solved using finding contribution of curr ele by finding in how many                                       subarray it is coming
198.  Remove Linked List Elements => both recursive and iterative solution.
199.  Remove Duplicates from Sorted List => very simple problem
200.  Minimum Number of Arrows to Burst Balloons => same as non overlapping intervals problem sort with then end times
201.  Median of Two Sorted Arrays => VIMP problem of binary search (68th problem of sde sheet)
202.  Sum of all Submatrices of a Given Matrix(sp - gfg) => very simple problem can be solved using contributions
203.  Find the row with maximum number of 1s(sp - gfg) => very simple but braintease problem I like this problem
204.  Binary Tree Preorder Traversal => both recursive and iterative (99th problem of sde sheet)
205.  Binary Tree Inorder Traversal => both recursive and iterative(98th problem of sde sheet)
206.  Binary Tree Postorder Traversal =>  both recursive and iterative (100th problem of sde sheet)
207.  Jump Game IV => Very classic graph BFS problem(228th problem of sde sheet)
208.  String to Integer (atoi) => VIMP string problem can be solved in 4 phases
209.  Binary Tree Level Order Traversal => simple level order traversal 
210.  Maximum Depth of Binary Tree => very simple dfs or bfs problem
211.  Symmetric Tree => very simple and IMP problem
212.  Rearrange an array so that arr[i] becomes arr[arr[i]] with O(1) extra space(sp - gfg) => VVVIMP storing two values at 1 idx adobe question
213.  A, B and Modulo (sp - stackOverflow) => Given two integers A and B, find the greatest possible positive M, such that A % M = B % M. asked in competitive coding .
214.  Modular Exponentiation/Power in Modular Arithmetic(sp - gfg) => Same as power just take % while doing computation to avoid TLE's
215.  Count pairs in array divisible by K(sp - gfg) => This is VVIMP problem creationg freq table of remainders and count them PAYPAL
216.  Prime Modulo Inverse(sp) => we can get modulo inverse by calling powermod fun of 214th problem
217.  Invert Binary Tree => VIMp problem with small trick
218.  Path Sum => Very simple and intuitive problem reduce val untill we go to leaf and have a check
219.  Word Pattern => just check respective loyalties with two maps
220.  Very Large Power => VIMp problem calculating (A ^ (B!) % C
221.  Count of divisors(sp - GFG) => this is hardest problem faced untill 17 Jan 2022 building sieve for smallest prime factor then divide and count the powers ..
222.  Copy List with Random Pointer => VIMP Implementation based problem(37th problem of sde sheet)
223.  Insert into a Binary Search Tree => very simple problem keep track of parent while doing iterative order traversal
224.  Search in a Binary Search Tree => very simple problem
225.  Can Place Flowers => This is very simple proble I LIKE THIS PROBLEM can be solved using simulation
226.  LRU Cache => this is VIMP problem (78th problem of sde sheet)
227.  Remove an element to maximize the GCD of the given array(sp -gfg) => classic prefix gcd and suffix gcd problem VIMP one
228.  Enumerating GCD(sp) => THis is classic brainteaser gcd problem
229.  Pubg(sp) => finding gcd of an array with some lavish story
230.  Largest number that divides x and is co-prime with y(sp - gfg) => very mathemaical problem and hard also
231.  Koko Eating Bananas => This is classic binary search problem similar like aggresive cows
232.  Kth Largest Element in a Stream => this is classic heap problem asked in amazon
233.  Gas Station => this is classic greedy problem which need to be boil down.. asked in fb
234.  Find two prime numbers with given sum(sp -gfg) => generate sieve then using two pointer locate the sum
235.  Prime Subsequences(sp) => cal no of primes then cal no of subsequence using 2 ^ n - 1 formula
236.  Lucky Numbers(sp) => generate a sieve and count all no which has 2 prime divisors
237.  Distinct Prime Factors of Array Product(sp - gfg) => take max ele of array generate sieve of smallest prime factors then cal divisors for each ele and add to set to return len
238.  Minimum number of primes required such that their sum is equal to N(sp -gfg) => goldbach conjecture and observations based problem This is BRAINTEASER
239.  Number of open doors(sp - gfg) => odd and even logic and sqrt and perfect square logic TCS question BRAINTEASER
240.  Sequential Digits => this can be solved using queue and some mathematics to construct next no
241.  Compute nCr % m(sp - codeforces) => can be solved using tabulation and dp table
242.  Compute nCr % p(sp - gfg) => inverse modulo and diff approach with python
243.  Lexicographic rank of a string(sp - gfg) => we have to calculate no of string lexicographically less than curr string using some thought process
244.  Detect Capital => very simple problem
245.  Valid Mountain Array => very simple two pointer problem
246.  All Elements in Two Binary Search Trees => very simple problem can be solved by traversing and merge function
247.  Single Number => solve using xor
248.  Design Add and Search Words Data Structure => this is exact trie problem where search fun is dependent on dfs
249.  Single Number II(sp) => only works natural no why it breaks for -ve no
250.  Check whether an Array can be made 0 by splitting and merging repeatedly(sp - gfg) => this problem involves some number system and boiled down to calculat no of odd no in aray
251.  Minimum XOR Value Pair(sp - gfg) => msb gets canceled in xor so sort the array and find out
252.  Count no of diff bits in two numbers => this question is made by me untill now using right shift and AND check with least significant bit
253.  find if ith bit is set or not => this question also made by me yet
254.  Sum of bit differences among all pairs(sp - gfg) => VIMP and classic bit problem where we have to go bit by bit on each array ele like single no 2
255.  Find the Missing Number in a sorted array(gfg) => asked in amazon very simple problem of binary search just shrinking the boundaries
256.  Minimum Number of Flips to Make the Binary String Alternating => google question which can be some thought process and implementation also
257.  Summary Ranges => this is two pointer problem moving in same direction
258.  Minimum Height Trees => truncating leaves one by one using indegree and bfs
259.  Largest Number At Least Twice of Others => very easy simulation based problem
260.  Single Number III(sp - leetcode) => get whole array xor then find out set bit location then divide array based on that location
261.  Shortest Completing Word => easy simulation based problem
262.  Count of Smaller Numbers After Self => this is classic merge sort problem on line of reverse pairs problem
263.  Find a number X such that (X XOR A) is minimum and the count of set bits in X and B are equal(sp - gfg) => first graze from MSB to LSB to set bit in ans whenever it is set in A then if B is still gt 0 then graze from LSB to MSB in answer to set bits to get min xor
264.  Strange Equality(sp) => this problem involves flipping active bits then finding most siginificant set bit then set 1 bit after that take little time to come up with this
265.  Divide Two Integers => it has standard process to do with some math
266.  Count total set bits in all numbers from 1 to n(sp -gfg) => this is classic formula based recursive problem
267.  Richest Customer Wealth => very simple problem
268.  Find Mode in Binary Search Tree => inorder trav with some cases to handle
269.  Minimum Absolute Difference in BST=> inorder trav with some little cases to handle as compare to above
270.  Longest Univalue Path => this is same as diameter of problem taking heights and keep tracks of path -- Google
271.  Sort Characters By Frequency => maxHeap will solve this problem -- Google
272.  Find All Anagrams in a String => sliding window and freq table problem.. 
273.  Sum of digit of a number using recursion(sp -gfg) => very simple problem
274.  Check if a number is magic (Recursive sum of digits is 1)(sp - gfg) => very simple problem
275.  Find Factorial!(sp -gfg) => very simple problem
276.  Program for Fibonacci numbers(sp - gfg) => very easy problem
277.  Print reverse of a string using recursion(sp - gfg) => very easy problem
278.  Another sequence problem(sp) => same line on the fibonacci
279.  4Sum II => easy problem can be solved with the help of hashtable
280.  Convert BST to DLL(LC premium) => using head and prev pointer doing it inplace
281.  Two Sum IV - Input is a BST => two bst iterators and two pointers problem
282.  Find Duplicate Subtrees => brainteaser how to check if subtree is equal do serialization with map
283.  Contiguous Array => very good problem
284.  Tower of Hanoi(sp - gfg) => best recursive problem
285.  K-th Symbol in Grammar => very good prblem - Google
286.  Gray Code => recursion based total algorithmic problem
287.  Island Perimeter => simple dfs problem with some modification -- Google
288.  Keys and Rooms => this is simple dfs problem - Google
289.  Merge k Sorted Lists => very simple problem with minHeap
290.  Shortest Bridge => very good problem with combination of dfs and multisource bfs
291.  Find All Numbers Disappeared in an Array => this is simple cyclic sort problem -- Google
292.  Split Array into Consecutive Subsequences => this is greedy problem with hashmap at each no check if can be included in prev subsequnce or can we create new subsequence
293.  Delete Characters to Make Fancy String => two pointer will help us out -- Google Microsoft(OA)
294.  Encode and Decode TinyURL => very simple problem using map --Google
295.  Largest Divisible Subset => this is dp problem cant able to solved using topdown but bottomup is be easy -- Google
296.  Guess Number Higher or Lower => simple bs problem -- Google
297.  Heaters => binary search problem with little modifications --Google
298.  Find K Closest Elements => binary search problem with little observations -- Google
299.  Word Break => brute force solution and dp map will work out --Google
300.  Decode String => this is classic stack problem with little thought process --Google
301.  Toeplitz Matrix => this is simulation based problem -- Google
302.  Count All Valid Pickup and Delivery Options => this is advanced permutations and combinations problem --Google
303.  Add Digits => simple simulation based problem
304.  Integer to English Words => only implementation based problem -- Google
305.  Merge two sorted arrays(sp - gfg) => simple two pointer problem
306.  Kth Smallest Element(sp) => finding it using selection sort where k <<< log(n)  
307.  Find the maximum possible value of a[i] % a[j] over all pairs of i and j(sp - gfg) => maxMod problem finding largest and second largest and return mod
308.  Check if array elements are consecutive(sp - gfg) => this is classic xor problem
309.  Chocolate Distribution Problem(sp - gfg) => very simple sorting problem
310.  K-diff Pairs in an Array => this is haskmap problem
311.  Subarray Sum Equals K => imp prefix sum and hashmap problem
312.  Interval List Intersections => two pointer problem with necessary observations -- Google
313.  Largest Number => comparing two string no concatenation is area of interest here
314.  Count Inversions in an array(sp -gfg) => this is same problem as reverse pairs can be solved using merge sort
315.  Minimum Increment to Make Array Unique => sort the array then check prev element
316.  Word Ladder => this is BFS graph problem
317.  Maximum Swap => preprocessing array by finding max no in right then swapping first idx which has max no in right
318.  QuickSort => this is very good problem
319.  Maximum & Minimum Magic(sp) => simple sorting problem
320.  Find the Minimum length Unsorted Subarray, sorting which makes the complete array sorted(sp - gfg) = tried brute force and it worked not yet tried optimized one
321.  Find the sum of maximum difference possible from all subset of a given array(sp - gfg) => we have to sort the array then using two loops cal no of subsequces for each pair of smallest and largest ele 
322.  Floor in a Sorted Array(gfg) => returning end after simple binary search
323.  Search insert position of K in a sorted array(sp - gfg) => it is like finding ceil of target no and return start after doing normal bs
324.  Swap Nodes in Pairs => simple recursion based problem
325.  Remove K Digits => Very good problem with montonic stack or deque
326.  Find an element in Bitonic array(sp - gfg) => very good binary search problem
327.  Special Integer(sp) => this is same problem like aggressive cows where we have to binary search and then cal for each mid if we can satify the condition VGP
328.  Remove Covered Intervals => simple brute force will work here
329.  Find median in row wise sorted matrix(sp -gfg) => VIMP problem of binary search   








