# SDRAM Controller and SDRAM in Caravel User Project
## Run User Project Memory Enabled counter_la Testbench
Run iverilog simulation
```sh
~/Desktop/soclab-sdram/testbench/counter_la_mm$
source run_clean
source run_sim
```

Validate the `Call function adder() in User Project BRAM (mprjram, 0x38000000) return value passed, 0x2233` is printed
```
Reading counter_la.hex
counter_la.hex loaded into memory
Memory 5 bytes = 0x6f 0x00 0x00 0x0b 0x13
VCD info: dumpfile counter_la.vcd opened for output.
LA Test 1 started
counter_la_mm_tb.uut.mprj.mprj.user_bram : at time           4896263000 ERROR: Bank is not Activated for Read
Call function adder() in User Project BRAM (mprjram, 0x38000000) return value passed, 0x2233
LA Test 2 passed
```
# extra_labD
