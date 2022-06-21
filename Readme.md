Longest Common Prefix Using Trie

In this approach the following steps been performed:
1) Insert all words one by one in the trie.After inserting we perform a walk on the trie.
2)In this walk, go deeper until we find a node having more than 1 children(branching occurs) or 0 children.
3)The first node where branching occurs,above that all characters is the longest common prefix string.

Time Complexity: 
Inserting all the words in the trie takes O(MN) time and performing a walk on the trie takes O(M) time.
where-
    N-Number of strings
    M-Length of the longest string

