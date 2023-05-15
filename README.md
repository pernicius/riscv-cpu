## Digital (Sim)

A simulated, pipelined, 32bit Risc-V CPU using [Digital](https://github.com/hneemann/Digital).

### Instruction Standards:
- [x] "RV32I" Base Integer Instruction Set (v2.1) except FENCE, ECALL, EBREAK
- [ ] "M” Standard Extension for Integer Multiplication and Division (v2.0)
- [ ] “C” Standard Extension for Compressed Instructions (v2.0)
- [ ] “Zicsr” Control and Status Register (CSR) Instructions (v2.0)

### other Features:
- [x] Universal Microcode Compiler ([umcc](https://github.com/pernicius/umcc))

### Later features:
- User/Supervisor/Machine-Mode
- Memory Management Unit (MMU)
- some form of memory protection
- Interupts (PLIC and/or [CLIC](https://github.com/riscv/riscv-fast-interrupt/blob/master/clic.pdf))
- Exceptions
