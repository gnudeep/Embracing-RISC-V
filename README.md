# ICTer2023 Workshop - Embracing-RISC-V 
<img src="https://riscv.org/wp-content/uploads/2020/06/riscv-color.svg" width="500" height="100">

In this workshiop participants will get an introduction to [RISC-V architecture](https://riscv.org/about/), hands-on tutorial to build a simple OS kernel, bootloader, and hardware interfacing.

In the hands-on tutorial we build a simple boot loader and boot [StarFive VisionFive2](https://www.starfivetech.com/en/site/boards) board. 

To follow this tutorial, participants need a Linux machine with a Internet connection.
* Perefered OS: Ubuntu 22.04 LTS 64 bit.
* Ubuntu packages
  * autoconf automake autotools-dev curl python3 python3-pip libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev ninja-build git cmake libglib2.0-dev
  * device-tree-compiler
  * u-boot-tools
* Machine or a laptop with a USB port.

To build binaries, we need to [setup the GNU tool chain](tool-chain-setup.md). 

You can try to build the [sample C program](https://github.com/gnudeep/hello-world-riscv.git) using this toolchain. 

[Spike RISC-V simulater](https://github.com/riscv-software-src/riscv-pk) helps to simulate the program on x86 Linux. 

Build the [example boot loader](https://github.com/gnudeep/SysResOS.git) using the RISC-V tool chain.

To test the build boot loader we need QEMU emulater with qemu-system-riscv64 capability.
