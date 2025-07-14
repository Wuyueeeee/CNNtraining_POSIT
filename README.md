## 1. Setup
### Clone the repositories:
```bash
$ git clone https://github.com/Wuyueeeee/CNNtraining_POSIT.git

$ cd CNNtraining_POSIT
$ git clone https://github.com/hpc-ulisboa/posit-neuralnet.git

$ cd posit-neuralnet/include
$ git clone https://github.com/gonced8/universal.git

Download appropriate PyTorch for C++ (LibTorch) and unzip also inside include folder
https://pytorch.org/get-started/locally/

$ mkdir build; cd build
$ cmake .. -DCMAKE_PREFIX_PATH="/path/to/libtorch"
$ make
```
## 2. Test
```bash
$ ./train_float
$ ./train_posit
```
