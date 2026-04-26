Based on MON85 monitor (Dave Dunfield - https://bitsofthegoldenage.org/download/mon85-dave-dunfields-diagnostic-monitor/,
Sergey Kiselev - https://github.com/skiselev/minimax8085/tree/master/software/mon85).

Adapted for ZASM assembler and 'Mega-80(Mega-580)' project (https://github.com/R2AKT)

Use ZASM assembler (https://github.com/Megatokio/zasm) for compilation.

Hardware required:
- CPU - https://github.com/R2AKT/CPU_8080;
- RAM - https://github.com/R2AKT/flat_mem_8k or https://github.com/R2AKT/flat_mem_32k;
- USART - https://github.com/R2AKT/USART - BASE address 0x008 (8251) and 0x000C (8253);
- PSU - https://github.com/R2AKT/power_unit.

Software:
 - IMSAI8080.asm - assembler code

 - mon85-v13_ver.8k.bin - binary for 8k linear memory version
 - mon85-v13_ver.8k_p001.bin - binary for 8k RAM version, part 1 (0x000-0x07FF). Load to UV EPROM/EEPROM IC DD1.
 - mon85-v13_ver.8k_p002.bin - binary for 8k RAM version, part 2 (0x800-0x0FFF). Load to UV EPROM/EEPROM IC DD2.

 - mon85-v13_ver.32k.bin - binary for 32k linear memory version. Load to UV EPROM/EEPROM IC DD1.


