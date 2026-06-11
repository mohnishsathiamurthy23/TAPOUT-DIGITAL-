# VLSI Projects

This repository contains Digital Logic Design, RTL architectures, and verification environments developed using Verilog HDL and Xilinx Vivado. The projects showcased here represent handson engineering flows implemented during specialized chip training, focusing on arithmetic circuit optimization, protocol modeling, and memory reliability analysis.
Toolstack & TechnologiesHardware Description Language: Verilog 
HDLDevelopment & Synthesis Suite: Xilinx VivadoSimulation Tools: Vivado Simulator 
(XSIM)Design Paradigms: RTL Design, Finite State Machines (FSM), Testbench VerificationFeatured Projects

1. SPI Protocol ControllerDescription: A robust digital controller replicating the Synchronous Serial Peripheral Interface (SPI) protocol.Key Implementations:Modeled Master/Slave architectures using hardware-efficient Finite State Machines (FSM).Handled synchronous data transmission, clock polarity (CPOL), and clock phase (CPHA) configurations.Verification: Validated complete data integrity and transmission timing constraints via functional simulation.

2. High-Speed 3x3 Array MultiplierDescription: An optimized structural implementation of a digital parallel multiplier designed for high-throughput arithmetic logic units (ALUs).Key Implementations:Managed partial product generation and reduction using efficient adder cell trees to minimize critical path delay.Verification: Stimulated with comprehensive test vectors to confirm mathematical and logical correctness under variable inputs.
  
   
3. Carry Look-Ahead Adder (CLA)Description: A high-speed adder architecture designed to bypass the sequential carry propagation bottleneck found in standard ripple-carry adders.Key Implementations:Implemented dedicated Carry Generate ($G$) and Carry Propagate ($P$) logic blocks for parallelized carry calculation.Verification: Synthesized and simulated to compare propagation delay improvements against standard architectures.Verification & Wavefor.

---
