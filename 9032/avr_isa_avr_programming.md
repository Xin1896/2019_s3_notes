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
	- Regsiters R1:R0 store the result of the multiplication function
	- Register R0 stores the data loaded from program memory

