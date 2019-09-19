# AVR

* 8-bit RISC architecture
* Instructions have 16bit length
* Take one clock cycle to execute

* AVR has a load store memory access architecture
* Internal program memory and data memory

## AVR Registers

* 32 8-bit registers (r0 ~ r31) or (R0 ~ R31)
* Some instructions only work on the second half of registers (R15 ~ R31)
* General purpose registers
* General purpose registers:
	- Register pairs that can be used as address registers/pointers:
		* X, R27:R26
		* Y, R29:R28
		* Z, R31:R30
	- Registers R1:R0 store the result of the multiplication function
	- Register R0 stores the data loaded from program memory
* I/O registers:
	- 64+ 8-bit registers
* Status register (SREG):

## Status Register (SREG)

The status register contains information about the result of the most recently
executed AL operation. It is updated by hardware after any AL operation.
It is *not* automatically saved when entering an interrupt routine. this must
be handled by software

### SREG bits
SREG has 8 bits, each denoting a different flag:
* Bit 0 - C (carry):
	- Meaning depends on operation
	- For addition, it is the carry from the most significant bit
	- For subtraction of unsigned int x-y, it indicates whether x<y or not.
	  if x<y, C=1. if x>y c=0.
	- 
