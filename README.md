# My Python Solutions for Leetcode

[The whole lists](https://github.com/qiyuangong/leetcode/tree/master/python):

&hearts; means you need a subscription.

| # | Title | Solution | Basic idea (One line) |
|---| ----- | -------- | --------------------- |
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/001_Two_Sum.py) | 1. Hash O(n) and O(n) space<br>2. Sort and search with two points O(n) and O(1) space |
| 2 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/002_Add_Two_Numbers.py) | Note the carry from lower digit. |
| 3 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/003_Longest_Substring_Without_Repeating_Characters.py) |1. Check every possible substring O(n^2) <br>2. Remember the character index and current check pos, if character index >= current pos, then there is duplicate |
| 4 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/004_Median_of_Two_Sorted_Arrays.py) | 1. Merge two sorted lists and compute median, O(m + n) and O(m + n)<br>2. An extension of median of two sorted arrays of equal size problem|
| 5 | [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/005_Longest_Palindromic_Substring.py) | [Background knowledge](http://en.wikipedia.org/wiki/Longest_palindromic_substring)<br>1. DP if s[i]==s[j] and P[i+1, j-1] then P[i,j]<br>2. A palindrome can be expanded from its center<br>3. Manacher algorithm|
| 7 | [Reverse Integer](https://leetcode.com/problems/reverse-integer/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/007_Reverse_Integer.py) | Overflow when the result is greater than 2147483647
| 8 | [String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/008_String_to_Integer(atoi).py) | Overflow, Space, and negative number |
| 9 | [Palindrome Number](https://leetcode.com/problems/palindrome-number/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/009_Palindrome_Number.py)| Get the len and check left and right with 10^len, 10 |
| 12 | [Integer to Roman](https://leetcode.com/problems/integer-to-roman/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/012_Integer_to_Roman.py) | [Background knowledge](http://www.rapidtables.com/convert/number/how-number-to-roman-numerals.htm) Just like 10-digit number, divide and minus |
| 13 | [Roman to Integer](https://leetcode.com/problems/roman-to-integer/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/013_Roman_to_Integer.py) | Add all curr, if curr > prev, then need to subtract 2 * prev |
| 15 | [3Sum](https://leetcode.com/problems/3sum/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/015_3Sum.py) | 1. Sort and O(n^2) search with three points <br>2. Multiple Two Sum (Problem 1) |
| 16 | [3Sum Closest](https://leetcode.com/problems/3sum-closest/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/016_3Sum_Closest.py) | Sort and Multiple Two Sum check abs|
| 18 | [4Sum](https://leetcode.com/problems/4sum/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/018_4Sum.py) | The same as 3Sum, but we can merge pairs with the same sum |
| 20 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/020_Valid_Parentheses.py) | 1. Stack<br>2. Replace all parentheses with '', if empty then True |
| 21 | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/021_Merge_Two_Sorted_Lists.py) | Add a dummy head, then merge two sorted list in O(m+n) |
| 23 | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/023_Merge_k_Sorted_Lists.py) | 1. Priority queue O(nk log k)<br>2. Binary merge O(nk log k)|  |
| 24 | [Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/024_Swap_Nodes_in_Pairs.py) | Add a dummy and store the prev |
| 28 | [Implement strStr()](https://leetcode.com/problems/implement-strstr/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/028_Implement_strStr().py) | 1. O(nm) comparison <br>2. KMP |
| 35 | [Search Insert Position](https://leetcode.com/problems/search-insert-position/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/035_Search_Insert_Position.py) | Binary Search |
| 46 | [Permutations](https://leetcode.com/problems/permutations/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/046_Permutations.py) | 1. Python itertools.permutations<br>2. DFS with swapping, O(n^2) and O(n^2)<br>3. iteratively generate n~permutations with n-1~permutations, O(n^3) and O(n^2) |
| 47 | [Permutations II](https://leetcode.com/problems/permutations-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/047_Permutations_II.py) | 1. DFS with swapping, check duplicate, O(n^2) and O(n^2)<br>2. iteratively generate n~permutations with n-1~permutations, O(n^3) and O(n^2) |
| 53 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/053_Maximum_Subarray.py) | 1. Recursion, O(nlgn), O(lgn)<br> 2. Bottom-up DP, O(n) and O(n)<br>3. Bottom-up DP, f(x) = max(f(x-1)+A[x], A[x]), f(x) = max(f(x-1)+A[x], A[x]),O(n) and O(1) |
| 54 | [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/054_Spiral_Matrix.py) | O(nm) 1. Turn in the corner and loop<br>2. (0, 1) -> (1, 0) -> (0, -1) -> (-1, 0) |
| 62 | [Unique Paths](https://leetcode.com/problems/unique-paths/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/062_Unique_Paths.py) | 1. Bottom-up DP, dp[i][j] = dmap[i-1][j] + dmap[i][j-1], O(mn) and O(mn)<br>2. Combination (m+n-2, m-1) |
| 63 | [Unique Paths II](https://leetcode.com/problems/unique-paths-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/063_Unique_Paths_II.py) | Bottom-up DP, dp[i][j] = dmap[i-1][j] + dmap[i][j-1] (if block, then 0), O(mn) and O(mn) |
| 65 | [Valid Number](https://leetcode.com/problems/valid-number/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/065_Valid_Number.py) | 1. strip leading and tailing space, then check float using exception, check e using split <br>2. check is number split by . or e, note that number after e may be negative |
| 66 | [Plus One](https://leetcode.com/problems/plus-one/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/066_Plus_One.py) | Check if current digit == 9. |
| 70 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/070_Climbing_Stairs.py) | Bottom-up DP, dp[i] = dp[i - 2] + dp[i- 1] <br>1. O(n) and O(n)<br>2. Only two variables are needed, O(n) and O(1) |
| 72 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/072_Edit_Distance.py) | [Background](https://en.wikipedia.org/wiki/Edit_distance)<br> 1. DP O(n^2) space<br>2. DP O(n) space |
| 78 | [Subsets](https://leetcode.com/problems/subsets/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/078_Subsets.py) | 1. DFS Recursion, O(2^n) and O(2^n)<br>2. Recursion on a binary number, O(2^n) and O(2^n)<br>3. Sort and iteratively generate n subset with n-1 subset, O(n^2) and O(2^n)|
| 90 | [Subsets II](https://leetcode.com/problems/subsets-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/090_Subsets_II.py) | 1. DFS Recursion with duplicate check, O(2^n) and O(2^n)<br>2. Recursion on a binary number, O(2^n) and O(2^n)<br>3. Sort and iteratively generate n subset with n-1 subset, note that if nums[index] == nums[index - 1] then generate from last end to curr end, O(n^2) and O(2^n) |
| 94 | [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/094_Binary_Tree_Inorder_Traversal.py) | 1. Recursion, O(n) and O(1)<br>2. Stack and check isinstance(curr, TreeNode), O(n) and O(n)<br>3. Stack and check left and right, O(n) and O(n) |
| 98 | [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/098_Validate_Binary_Search_Tree.py) | 1. Stack O(n) and O(n)<br>2. Recursion O(n) and O(n) |
| 104 | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/104_Maximum_Depth_of_Binary_Tree.py)| Recursion max(left, right) + 1 |
| 108 | [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/108_Convert_Sorted_Array_to_Binary_Search_Tree.py)| Recursion O(n) and O(nlgn)|
| 109 | [Convert Sorted List to Binary Search Tree](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/109_Convert_Sorted_List_to_Binary_Search_Tree.py) | 1. Two points fast (next next) and slow (next) O(nlgn) and O(n)<br>2. Bottom-up recursion O(n) and O(lgn) |
| 110 | [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/110_Balanced_Binary_Tree.py) | Recursion 1. Top-down O(n^2) and O(n), Bottom-up recursion with sentinel -1 O(n) and O(n) |
| 111 | [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/111_Minimum_Depth_of_Binary_Tree.py) | 1. Recursion, note that when size of left (ld) or right (rd) is 0, then min = 1 + ld + rd<br> 2. BFS check by level (right most), which is much faster than recursion |
| 124 | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/124. Binary Tree Maximum Path Sum.py) | Recursion O(n) and O(n), max (left + node, right + node, left + node + right) |
| 125 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/125_Valid_Palindrome.py)| Exclude non-alphanumeric characters and compare O(n) |
| 128 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/128_Longest_Consecutive_Sequence.py) | Set or hash, pop adjacency, O(n) and O(n) |
| 133 | [Clone Graph](https://leetcode.com/problems/clone-graph/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/133_Clone_Graph.py) | Hash and DFS or BFS |
| 136 | [Single Number](https://leetcode.com/problems/single-number/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/136_Single_Number.py) | 1. Hash or set, O(n) and O(n)<br>2. xor O(n) and O(1) |
| 137 | [Single Number II](https://leetcode.com/problems/single-number-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/137_Single_Number_II.py) | 1. ctypes 32 % 3 and &, O(n) and O(1)<br>2. ones, twos, threes as bitmask (e.g. ones represents ith bit had appeared once), O(n) and O(1) | 
| 138 | [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/138_Copy_List_with_Random_Pointer.py) | 1. Hash O(n) and O(n)<br>2.  Modify original structure: Original->Copy->Original, then node.next.random = node.random.next, O(n) and O(1) |
| 141 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/141_Linked_List_Cycle.py) | 1. Hash or set<br> 2. Two points (fast and slow)<br>3. Add a max and check if reach the max |
| 142 | [Linked List Cycle II](https://discuss.leetcode.com/topic/2975/o-n-solution-by-using-two-pointers-without-change-anything) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/142_Linked_List_Cycle_II.py) | Two points, a+b=nr |
| 143 | [Reorder List](https://leetcode.com/problems/reorder-list/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/143_Reorder_List.py) | 1. List as index to rebuild relation, O(n) and O(n)<br>2. Two points, O(n) and O(1) |
| 144 | [Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/144_Binary_Tree_Preorder_Traversal.py) | 1. Recursion, O(n) and O(n)<br>2. Stack, O(n) and O(n) |
| 145 | [Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/145_Binary_Tree_Postorder_Traversal.py) | 1. Recursion, O(n) and O(n)<br>2. Stack and queue (insert 0), O(n) and O(n)<br>3. Stack and isinstance(curr, TreeNode), O(n) and O(n) |
| 146 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/146_LRU_Cache.py) | 1. Queue and dict<br>2. OrderedDict |
| 150 | [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/150_Evaluate_Reverse_Polish_Notation.py) | Stack |
| 151 | [Reverse Words in a String](https://discuss.leetcode.com/category/159/reverse-words-in-a-string) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/151_Reverse_Words_in_a_String.py)| 1. Python split by space <br>2. Reverse all and reverse words |
| 152 | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/152_Maximum_Product_Subarray.py) | DP, f(k) = max(f(k-1) * A[k], A[k], g(k-1) * A[k]), g(k) = min(g(k-1) * A[k], A[k], f(k-1) * A[k]), O(n) and O(1) |
| 153 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/153_Find_Minimum_in_Rotated_Sorted_Array.py) | Binary search with conditions, A[l] > A[r] |
| 154 | [Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/154_Find_Minimum_in_Rotated_Sorted_Array_II.py) | Binary search with conditions, A[l] > A[r], A[l]=A[mid]=A[r] |
| 155 | [Min Stack](https://leetcode.com/problems/min-stack/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/155_Min_Stack.py) | Add another stack for min stack, maintance this stack when the main stack pop or push |
| 156 | [Binary Tree Upside Down](https://leetcode.com/problems/binary-tree-upside-down/) &hearts;| [Python](https://github.com/qiyuangong/leetcode/blob/master/python/156_Binary_Tree_Upside_Down.py) | p.left = parent.right, parent.right = p.right, p.right = parent, parent = p.left, p = left |
| 157 | [Read N Characters Given Read4](https://leetcode.com/problems/read-n-characters-given-read4/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/157_Read_N_Characters_Given_Read4.py) | Handle the edge case (the end) |
| 158 | [Read N Characters Given Read4 II - Call multiple times](https://leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/) &hearts;| [Python](https://github.com/qiyuangong/leetcode/blob/master/python/158_Read_N_Characters_Given_Read4_II_Call_multiple_times.py) | Store the pos and offset that is read by last read4 |
| 159 | [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/159_Longest_Substring_with_At_Most_Two_Distinct_Characters.py) | Maintain a sliding window that always satisfies such condition |
| 161 | [One Edit Distance](https://leetcode.com/problems/one-edit-distance/) &hearts;| [Python](https://github.com/qiyuangong/leetcode/blob/master/python/161_One_Edit_Distance.py) | 1. Check the different position and conditions<br>2. [Edit distance](https://leetcode.com/problems/edit-distance/)|
| 163 | [Missing Ranges](https://leetcode.com/problems/missing-ranges/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/163_Missing_Ranges.py) | Add -1 to lower for special case, then check if curr - prev >= 2|
| 166 | [Fraction to Recurring Decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/166_Fraction_to_Recurring_Decimal.py) | % and Hash to find duplicate |
| 167 | [Two Sum II - Input array is sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/167_Two_Sum_II_Input_array_is_sorted.py) | Two points O(n) and O(1) |
| 170 | [Two Sum III - Data structure design](https://leetcode.com/problems/two-sum-iii-data-structure-design/) 
&hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/170_Two_Sum_III-Data_structure_design.py) | 1. Hash, O(1) for add, O(n) for find, O(n) space<br>2. sorted list, O(logn) for add, O(n) for find, O(n) space<br> 3. Sort before find, O(1) for add, O(nlogn) for find, O(n) space|
| 186 | [Reverse Words in a String II](https://leetcode.com/problems/reverse-words-in-a-string-ii/) &hearts;| [Python](https://github.com/qiyuangong/leetcode/blob/master/python/186_Reverse_Words_in_a_String_II.py) | Reverse all and reverse each words |
| 198 | [House Robber](https://leetcode.com/problems/house-robber/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/198_House_Robber.py) | f(k) = max(f(k – 2) + num[k], f(k – 1)), O(n) and O(1) |
| 200 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/200_Number_of_Islands.py) | 1. Quick union find, O(nlogn) and O(n^2)<br>2. BFS with marks, O(n^2) and O(1) |
| 206 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/206_Reverse_Linked_List.py) | 1. Stack, O(n) and O(n)<br>2. Traverse on prev and curr, then curr.next = prev, O(n) and O(1)<br>3. Recursion, O(n) and O(1) | 
| 213 | [House Robber II](https://leetcode.com/problems/house-robber-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/213_House_Robber_II.py) | f(k) = max(f(k – 2) + num[k], max(dp[0~ls-2],dp[1~ls-1], O(n) and O(1)|
| 217 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/217_Contains_Duplicate.py) | 1. Set and compare length<br>2. Sort and check i,i +1|
| 219 | [Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/219_Contains_Duplicate_II.py) | 1. Brute force<br> 2. Maintenance a set that contains previous k numbers, and check if curr in set |
| 220 | [Contains Duplicate III](https://leetcode.com/problems/contains-duplicate-iii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/220_Contains_Duplicate_III.py) | 1. Sort and binary Search <br>2. Bucket sort |
| 221 | [Maximal Square](https://leetcode.com/problems/maximal-square/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/221_Maximal_Square.py) | 1. Brute force<br> 2. dp[i][j] = min(dp[i-1][j], dp[i-1][j-1], dp[i][j-1]) + 1, O(mn) and O(mn)<br>3. dp[j] = min([j], dp[j-1], prev) + 1, O(mn) and O(n)|
| 228 | [Summary Ranges](https://leetcode.com/problems/summary-ranges/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/228_Summary_Ranges.py) | Detect start and jump, O(n) and O(1) |
| 243 | [Shortest Word Distance](https://leetcode.com/problems/shortest-word-distance/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/243_Shortest_Word_Distance.py) | Update index1 and index2, and check distance, O(n) and O(1) |
| 246 | [Strobogrammatic Number](https://leetcode.com/problems/strobogrammatic-number/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/246_Strobogrammatic_Number.py) | Hash table and reverse string, O(n) and O(n) |
| 252 | [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/252_Meeting_Rooms.py) | 1. Sort and compare intervals[i].end with intervals[i+1], O(nlogn) and O(1)<br>2. Sort and check intervals when count >= 2, O(nlogn) and O(n) |
| 259 | [3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/259_3Sum_Smaller.py) | 1. Reduce to two sum smaller, then binary search, O(n^2lgn) and O(1)<br>2. Reduce to two sum smaller, then two points, O(n^2) and O(1)|
| 266 | [Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/266_Palindrome_Permutation.py) | Compute frequency, check number of odd occurrences <= 1 then palindrome, O(n) and O(n)|
| 267 | [Palindrome Permutation II](https://leetcode.com/problems/palindrome-permutation-ii/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/267_Palindrome_Permutation_II.py) | Check palindrome then generate half with [Permutations II](https://leetcode.com/problems/permutations-ii/), O(n^2) and O(n^2) |
| 270 | [Closest Binary Search Tree Value](https://leetcode.com/problems/closest-binary-search-tree-value/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/270_Closest_Binary_Search_Tree_Value.py) | 1. Recursively brute force, O(n) and O(n)<br>2. Recursively compare root result with current kid's result (left or right), O(logn) and O(logn)<br>3. Iteratively compare root result with current kid's result (left or right), O(logn) and O(logn) |
| 274 | [H-Index](https://leetcode.com/problems/h-index/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/274_H-Index.py) | [Background](https://en.wikipedia.org/wiki/H-index)<br>1. Sort and check number of papers greater than h, O(nlogn) and O(1)<br>2. Counting sort, O(n) and O(n) |
| 276 | [Paint Fence](https://leetcode.com/problems/paint-fence/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/276_Paint_Fence.py) | ways[i>2] = (ways[i-1] + ways[i-2]) * (k - 1), O(n) and O(1) |
| 280 | [Wiggle Sort](https://leetcode.com/problems/wiggle-sort/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/280_Wiggle_Sort.py) &hearts; | 1. Sort and insert (n - 1) / 2 from tail to correct position, O(nlogn) and O(1)<br>2. Sort and swap(i, i + 1) from 1 to n - 1, O(nlogn)<br>3. Iteratively check order and reverse order, if not satisfied, then swap i with i + 1, O(n) |
| 286 | [Walls and Gates](https://leetcode.com/problems/walls-and-gates/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/286_Walls_and_Gates.py) | BFS with queue, O(mn) and O(mn) |
| 288 | [Unique Word Abbreviation](https://leetcode.com/problems/unique-word-abbreviation/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/288_Unique_Word_Abbreviation.py) | hash |
| 296 | [Best Meeting Point](https://leetcode.com/problems/best-meeting-point/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/296_Best_Meeting_Point.py) | Think hard about Manhattan Distance in 1D case. Sort and find mean, O(mnlogmn) and O(1) |
| 298 | [Binary Tree Longest Consecutive Sequence](https://leetcode.com/problems/binary-tree-longest-consecutive-sequence/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/298_Binary_Tree_Longest_Consecutive_Sequence.py) | Bottom-up or top-down recursion, O(n) and O(n) |
| 305 | [Number of Islands II](https://leetcode.com/problems/number-of-islands-ii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/305_Number_of_Islands_II.py) | Quick union find with weights, O(nlogn) and O(n) |
| 322 | [Coin Change](https://leetcode.com/problems/coin-change/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/322_Coin_Change.py) | Bottom-up or top-down DP, dp[n] = min(dp[n], dp[n - v_i]), where v_i is the coin, O(amount * n) and O(amount) |
| 337 | [House Robber III](https://leetcode.com/problems/house-robber-iii/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/337_House_Robber_III.py) | 1. Recursion with hash map, O(n) and O(n)<br>2. Recursion on two steps, O(n) and O(1) |
| 339 | [Nested List Weight Sum](https://leetcode.com/problems/nested-list-weight-sum/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/339_Nested_List_Weight_Sum.py) | Depth-first recursion |
| 340 | [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/340_Longest_Substring_with_At_Most_K_Distinct_Characters.py) | Maintain a sliding window with at most k distinct characters and a count for this window. Note that the start position need a loop to update.|
| 346 | [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) &hearts; | 
[Python](https://github.com/qiyuangong/leetcode/blob/master/python/346_Moving_Average_from_Data_Stream.py) | fix-sized queue or dequeue, O(1) and O(n) |
| 351 | [Android Unlock Patterns](https://leetcode.com/problems/android-unlock-patterns/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/351_Android_Unlock_Patterns.py) | Backtracking, O(n!) and O(n) |
| 368 | [Largest Divisible Subset](https://leetcode.com/problems/largest-divisible-subset/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/368_Largest_Divisible_Subset.py) | Sort and generate x subset with previous results, O(n^2) and O(n^2) |
| 370 | [Range Addition](https://leetcode.com/problems/range-addition/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/370_Range_Addition.py) | Interval problem with cumulative sums, O(n + k) and O(n) |
| 384 | [Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/384_Shuffle_an_Array.py) | Fisher–Yates shuffle, O(n) and O(n) |
| 388 | [Longest Absolute File Path](https://leetcode.com/problems/longest-absolute-file-path/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/388_Longest_Absolute_File_Path.py) | Store last length and rindex, O(n) and O(n) |
| 408 | [Valid Word Abbreviation](https://leetcode.com/problems/valid-word-abbreviation/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/408_Valid_Word_Abbreviation.py) | Go over abbr and word, O(n) and O(1) |
| 416 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/416_Partition_Equal_Subset_Sum.py) | DP, Check if sum of some elements can be half of total sum, O(total_sum / 2 * n) and O(total_sum / 2) |
| 421 | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/421_Maximum_XOR_of_Two_Numbers_in_an_Array.py) | Check 0~32 prefix, check if there is x y in prefixes, where x ^ y = answer ^ 1, O(32n) and O(n) |
| 422 | [Valid Word Square](https://leetcode.com/problems/valid-word-square/) &hearts; | [Python](https://github.com/qiyuangong/leetcode/blob/master/python/422_Valid_Word_Square.py) | Compare row with column, O(n^2) |

| # | To Understand |
|---| ----- |
| 4 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) |
