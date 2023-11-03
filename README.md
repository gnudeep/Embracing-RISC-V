# ICTer2023 Workshop - Embracing-RISC-V

In this workshiop participants will get an introduction to RISC-V architecture, hands-on tutorial to build a simple OS kernel, bootloader, and hardware interfacing.

In the hands-on tutorial we build a simple boot loader and boot [StarFive VisionFive2](https://www.starfivetech.com/en/site/boards) board. 

To follow this tutorial, participants need a Linux machine with a Internet connection.
* Perefered OS: Ubuntu LTS 64bit.
* Machine or a laption with a USB port.

To build binaries, we need to [setup the GNU tool chain](tool-chain-setup.md). 

You can try to build the [sample C program](https://github.com/gnudeep/hello-world-riscv.git) using this toolchain. 

[Spike RISC-V simulater](https://github.com/riscv-software-src/riscv-pk) helps to simulate the program on x86 Linux. 

Build the [example boot loader](https://github.com/gnudeep/SysResOS.git) using the RISC-V tool chain.

To test the build boot loader we need QEMU emulater with qemu-system-riscv64 capability.




