# My Personal Codebook
> This codebook contains the implementation of various algorithms and data structures in the form of classes. To use these, simply copy and paste the whole class and use the implemented methods to get the job done!

## Contents

- <font size="3"> [Suffix Array](Suffix_Array.txt) </font>
>> **Time Complexity:** $O(n\log{n})$<br />
>> **Space Complexity:** $O(n)$

- <font size="3"> [Union Find](Union_Find.txt) </font>
>> **Time Complexity:** $O(n\log{n})$<br />
>> **Space Complexity:**  $O(n)$

- <font size="3">[Segment Tree For Minimum (Point Update)](Segment_Tree_Point.txt) </font>
>> **Time Complexity (Building):**  $O(n)$ <br />
>> **Time Complexity (Query):** $O(\log{n})$ <br />
>> **Time Complexity (assign):** $O(\log{n})$ <br />
>> **Time Complexity (increment):** $O(\log{n})$ <br />
>> **Space Complexity:**  $O(n)$

- <font size="3">[Segment Tree For Minimum (Mass Update)](Segment_Tree_Mass.txt) </font>
>> **Time Complexity (Building):**  $O(n)$ <br />
>> **Time Complexity (Query):** $O(\log{n})$ <br />
>> **Time Complexity (Update):** $O(n\log{n})$ <br />
>> **Space Complexity:**  $O(n)$

- <font size="3">[AVL Tree (Generic)](AVL_Tree.txt) </font>
>> **Time Complexity (insert):** $O(\log{n})$ <br />
>> **Time Complexity (remove):** $O(\log{n})$ <br />
>> **Time Complexity (kthLargestElement):** $O(\log{n})$ <br />
>> **Time Complexity (countOfGreater):** $O(\log{n})$ <br />
>> **Space Complexity:**  $O(n)$

- <font size="3">[Window Manager](Window_Manager.txt) </font>
>> **Time Complexity (push):** $O(1)$ [Average] <br />
>> **Time Complexity (pop):** $O(1)$ [Average] <br />
>> **Time Complexity (empty):** $O(1)$ <br />
>> **Space Complexity:**  $O(n)$

- <font size="3">[Digit DP BoilerPlate](Digit_DP_BoilerPlate.txt) </font>
>> **Time Complexity:** Depends On The Specific Question <br />
>> **Space Complexity:** Depends On The Specific Question

- <font size="3">[Binary Lifter](Binary_Lifter.txt) </font>
>> **Time Complexity (build):** $O(n\log{n})$ <br />
>> **Time Complexity (getKthAncestor):** $O(\log{n})$ <br />
>> **Time Complexity (getLCA):** $O(\log{n})$ <br />
>> **Space Complexity:** $O(n\log{n})$****

- <font size="3">[Trie Numeric](Trie_Numeric.txt) </font>
>> **Time Complexity (insert):** $O(BITS)$ <br />
>> **Time Complexity (remove):** $O(BITS)$ <br />
>> **Time Complexity (contain):** $O(BITS)$ <br />
>> **Time Complexity (findPairForMaxXor):** $O(BITS)$ <br />
>> **Space Complexity:** O($2^{BITS}$) <br />
>> `[Here BITS is the maximum number of bits in the binary representation of the inserted numbers]`

- <font size="3">[KMP Pattern Matching](KMP.txt) </font>
>> **Time Complexity (build):** $O(n)$ <br />
>> **Time Complexity (getMatches):** $O(n + m)$ <br />
>> **Space Complexity:** $O(n)$ <br />
>> `[Here 'n' is pattern length and 'm' is text length]`

- <font size="3">[Aho Corasick Trie](Aho_Corasick_Trie.txt) </font>
>> **Time Complexity (insert):** $O(n)$ <br />
>> **Time Complexity (finalizeTrie):** $O(mk)$ <br />
>> **Time Complexity (resetIterator):** $O(1)$ <br />
>> **Time Complexity (proceed):** $O(1)$ <br />
>> **Time Complexity (getSuffixes):** $O(\sqrt{n})$ <br />
>> **Space Complexity:** $O(lk)$ <br />
>> `[Here 'n' is length of string to be inserted, 'm' is sum of all lengths of string that is to be inserted, 'k' is the size of the alphabet, 'l' is the maximum number of children nodes]`