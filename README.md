# gem5_riscvTest
### gem5 stable code v21
gem5 for riscv ISA test
+ **usage**
```shell
mkdir gem5
tar zxvf gem5-refs_heads_stable.tar.gz -C ./gem5
cd gem5
scons build/RISCV/gem5.opt -j`nproc`
```
+ **run sh script**
```shell
./build/RISCV/gem5.opt ./configs/example/se.py -c ./test/<testprogram> --cpu-type O3CPU --caches --mem-type DDR3_1600_8x8 --mem-size 2GB
```
> More info to visit gem5.org please 
