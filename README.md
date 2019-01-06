This repo is my undergrad research project report, 
on designing efficient data structures by leveraging memory level parallelism,
a CPU hardware feature available on most of the modern CPUs manufactured after 2000.
[pdf here](https://github.com/sillycross/efficient-mlp/blob/master/main.pdf)

In this report, we demostrated that by leveraging memory level parallelism, 
one can design data structures that is up to 4x faster than the current state-of-the-art.

We present two novel "MLP-grounded" data structures:
* A lock-free skiplist iterator
* An ordered index

Those data structures support identical APIs as their traditional counterparts, 
specifically, std::set::iterator and std::set.

The implementation of our ordered index can be found [here](https://github.com/sillycross/mlpds).

