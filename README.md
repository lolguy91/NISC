# NISC Specs:

`8` registers: `A-H`

Instruction format:
- bit `0`: Data input
- bit `1`: ALU enable
- bits `2-10`: Register input enable lines
- bit `11`: input bus A -> out bus
- bit `12`: input bus B -> out bus
- bit `13`: output address(note: the load system is not refined yet, do not use)
- bits `14-16`: input bus A register selector
- bits `17-19`: input bus B register selector
- bits `20-22`: ALU operation selector
- bits `23-31`: Yet to be assigned

ALU operations:
0. Add
1. Subtract
2. AND
3. OR
4. XOR
5. NOT
6. Shift left
7. Unassigned
