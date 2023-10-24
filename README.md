# Impledge-assignment

Language :- c++

Time complexity :- O(n)      iterating over every word in file.

Space complexity :- o(u)     store only unique words.

1. This program uses a trie structure to store the words from the input file, specified during code.
2. A major thing done to minimize space complexity was to store unique words in trie from the file.
3. So space complexity is O(u) where u is unique characters only.
4. The program iterates over the words in trie and checks to see if each word can be made by combining two or more shorter words.
5. If a word is made from a shorter word, then it is a compound word.
6. The program keeps track of the longest compound word it found.
7. It then prints the longest compound word in the console 
