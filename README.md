# Fast-kNN

Author: CS1807 Chenhui Mo.

the implementation for Machine Learning course of Huazhong University of Science and Technology and learning GEMM.

All in C++ and use vectorizing instructions for the best performance.

# Speed: 

test environment: i7-8750H, msvc19, release x64, mnist dataset.

- naive implementation: 81ms per photo.
- optimize cache but not use avx: 21ms per photo.
- all optimization: 13ms per photo. 
