C++ Opening MNIST Handwriting Digits data-set
======

Based on the [Dariush's comment](http://stackoverflow.com/questions/8286668/how-to-read-mnist-data-in-c)

A simple complete C++ script to read the [MNIST](http://yann.lecun.com/exdb/mnist/) data-set.



Just Copy + Paste the main.cpp, and in the main() specify your own location of the files: [your path].

To open the value of the image just do:
 image -> dataset[number of the image to open][pixel from 0 to 784 = 28(rows)*28(cols)]
 label -> +label[number of the image to open]  // " Yes with the '+' "
