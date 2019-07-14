# Assembler
implement two pass Assembler through two phases ..

The First Phase (Pass1):  Assign addresses to all statements in the program
                          Save the values assigned to all
                          labels for use in Pass 2
                          Perform some processing of assembler directives
                          
The Second Phase (Pass2): Assemble instructions
                          Generate data values defined by BYTE, WORD
                          Perform processing of assembler directives not done in Pass 1
                          Write the object program and the assembly listing
