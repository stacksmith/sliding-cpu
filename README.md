sliding-cpu
===========

sliding-cpu is an initiative to create a cpu described in http://www.fpgarelated.com/showarticle/44.php
It has the following characteristics:

- 8-bit opcodes (maybe 9-bit; anyway, very small)
- decoded via a sliding table of 256 (or 512) entries;
- base of the table is related to instruction address;
- table contains 256 target addresses or microcode entries
- execution is threaded (as in Forth etc).

A software system is availabe for evaluating and playing with this technology a this repository:

https://github.com/stacksmith/FemtoForth


