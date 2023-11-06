## How to setup RISC-V GNU Toolchain

Clone and build and install the [RISC-V GNU tool chain](https://github.com/riscv-collab/riscv-gnu-toolchain). 

**How to build the riscv-gnu-toolchain project**
```
./configure --prefix=/opt/riscv
make
or
make linux
```
Add `/opt/riscv` to the `PATH`.

You can alter the configuration according to the requirements. 
```
./configure --prefix=/opt/riscv-zifencei --host=riscv64-unknown-elf --with-arch=rv64imafdczifencei
make
```
