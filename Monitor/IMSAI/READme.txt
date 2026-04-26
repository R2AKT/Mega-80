Based on IMSAI monitor (https://github.com/imsaiguy/8080-Monitor).

Adapted for ZASM assembler and 'Mega-80(Mega-580)' project (https://github.com/R2AKT)

Use ZASM assembler (https://github.com/Megatokio/zasm) for compilation.

Hardware required:
- CPU - https://github.com/R2AKT/CPU_8080;
- RAM - https://github.com/R2AKT/flat_mem_8k or https://github.com/R2AKT/flat_mem_32k;
- USART - https://github.com/R2AKT/USART - BASE address 0x008 (8251) and 0x000C (8253);
- PSU - https://github.com/R2AKT/power_unit.

Software:
 - IMSAI8080.asm - assembler code

 - IMSAI8080_ver.8k.bin - binary for 8k linear memory version
 - IMSAI8080_ver.8k.p001.bin - binary for 8k RAM version, part 1 (0x000-0x07FF). Load to UV EPROM/EEPROM IC DD1.
 - IMSAI8080_ver.8k.p002.bin - binary for 8k RAM version, part 2 (0x800-0x0FFF). Load to UV EPROM/EEPROM IC DD2.

 - IMSAI8080_ver.32k.bin - binary for 32k linear memory version. Load to UV EPROM/EEPROM IC DD1.


