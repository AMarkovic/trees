# trees

Check sample tree at: 
- [flat](http://htmlpreview.github.io/?https://github.com/epogrebnyak/trees/blob/master/index_flat.htm)
- [round](http://htmlpreview.github.io/?https://github.com/epogrebnyak/trees/blob/master/index_round.htm)

Issues:
- saving [png file](http://htmlpreview.github.io/?https://github.com/epogrebnyak/trees/blob/master/to_png/index.htm)
- Russian letters and spaces in names
- mixed sports

Data Communication Instructions
-------------------------------


| MSA           | description                   | Altivec       |
| :------------ | :---------------------------: | ------------: |
| ILVL.B        | interleave left (byte)        | VMRGHB        |
| ILVL.H        | interleave left (halfword)    | VMRGHH        |
| ILVL.W        | interleave left (word)        | VMRGHW        |
| ILVL.D        | interleave left (doubleword)  |  n/a          |
| ILVR.B        | interleave right (byte)       | VMRGLB        |
| ILVR.H        | interleave right (halfword)   | VMRGLH        |
| ILVR.W        | interleave right (word)       | VMRGLW        |
| ILVR.D        | interleave right (doubleword) |  n/a          |
| ILVEV.B       | interleave even (byte)        |  n/a          |
| ILVEV.H       | interleave even (halfword)    |  n/a          |
| ILVEV.W       | interleave even (word)        | VMRGEW        |
| ILVEV.D       | interleave even (doubleword)  |  n/a          |
| ILVOD.B       | interleave odd (byte)         |  n/a          |
| ILVOD.H       | interleave odd (halfword)     |  n/a          |
| ILVOD.W       | interleave odd (word)         | VMRGOW        |
| ILVOD.D       | interleave odd (doubleword)   |  n/a          |


Logical Instructions
--------------------


| MSA           | description                   | Altivec       |
| :------------ | :---------------------------: | ------------: |
| AND.V         | bitwise AND                   | VAND          |
| OR.V          | bitwise OR                    | VOR           |
| NOR.V         | bitwise NOR                   | VNOR          |
| XOR.V         | bitwise XOR                   | VXOR          |
|  n/a          | bitwise NAND                  | VNAND         |
|  n/a          | bitwise AND with complement   | VANDC         |
|  n/a          | bitwise OR with complement    | VORC          |
|  n/a          | bitwise equivalence           | VEQV          |


Parity Instructions
-------------------


| MSA           | description                   | Altivec       |
| :------------ | :---------------------------: | ------------: |
|  n/a          | parity byte word              | VPRTYW        |
|  n/a          | parity byte doubleword        | VPRTYD        |
|  n/a          | parity byte quadword          | VPRTYQ        |
