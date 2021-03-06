## TreeGraph Class: Python object to create instances of hierachical structures with the possibility to use different colored fonts in the same line of text

Python object created to add multicolored fonts to the labels of a [NetworkX](https://networkx.github.io/) graph. The `TreeGraph` class takes all the arguments to create a hierarchical tree graph, that can be oriented vertically or horizontally. The class includes methods to plot a tree with its nodes and edges (branches). It also has methods to get descendants and to calculate the product of a specific path in the tree.

Here's an example of a probability tree diagram:

![](https://github.com/jhmanchola/Learning-curve/blob/master/Problem-Solving/Probability-Tree-Diagram-With-Multicolor-Font-labels/newplot.png)


The main feature of this class is to allow the color coding of text, by letting the user to plot a line of text in a multicolor format:

![](https://github.com/jhmanchola/Learning-curve/blob/master/Problem-Solving/Probability-Tree-Diagram-With-Multicolor-Font-labels/multicolored_text.png)

This was not a possibility in NetworkX, thus the need for this solution.
