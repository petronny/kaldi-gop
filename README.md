# kaldi-gop
This project computes GOP (Goodness of Pronunciation) bases on Kaldi.

This project has not been ready by far.

## How to build
1. Install kaldi and openblas-lapack  
You can fetch these 2 packages from [arch4edu](https://github.com/arch4edu/arch4edu)
1. Compile the binary
```
cd src/
mkdir build && cd build
cmake .. && make
```
1. Run the example
```
cd egs/gop-compute
./run.sh
```
