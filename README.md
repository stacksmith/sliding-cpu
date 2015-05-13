sliding-cpu
===========

sliding-cpu is an initiative to create a cpu described in http://www.fpgarelated.com/showarticle/44.php
It has the following characteristics:

- 8-bit tokens (maybe 9-bit; anyway, very small) fetched from instruction space (IRAM)
- decoded via a sliding window of 256 (512?) entries into a wider data space (DRAM, 16 or 32 bits);
- base of the window is related to instruction address;
- table contains target addresses, wide literals and microcode entries (tokens decoded to control bits)
- execution is threaded (as in Forth etc).

A software system is availabe for evaluating and playing with this technology a this repository:

https://github.com/stacksmith/FemtoForth


