# kaldi-gop
This project computes GOP (Goodness of Pronunciation) bases on Kaldi.

__This fork is for Archlinux only.__

## How to build
* Install kaldi and openblas-lapack  
PS. You can fetch these 2 packages from [arch4edu](https://github.com/arch4edu/arch4edu)
* Compile the binary
```
cd src/
mkdir build && cd build
cmake .. && make
```
* Run the example
```
cd egs/gop-compute
./run.sh
```
