# RAM-Design
Company name- CODTECH IT SOLUTIONS
Name- Akshaya Gollapelly
Intern ID-CT08PFT
Domain- VLSI
Duration- 4 weeks
Mentor- Neela Santosh
Descrition--The given Verilog code defines a Synchronous RAM (SyncRAM) module along with a testbench to verify its functionality. The SyncRAM module has parameterized data width and address width, making it flexible for different memory configurations. It consists of a register array (`ram`) to store data, and it operates synchronously with the clock signal (`clk`). The write operation occurs when the `we` (Write Enable) signal is high, storing the input data (`din`) at the specified address (`addr`). The read operation is continuously available through a combinational assignment of `dout` to the value stored at the given address. The testbench generates a clock signal and performs a series of write and read operations to validate the module. It uses `$monitor` to display the results, helping in debugging and verifying correct memory behavior.
