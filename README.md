# zc-test
1.Introduce

This repository provides the source code, elf files and build scripts for the executable tests of the zc extension.

2.Test progress

We have completed the executable test of most of the instructions of the zc extension, but the following instructions have not been completed.

·We don't know how to write code to generate cm.jt instructions for the zcmt sub-extended. When testing the cm.jalt instruction, we found that the base address of the JVT was not initialized to the csr register.

·Now, we only know that the cm.pop instruction is generated by calling an interrupt in the source code, but the qemu emulator does not support the mret instruction in use mode. We don't know how to write code to generate cm.popretz instructions for the zcmpe sub-extended.

