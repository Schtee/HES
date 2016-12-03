# Homebrew Games Console Spec

## Word Size
16 bit

## Registers
* 16 Bit SP
* 16 Bit PC
* 4 * 16 Bit General purpose
* 8 Bit flags

### Flags
|7     |6     |5     |4     |3       |2       |1    |0   |
|------|------|------|------|--------|--------|-----|----|
|-     |-     |-     |-     |N       |O       |C    |Z   |
|Unused|Unused|Unused|Unused|Negative|Overflow|Carry|Zero|

## Speed
* 1 MHz
* 1 Cycle per instruction

## Memory
64KB (16 bit addressable memory)
