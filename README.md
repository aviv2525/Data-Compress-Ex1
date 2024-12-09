Background:
One of the prominent drawbacks of Huffman coding is the inability to slightly modify the original file to improve compression. The new Huffman method we will create will be able to do this.

*The Exercise*
On the website:
https://u.cs.biu.ac.il/~wisemay/compression/

There are several compression programs in the C language. Copy the library. To create a Huffman coding program, compile the following files:
Note that the files with the .h extension are also essential for compilation.
To run the program that decodes Huffman code, replace the file main-c.c with main-e.c.


Instructions:
Find the ten most frequent characters in the file.

For any other character (that is not among the ten most frequent), replace it with the frequent character whose ASCII value is closest to it (if there are two characters equally close, one above and one below, prefer the one below).

Build a Huffman tree for only the ten most frequent characters and compress the file using the tree you built.

Translation to English:
Background:
One of the prominent drawbacks of Huffman coding is the inability to slightly modify the original file to improve compression. The new Huffman method we will create will be able to do this.

The Exercise:
On the website:
https://u.cs.biu.ac.il/~wisemay/compression/

There are several compression programs in the C language. Copy the library. To create a Huffman coding program, compile the following files:

huff.c
bitio.c
main-c.c
errhand.c
Note that the files with the .h extension are also essential for compilation.

To run the program that decodes Huffman code, replace the file main-c.c with main-e.c.

Instructions:
Find the ten most frequent characters in the file.
For any other character (that is not among the ten most frequent), replace it with the frequent character whose ASCII value is closest to it (if there are two characters equally close, one above and one below, prefer the one below).
Build a Huffman tree for only the ten most frequent characters and compress the file using the tree you built.

Note:
As an inevitable result of this modification, the decoded file will contain only the ten most frequent characters, and the decoded file will differ from the original file.
