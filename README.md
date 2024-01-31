# SNlayout
Plots for signed networks with weight using the circlize libary in R

The circlize-tes.r script contains the example provided by the self library in their home page.

https://jokergoo.github.io/circlize_book/book/introduction.html


The WDSN_plot .r and .ipynb files are the examples of plotting the adjacency matrix of a signed, directed and weighted network. The idea is to show the intensity of the influence by the width of the edge in the source and the sign of it with the color of the bound.

In this algoritm, each node expands in a circular layout an arc length proportional to its total influence (the sum of the absolute values of the corresponding row of the adj. matrix). The idea is that the arc length of a node is enterely covered by the width of the edges departing from it.
