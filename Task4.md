Synthesis Lab 1 & 2


Yosys


![task4 1](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/885f24f1-2381-4537-a247-52469ca05ab4)


read_liberty -lib ../my_lib/lib/sky130_fd_sc_hd__tt_025C_1v80.lib
read_verilog good_mux.v
synth -top god_mux


![task4 2](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/bde8dfca-e878-4607-9177-abda4dc67c05)



![task4 2](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/c8a214d4-63c6-40a3-99f6-8e86acd06fea)



gvim good_mux


![task4](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/bc69f1a4-7571-4747-a51d-ad4590246c9a)



write_verilog good_mux_netlist.v
!gvim good_mux_netlist.v
write_verilog -noattr good_mux_netllist.v
!gvim good_mux_netlist.v


![task4 5](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/3eb20806-aa63-471a-9762-84001740bdd9)



![task4 4](https://github.com/K-P-Shwetha/RISC-V/assets/160413577/da94ffd7-4128-4f30-8820-5f1b7f110beb)

