Trie-DataStructure
==================
I used many common data structure like Array,LinkedList,Stack,Queue and Binary trees to solve my problems now i am trying to learn the trie data structure. I read many places that it is efficent data structure to store strings. Motivation for me learning this is that in binary tree we can do a operation in 0(log n base 2 ) as if we have a ternary tree we can do most of the operations in O(log n base 3) so same way as tree goes wider operation time goes down.
           I am tring to implement trie to store strings one observation every one can notice is that it is memory optimaztion also with cpu time optimaztion

for ex.
  I have 7 words: like,lion,last,some,same,king,knife 
  if i store them in simple string than i required like 4+4+4+4+4+4+5 chars space but if i store them in trie than structure should b like this
                                                  root
  
                                             l             s           k
                                          i     a        o    a     i     n
                                        k   o   s        m    m     n     i
                                        e   n   t        e    e     g     f
                                                                          e
so it is required less number of char and it takes less look up time also .

I am going to first try to implement trie than will do many exercise upon the built tree.

step: 1 I started with simple node class that have two class fields one holds the char of node(ex. 'a','b') and other one holds the list of childrens . In the node class also implemented print,add,count fun for basic utils of node class.

step:2 I created another class trie that holds trie structure with node root. I started with one string.Adding one string is a very simple job just iterate through string and add char as child . But adding second string is a little complex
