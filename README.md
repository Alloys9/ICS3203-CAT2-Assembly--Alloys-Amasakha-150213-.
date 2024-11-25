# ICS3203 CAT 2 - Assembly Programs
### **Repository Overview**
This repository contains solutions to the CAT 2 practical assembly programming tasks.

### **Tasks**
1. **Control Flow and Conditional Logic**: Classify numbers as positive, negative, or zero.
2. **Array Reversal**: Reverse an array in place.
3. **Factorial Calculation**: Modular factorial calculation using subroutines.
4. **Port-Based Simulation**: Simulate monitoring and controlling based on sensor input.

### **Instructions**
- Assemble: `nasm -f elf32 <file>.asm`
- Link: `ld -m elf_i386 -o <file> <file>.o`
- Run: `./<file>`

### **Challenges**
- Managing memory directly in array reversal.
- Register preservation in modular programs.