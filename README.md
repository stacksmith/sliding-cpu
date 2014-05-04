sliding-cpu
===========

sliding-cpu is an initiative to create a cpu described in http://www.fpgarelated.com/showarticle/44.php
It has the following characteristics:

- 8-bit opcodes;
- decoded via a sliding table of 256 entries;
- base of the table is related to instruction address;
- table contains 256 target addresses or microcode entries
- execution is theaded (see Forth etc).

A software system is availabe for evaluating and playing with this technology a this repository:

