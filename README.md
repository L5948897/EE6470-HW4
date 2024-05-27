# ESL HW4

## Requirments

Linux system, SystemC, RISC_V VP

## HW4-1 Gaussian Blur Filter to RISC-V VP platform

Use Linux system and copy all the files in riscv-vp/vp/src/platform/ and riscv-vp/sw/ to the riscv-vp engine. For example:

```
cp -r hw4/riscv-vp/vp/src/platform/* $EE6470/riscv-vp/vp/src/platform
cp -r hw4/riscv-vp/sw/* $EE6470/riscv-vp/sw
```

Then go to riscv-vp/vp/build/ in the riscv-vp engine and type:

```
cmake ..
make install
```

Then go to riscv-vp/sw/basic-sobel/ and type:

```
make
make sim
```

After waiting for some time, the output file "out.bmp" will be created at this current folder.