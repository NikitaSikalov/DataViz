# Algorithms of data visualization

## Content

1. [Tree visualization](##Tree_visualization)
2. [DAG visualization](##DAG_visualization)
## Tree_visualization

You can find out code and examples in colab notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaSikalov/DataViz/blob/main/TreeViz.ipynb)

We use `Layered-Tree-Draw` algorithm to visualize our trees. You can see its pseudocode on the sreenshot below.

![Algorighm](./assets/layered-tree-draw.png)

This screenshot was taken from this [paper](https://www.csd.uoc.gr/~hy583/papers/ch8.pdf) where you can find some more interesting algorithms of tree visualization.

In our implementation we use [matplotlib](https://matplotlib.org/) for visualization and also [networkx](https://networkx.org/) lib for loading and parsing graphs in [GraphML](https://en.wikipedia.org/wiki/GraphML) format.

## DAG_visualization

You can find out code and examples in colab notebook.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NikitaSikalov/DataViz/blob/main/DagVis.ipynb)

There are two algorithms implemented for DAG visualization:

* _Coffman-Graham algorithm_ for DAG visualization with `max_width`
* Algorithm for minimizing dummy vertecies

Also algorithm for minimizing crossings count executes after layout algorithm for minimizing dummy vertecies.
