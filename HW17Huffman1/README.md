# Build Huffman Code Book from Post-Order Description

Learning Goals
==============

* Understand Huffman Compression

* Understand the description of the compression tree using post-order description

Post-Order Description of Huffman Compress Tree
===============================================

The compression tree can be expressed by post-order traversal.  When a
leaf node is encountered, 1 is printed before printing the characer
stored in the node. When a non-leaf node is encountered, 0 is printed.
If the tree has `n` leaf nodes, the tree has `n-1` non-leaf nodes.
Thus, there are `n` 1 printed (not counting the characters) and `n-1`
0 printed.  A final 0 is added to indicate the end of the description.

![](huffman01.png)
