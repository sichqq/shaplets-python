# shaplets
work in progress

Python implementation of the [Learning Time-Series Shapelets method](http://www.ismll.uni-hildesheim.de/pub/pdfs/grabocka2014e-kdd.pdf). 

This implementation view the model as a layered network, where each layer implement a forward and backword method. This abstraction will make it easy to port the implementation to a framework like Torch or Tensorflow.
