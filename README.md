# Perfect State Transfer on GCD-Graphs

This Git repository contains the code we developed to generate data and conduct experiments on perfect state transfer in GCD-graphs over a **local** Frobenius ring, as discussed in our paper:

**[1]** Tung T. Nguyen, Nguyen Duy Tan, *Perfect State Transfer on GCD-Graphs over a Finite Frobenius Ring, I: General Theory and Results for Local Rings* (preprint, 2025).

There are two files, each dealing with local Frobenius rings of a different type. We refer the readers to the individual files for precise descriptions of their functionality:

1. A file on perfect state transfer (PST) in GCD-graphs over quotients of polynomial rings.
   
2. A file on PST in GCD-graphs over quotients of the ring $\mathbb{Z}/n[x]$.

The reason we have two different files is that in the case of polynomial rings, we can't figure out a direct way to iterate over a ring even if it is finite. We have to use an indirect method, via the theory of Gröbner bases, to deal with this (thanks to the help of Dr. Ricardo Buring). We are grateful for his kind help over the years.

## Description

Our code utilizes the SageMath 9.4 kernel and the Python library NetworkX. 

## License

This project is licensed under the MIT License.
