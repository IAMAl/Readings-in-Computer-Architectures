# RiCA: Readings in Computer Architecture

**Lisence** : Creative Commons v1.0 Universal

## 1. Purpose of This Site
Collection of Educational Document related to Computer Architecture.

## 2. Target Readers
- Undergraduate Students related to Computer Science and Engineering
- Undergraduate Students related to Information Technology
- Undergraduate Students related to Electric and Electrical Engineering
- Or, Person having above Background(s)

## 3. Category of Collection

1. Semiconductor Technology
2. Digital Logic Circuit and its Design
3. Processor Architecture
4. Storage Architecture
5. Interconnect Architecture
6. Distributed System Architecture
7. Programming Model
8. Cost and Performance

## 4. Semiconductor Technology

### 4.1. Band-Gap Model

#### 4.1.1. Band Theory and Its Band-Gap

#### 4.1.2. Doping

### 4.2. Transistor

#### 4.2.1. Band-Gap and Junction

#### 4.2.2. Historical Review of Transistor

- "The invention of the transistor", Proceedings of the IEEE (Volume: 86, Issue: 1, Jan. 1998)

### 4.3. Fabrication

#### 4.3.1. Fabrication Process

#### 4.3.2. Wafer

#### 4.3.3. Packaging

### 4.4. Interposer and Die-Stacking

#### 4.4.1. Interposer

- "Interposer Technologies for High-Performance Applications", IEEE Transactions on Components, Packaging and Manufacturing Technology (Volume: 7, Issue: 6, June 2017)

#### 4.4.2. Chiplet

- "Architecture, Chip, and Package Codesign Flow for Interposer-Based 2.5-D Chiplet Integration Enabling Heterogeneous IP Reuse", IEEE Transactions on Very Large Scale Integration (VLSI) Systems (Volume: 28, Issue: 11, Nov. 2020)

## 5. Digital Logic Circuit and its Design

### 5.1. Boolean Algebra

#### 5.1.1.Boolean Algenra

- "Elements of Boolean Algebra for the Study of Information-Handling Systems", Proceedings of the IRE (Volume: 41, Issue: 10, Oct. 1953)

#### 5.1.2. Logic Gates

### 5.2. Logic Gate Primitives

### 5.3. Combinatorial Logic CIrcuit

### 5.4. Synchronous Logic and Pipelining

#### 5.4.1. Clocking

#### 5.4.2. Latches and Flip-Flop

#### 5.4.3. Registers

#### 5.4.4. Pipelining

- "Pipelining of Arithmetic Functions", IEEE Transactions on Computers (Volume: C-21, Issue: 8, Aug. 1972)

### 5.5. Finite State Machine

#### 5.5.1. State Diagram

#### 5.5.2. Mapping State Diagram to FSM

- "Introduction to the theory of finite-state machines", McGraw Hill; First Edition, First Printing (January 1, 1962)

#### 5.5.3. Optimization

### 5.6. Modular and Intellectual Properties

#### 5.6.1. Module: Hierarchical Description

#### 5.6.2. Reuse of Module

#### 5.6.3. Hardware Description Languages


## 6. Processor Architecture

### 6.1. Programming and Instruction Set

#### 6.1.1. Mapping State Diagram to Programming

#### 6.1.2. Mapping Programming to Instruction and Instruction Set

#### 6.1.3. Instruction Set Architecture

- "MIPS: A microprocessor architecture", ACM SIGMICRO Newsletter, October 1982

- "Reduced instruction set computer architecture", Proceedings of the IEEE, Volume: 76, Issue: 1, Jan. 1988

### 6.2. Computing Mechanism

#### 6.2.1. Primitives to Compute

- "Architecture of the IBM System/360", IBM Journal of Research and Development (Volume: 44, Issue: 1.2, Jan. 2000)

#### 6.2.2. Steering Instructions

- "The IBM System/360 Model 91: Machine Philosophy and Instruction-Handling", IBM Journal of Research and Development (Volume: 11, Issue: 1, Jan. 1967)

