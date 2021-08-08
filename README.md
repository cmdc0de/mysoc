# Status
Very early brain storming.  My goal is to design a CPU, Communication BUS, RAM and Storage.
I'll start by using an FPGA, write the compiler for assembler ensure all works, then make the application from either MOSFETs or Logic Gates.

# mysoc
Creating my own soc, staring with an FPGA then hardware


# CPU instructions:
| ID | Name | PARAMS         | Description   |
|----|------|----------------|---------------|
| 0  | NOP  | NONE           | do nothing    | 
| 1  | LR   | REG, VAL       | Load Register: REG A = 0x0, REG B = 0x1, INSTRUCTION REG = 0XFF | 
| 2  | ADD  | REG1, REG2, OUT| ADD REG1 into REG 2 and put result in OUT REG |
| 3  | MUL  | REG1, REG2, OUT| MUL REG1 by REG 2 and put result in OUT REG |
| 4  | SUB  |                |                                             |
| 5  | DIV  |                |                                             |



# RAM

256K

# Storage

1 MB
