# 32-bit_Simple_RISC
A 32-bit processor in Logisim with a 5-stage pipeline structure.

The various components of the processor can be found in `Simple_risc`. The following stages of the 5-stage pipeline were implemented:
- Instruction Fetch (IF) stage
- Operand Fetch (OF) stage 
- Execute (EX) stage
- Memory Access (MA) stage 
- Read-Write (RW) stage

The ALU, Control Unit, Forwarding Unit, Data Lock Unit and Latches were also implemented and are present in `RiscProcessor.circ`

***

For further details of the project [go here](https://github.com/Deep-A-nshu/32-Bit-Simple-RISC-Processor/tree/main/docs)

The SimpleRISC codes that were used to evaluate and benchmark the processor can be found in `Benchmarks`. Additionally, an assembler was created to convert the assembly language code to machine code and can be accessed from the `Assembler.py` file.            

## Conculsions
By Building on our knowledge of a SimpleRISC processor and combining it with the essential 5-stage pipeline structure, we have been able to successfully design and implement a 32-bit SimpleRisc processor with  forwarding and lock units . The integration with the pipeline provided significant speed-up in implementation of programs with polynomial complexity. The working of the processor has been fully verified through test-programs and benchmark evaluations. Further, the project allowed us to delve deeper into the nitty-gritty of basic computer architectures and understand the importance of individual components. In the end, we were able to build a processor which is capable of performing many common instructions that are typically required by processors used in small embedded systems.
