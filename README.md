C++ Opening MNIST Handwriting Digits data-set
======

Based on the [Dariush's comment](http://stackoverflow.com/questions/8286668/how-to-read-mnist-data-in-c) in StackOverflow.

A simple complete C++ script to read the [MNIST](http://yann.lecun.com/exdb/mnist/) data-set.

How To
------

Just Copy + Paste the [main.cpp](https://github.com/Cartucho/Cpp-Opening-MNIST-Handwriting-Digits-data-set/blob/master/main.cpp), and in the main() specify your own location of the files: [your path].

To open the value of the image just do:
 image -> dataset[number of the image to open][pixel from 0 to 784 = 28(rows)*28(cols)]
 label -> +label[number of the image to open]  // " Yes with the '+' "
 
Just run the script with your path's
------

And you should see a random example opening: (converted to binary just to show the example)

![alt text](https://github.com/Cartucho/Cpp-Opening-MNIST-Handwriting-Digits-data-set/blob/master/example.png)
