# RM_Presentation

A presentation on the work of John Cocke ...
***
#### John - Part 1 RISC Architecture
#### Matt - Part 2 Compiler Optimization
***
### Presentation Part 1 - RISC Architecture
***
### Introduction
In the early 1970s, John Cocke transformed computing by simplifying the 
set of instructions that tell computers which functions to perform. 
Cocke was the turing award winner of 1987. Cocke won this award for his significant contributions in the design and theory of 
compilers, the architecture of large systems and the development of Reduced Instruction Set Computers (RISC): 
for discovering and systematizing many fundamental transformations now used in optimizing compilers 
including the reduction of:
* Operator Strength
* Elimination of Common Subexpressions 
* Register Allocation
* Constrant Propagation
* Dead Code Elimination
***
### RISC Architecture
* Reduced Instruction Set Computers.

* The main idea behind this architecture was to make simpler hardware by using a reduced instruction set composed by a few basic step for loading evaluating and storing operations. 

* Although this is a reduced instruction set this approach tries to increase the CPU performance.

* Reduce the cycles per instruction at the cost of the number of instructions per program.

### Characteristic of RISC
* Relatively few instructions 
* One word instructions.
* Instruction take a single clock cycle to get executed.
* More number of general purpose register.
* Simple Addressing Modes.
* Less Data types.
* Pipeline can be achieved.

#### Pipelining
* Pipelining, a standard feature in RISC processors, is much like an assembly line. 
Because the processor works on different steps of the instruction at the same time,
more instructions can be executed in a shorter period of time.

* Pipelining is a technique of decomposing a sequentail 
process into sub-processes, with each sub-process 
being executed in a special dedicated segment that 
operates concurrently withh all other segments 

* Any operation that cn be cecomposed into a 
sequence of a sub-operation of about the same 
compleity can be implemented by a pipeline processor

***
### RISC Projects
John Cocke was involved in three RISC projects:
* IBM 801 machine (1974)
* Berkeley’s RISC-I and RISC-II processors (1980)
* Stanford’s MIPS processor (1981)
***
### IBM 801 machine
* IBM designed an experimental minicomputer named the 801. 
  - *The name 801 comes from the building the project was housed in.*
* IBM used the resulting architecture in various roles out through to the 1980s.
* In the early-mid 1970s, IBM were interested in the possibility of constructing a telephone switch to handle a million cal per hour. 
* Their estimation was that this would require at least a 6 MIPS processor. 
* John Cocke and his group who were working on the project at the Thomas J. Watson Research Center.

### Berkeley’s RISC-I and RISC-II processors
#### RISC I 
* Originally known as Gold 
  - *The first attempt to implement the RISC concept was originally known as Gold*
* VLSI design course 
  - *Work on the design started in 1980 as part of a VLSI design course, but the then-complicated design crashed almost all existing design tools. The team had to spend considerable amounts of time improving or re-writing the tools, and even with these new tools it took just under an hour to extract the design on a VAX-11/780.*
 *  ACM ISCA
    - 44,500 transistors
    - 31 instructions
    - 78 32-bit registers
    - *The final design, known as RISC I, was published in ACM ISCA in 1981.*
    - *It had 44,500 transistors implementing 31 instructions and a register file containing 78 32-bit registers*
    
#### RISC II
* Blue design
  - *While the RISC I design ran into delays, work at Berkeley had already turned to the new Blue design.*
  - *Work on Blue progressed slower than Gold, due both to the lack of a pressing need now that Gold was going to fab, as well as changeovers in the classes and students staffing the effort. This pace also allowed them to add in several new features that would end up improving the design considerably.*
  
* 138 registers broken into 
* 8 windows - *of*
* 16 registers each - *with another*
* 10 globals

* RISC instruction set with only 39,000 transistors

### Stanford’s MIPS processor 
* Strong background in compilers
* Develop a processor 
  - *whose architecture would represent the lowering of the compiler to the hardware level, as opposed to the raising of hardware to the software level, which had been a long running design philosophy in the hardware industry.*
 * MIPS processor implemented a smaller, simpler instruction set
 * 32 registers - *each*
 * 32 bits wide 

##### END OF PART 1
***
### Presentation Part 2 - Compiler Optimization
***
### Introduction
***
### Compiler Optimization
##### END OF PART 2
***
### Conclusion
***

#### References
[1] [A.M. Turing](https://amturing.acm.org/award_winners/cocke_2083115.cfm)

[2] [John Cocke | Lemelson](https://lemelson.mit.edu/resources/john-cocke) *

[3] [RISC Architecture](https://www.ibm.com/ibm/history/ibm100/us/en/icons/risc/) *

[4] [Britannica Article by William L. Hosch](https://www.britannica.com/biography/John-Cocke)

[5] [Computer Pioneers](https://history.computer.org/pioneers/cocke.html)

[6] [Computer Organization | RISC and CISC](https://www.geeksforgeeks.org/computer-organization-risc-and-cisc/#:~:text=RISC%3A%20Reduce%20the%20cycles%20per,number%20of%20cycles%20per%20instruction.) *

[7] [IBM 801](https://en.linkfang.org/wiki/IBM_801) *

[8] [RISC I & RISC II](https://en.wikipedia.org/wiki/Berkeley_RISC) *

[9] [MIPS](https://cs.stanford.edu/people/eroberts/courses/soco/projects/risc/mips/index.html) *

10 [RISC Pipeline](https://cs.stanford.edu/people/eroberts/courses/soco/projects/risc/pipelining/index.html) *

***
