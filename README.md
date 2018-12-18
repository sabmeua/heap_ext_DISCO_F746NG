# heap_ext_DISCO_F746NG

# What is this

This is a library for mbed for using SDRAM instead of SRAM as heap region with DISCO_F746NG.

It's effective only if the target is DISCO_F746NG. And currently, The compile switch is set so that it works only when the tool chain is GCC_ARM.

It's under investigation how to implement for the other toolchains.


# How to use

In the mbed project,

```
mbed add https://github.com/sabmeua/heap_ext_DISCO_F746NG.git
```

# Sample project

This is a sample mbed project that allocates memory using this library.

https://github.com/sabmeua/DISCO-F746NG_SDRAM_test

