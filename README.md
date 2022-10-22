# Word-composition-problem
A concatenated word is defined as a string that is comprised entirely of at least two shorter words in the given array.
This problem can be solved by using trie and hashset.
 Trie is a sorted tree-based data-structure that stores the set of strings. It has the number of pointers equal to the number of characters of the alphabet in each node. It can search a word in the dictionary with the help of the word's prefix. For example, if we assume that all strings are formed from the letters 'a' to 'z' in the English alphabet, each trie node can have a maximum of 26 points
Trie is also known as the digital tree or prefix tree. The position of a node in the Trie determines the key with which that node is connected.
 In this first we have to search concat word fuction read the text and constructed trie from input text given.
 Then we have to find the longest string insise the loop by making an function.
 Then prefixChecker function checks the string whether it was constructed using small words found in the Trie.
  if greater than 1 increment the index and after loop ends return true If not there are two cases:
  (1) If the index is equal to 1 that means concat word is not found in the Trie and return false 
  (2) Else it cuts the previous part and recursively call prefixChecker function again.
