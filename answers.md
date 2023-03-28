# CMPS 2200 Recitation 6
## Answers

**Name:**___Sam DeMarinis & Zoe Oboler________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File        | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt         | 1340                | 826            | 0.61
alice29.txt    | 1039367             | 676374         | 0.65
asyoulik.txt   | 876253              | 606448         | 0.69
grammar.lsp    | 26047               | 17356          | 0.66
fields.c       | 78050               | 56206          | 0.72

We see that there is consistently less cost when doing Huffman Coding as opposed to Fixed-Length Coding. The Huffman Coding cost for each file seems to be around 60-70% of its Fixed-Length Coding cost. Additionally, although grammar.lsp is an outlier we see that, genereally, as the length of the document increases so does the ratio between fixed length and Huffman encoding.


- **e.**

The expected cost of a Huffman encoding for the document is nlogn. A Huffman tree based on a document where each character has the same frequency is balanced, and so the number of leaves will be n. It is consistent across documents.
