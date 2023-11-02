## How to setup RISC-V GNU Toolchain

Clone and build and install the [RISC-V GNU tool chain](https://github.com/riscv-collab/riscv-gnu-toolchain). 

**How to build the riscv-gnu-toolchain project**
```bash
./configure --prefix=/opt/riscv
make
```
Add `/opt/riscv` to the `PATH`.
