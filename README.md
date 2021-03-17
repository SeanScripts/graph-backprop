# graph-backprop

Simple implementation of network backpropagation on a graph. This allows for arbitrary neural network architectures defined by a graph structure, rather than the usual layered structure (though of course the layered structure is a simple case of this). This includes any kind of structure with loops, like recurrent neural networks, as well as topologies which cannot be created in the existing frameworks. Uses numpy, with the backprop coded from scratch in an efficient matrix-oriented way.
