# SV-Parameterized-N-bit-Register
A parameterized N-bit register in digital design refers to a register whose bit-width can be set by a parameter, making it flexible and reusable across different designs where different word sizes are needed.
**Why Parameterized?**
Instead of hardcoding the bit-width (e.g., 8-bit, 16-bit), we define a parameter that can be set at instantiation time. This allows the same module to be used as an 8-bit register, 32-bit register, etc.
**Benefits of Parameterization**
Promotes modular design
Reduces bugs from repetitive code
Enables easy testing with different widths
Works well with generators or configurable IP cores
