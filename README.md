This repo is my undergrad research project report, 
on designing efficient data structures by leveraging memory level parallelism,
a CPU hardware feature available on most of the modern CPUs manufactured after 2000.
[pdf here](https://github.com/sillycross/efficient-mlp/blob/master/main.pdf)

We present 3 data structures that achieves superior performance via the clever use of memory level parallelism:
* A lock-free skiplist iterator (std::set::iterator)
* A priority queue (std::priority_queue)
* An ordered index (std::set)

Those data structures support identical APIs as their traditional counterparts (in the parentheses).

The implementation of our ordered index can be found [here](https://github.com/sillycross/mlpds).
