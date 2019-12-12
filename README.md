# ISA-Mnemonic-to-Binary-Simulator
| Opcode | Key |                       Summary                        |       Example         |
| ------ | ---- | --------------------------------------------------- | --------------------- |
|  PUT   |  0011 |Input an integer into a register                      |PUT 1 R1               |
|  SUM   |  0101 |Add the values into the registers and stored into the desired register  |SUM R1 R2 R3           |
|  OUT   |  1111 | Outputs the value of the desired register            |OUT R3                 |
| ARRAY  |  1010 |Make an array                                         |ARRAY 5 A1             |
| CLEAR   | 0000 |Clear all registers                                   |CLEAR                  |
| SIZE    | 1000 |Allows user to input size of an array                 |SIZE 5                 |
| QOV     | 1100 |Input integers for actual registers of an array       |QOV R1 R2 R3 R4 R5 R6  |
| DIMSUM  | 1110 |Displays the sum of an array                          |DIMSUM R6              |
| FNDNR   | 0001 |Checks to see if a certain integer is inside an array |FNDNR 5 R6             |
| SUBT    | 1011 |Subtracts two registers and stores it into a register |SUBT R5 R4 R3          |
  