#### 6.2.3. Call and Return

#### 6.2.4. Computer System

- "IBM system/360 principles of operation", IBM Press, January 1964

- "The CDC 6600 Project", Annals of the History of Computing (Volume: 2, Issue: 4, Oct.-Dec. 1980)

### 6.3. Processor

#### 6.3.1. Mapping State Diagram to Processing Flow

#### 6.3.2. Mapping Processing Flow to FSM based Processor

### 6.4. Pipelined Processor

#### 6.4.1. Pipelining and Hazards

- "The performance impact of incomplete bypassing in processor pipelines", Proceedings of the 28th Annual International Symposium on Microarchitecture, 29 Nov.-1 Dec. 1995

#### 6.4.2. Pipeline Optimization

- "The optimum pipeline depth for a microprocessor", Proceedings 29th Annual International Symposium on Computer Architecture, May 2002

### 6.5. Out-of-Order Enhancement

#### 6.5.1. Out-of-Order Execution

- "An Efficient Algorithm for Exploiting Multiple Arithmetic Units", IBM Journal of Research and Development (Volume: 11, Issue: 1, Jan. 1967)

- "Instruction Issue Logic in Pipelined Supercomputers", IEEE Transactions on Computers ( Volume: C-33, Issue: 11, Nov. 1984)

- "Checkpoint Repair for High-Performance Out-of-Order Execution Machines", IEEE Transactions on Computers (Volume: C-36, Issue: 12, Dec. 1987)



### 6.6. Parallelism: Limits of Processors

- "Exploiting Instruction- and Data-Level Parallelism", IEEE Micro, September/October 1997, pp.20-27, vol. 17

#### 6.6.1. Instruction-Level Parallelism

- "Limits of instruction-level parallelism", ACM SIGARCH Computer Architecture News, April 1991

#### 6.6.2. Data-Level Parallelism

- "Subword parallelism with MAX-2", IEEE Micro, Volume: 16, Issue: 4, Aug 1996

#### 6.6.3. Thread-Level Parallelism

- "The case for a single-chip multiprocessor", ACM SIGPLAN Notices, September 1996

- "Converting thread-level parallelism to instruction-level parallelism via simultaneous multithreading", ACM Transactions on Computer Systems, August 1997

### 6.7. Exception and Interruption

- "Implementing precise interrupts in pipelined processors", IEEE Transactions on Computers, Volume: 37, Issue: 5, May 1988

## 7. Storage Architecture

### 7.1. Register

### 7.2. Static RAM

### 7.3. Volatile Memories

### 7.4. Non-Volatile Memories


## 8. Interconnect Architecture

### 8.1. Signaling

#### 8.1.1. Crosstalk

- "Reflection and crosstalk in logic circuit interconnections", IEEE Spectrum ( Volume: 7, Issue: 7, July 1970)

#### 8.1.2. Wire Delay


### 8.2. Networks-on-Chip

- "Route packets, not wires: on-chip inteconnection networks", DAC '01: Proceedings of the 38th annual Design Automation, 2001

- "A survey of research and practices of Network-on-chip", ACM Computing Surveys, June 2006

### 8.3. Livelock and Deadlock

- "Some Deadlock Properties of Computer Systems", ACM Computing Surveys, September 1972

- "Virtual-channel flow control", IEEE Transactions on Parallel and Distributed Systems, Volume: 3, Issue: 2, Mar 1992

### 8.4. Routing on a Chip

- "Deadlock-Free Message Routing in Multiprocessor Interconnection Networks", IEEE Transactions on Computers, Volume: C-36, Issue: 5, May 1987

## 9. Distributed System Architecture

## 10. Programming Model

## 11. Cost and Performance

### 11.1. Energy Consumption

#### 11.1.1. Energy Consumption on Microprocessors

- "Energy dissipation in general purpose microprocessors", IEEE Journal of Solid-State Circuits (Volume: 31, Issue: 9, Sep 1996)
