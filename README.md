# RCA: Readings in Computer Architectures

**Licence** : Creative Commons v1.0 Universal

## A. Purpose of This Site

Collection of Educational Documents related to Computer Architecture.

## B. Target Readers

Undergraduate Students related to

- Computer Science and Engineering
- Electric and Electrical Engineering
- Information Science and Engineering

Or, Person having the above Background(s)

## C. Category of Collection

1. Programming Model
2. Computer Architecture
3. Processor Architecture
4. Storage Architecture
5. Distributed Computing Architecture
6. Interconnect Architecture
7. Digital Logic Circuit and its Design
8. Semiconductor Technology
9. Constraint and Performance

## 1. Programming Model


## 2. Computer Architecture

### 2.1. Programming and Instruction Set

#### 2.1.1. Mapping State Diagram to Program

#### 2.1.2. Mapping Program to Instruction Stream

- "Programming Languages — The First 25 Years", Wegner, IEEE Transactions on Computers ( Volume: C-25, Issue: 12, December 1976)

- "ILLIAC IV Software and Application Programming", D.J. Kuck, IEEE Transactions on Computers ( Volume: C-17, Issue: 8, August 1968)

### 2.2. Computing Mechanism

#### 2.2.1. Primitives to Compute

- "Architecture of the IBM System/360", G. M. Amdahl, G. A. Blaauw, F. P. Brooks, IBM Journal of Research and Development (Volume: 44, Issue: 1.2, Jan. 2000)

#### 2.2.2. Instruction Handling

- "The IBM System/360 Model 91: Machine Philosophy and Instruction-Handling", D. W. Anderson, F. J. Sparacio, R. M. Tomasulo, IBM Journal of Research and Development (Volume: 11, Issue: 1, Jan. 1967)

#### 2.2.3. Computer System

- "IBM system/360 principles of operation", IBM Press, January 1964

- "The CDC 6600 Project", James E. Thornton, Annals of the History of Computing (Volume: 2, Issue: 4, Oct.-Dec. 1980)

- "The CRAY-1 computer system", Richard M. Russell, Hardware Reference Manual, Cray Research, Inc., 1977


## 3. Processor Architecture


### 3.1. Instruction-Set
#### 3.1.1. Instruction Set: Mapping State Diagram to Processing Flow

- "VLSI Processor Architecture", J.L. Hennessy, IEEE Transactions on Computers ( Volume: C-33, Issue: 12, Dec. 1984)

#### 3.1.2. Mapping Processing Flow to FSM-based Processor

#### 3.1.3. Instruction Set Architecture

- "MIPS: A microprocessor architecture", John Hennessy, Norman Jouppi, Steven Przybylski, Christopher Rowen, Thomas Gross, Forest Baskett, John Gill, ACM SIGMICRO Newsletter, October 1982

- "Reduced instruction set computer architecture", W. Stallings, Proceedings of the IEEE, Volume: 76, Issue: 1, Jan. 1988

### 3.2. Pipelined Processor

#### 3.2.1. Hazards and Bypassing

- "The design space of register renaming techniques", D. Sima, IEEE Micro (Volume: 20, Issue: 5, Sep/Oct 2000)

- "The performance impact of incomplete bypassing in processor pipelines", P.S. Ahuja, D.W. Clark, A. Rogers, Proceedings of the 28th Annual International Symposium on Microarchitecture, 29 Nov.-1 Dec. 1995

#### 3.2.2. Pipeline Optimization

- "The optimum pipeline depth for a microprocessor", A. Hartstein; T.R. Puzak, Proceedings 29th Annual International Symposium on Computer Architecture, May 2002

### 3.3. Out-of-Order Enhancement

#### 3.3.1. Out-of-Order Execution

- "An Efficient Algorithm for Exploiting Multiple Arithmetic Units", R. M. Tomasulo, IBM Journal of Research and Development (Volume: 11, Issue: 1, Jan. 1967)

- "Instruction Issue Logic in Pipelined Supercomputers", Shlomo Weiss, James E. Smith, IEEE Transactions on Computers (Volume: C-33, Issue: 11, Nov. 1984)

- "Checkpoint Repair for High-Performance Out-of-Order Execution Machines", Wen-Mei W. Hwu, Yale N. Patt, IEEE Transactions on Computers (Volume: C-36, Issue: 12, Dec. 1987)

#### 3.3.2. Superscalar Processors

- "The Alpha AXP architecture and 21064 processor", E. McLellan, IEEE Micro ( Volume: 13, Issue: 3, June 1993)

- "The microarchitecture of superscalar processors", J.E. Smith, G.S. Sohi, Proceedings of the IEEE (Volume: 83, Issue: 12, Dec. 1995)

- "A 600 MHz superscalar RISC microprocessor with out-of-order execution", B.A. Gieseke, R.L. Allmon, D.W. Bailey, B.J. Benschneider, S.M. Britton, J.D. Clouser, H.R. Fair, J.A. Farrell, M.K. Gowan, C.L. Houghton, J.B. Keller, T.H. Lee, D.L. Leibholz, S.C. Lowell, M.D. Matson, R.J. Matthew, V. Peng, M.D. Quinn, D.A. Priore, M.J. Smith, K.E. Wilcox, 1997 IEEE International Solids-State Circuits Conference. Digest of Technical Papers

### 3.4. Vector Microprocessors

- "Advanced Vector Architectures", Roger Espasa, Ph.D. Thesis, 1997

- "Vector Microprocessors", K. Asanovic, Ph.D. Thesis, 1998

- "Vector architectures: past, present and future", Roger Espasa, Mateo Valero, James E. Smith, Proceedings of the 12th international conference on SupercomputingJuly 1998

### 3.5. Parallelism: Limits of Processors

- "Exploiting Instruction- and Data-Level Parallelism", Roger Espasa, Mateo Valero, IEEE Micro, September/October 1997, pp.20-27, vol. 17

#### 3.5.1. Instruction-Level Parallelism

- "Limits of instruction-level parallelism", David W. Wall, ACM SIGARCH Computer Architecture News, April 1991

- "Checkpoint processing and recovery: towards scalable large instruction window processors", H. Akkary, R. Rajwar, S.T. Srinivasang, Proceedings. 36th Annual IEEE/ACM International Symposium on Microarchitecture, 2003. MICRO-36

- "A Survey of Techniques for Dynamic Branch Prediction", S Mittal, ArXiv, 2018


#### 3.5.2. Basic Block-Level Parallelism

#### 3.5.3. Thread-Level Parallelism

- "The case for a single-chip multiprocessor", Kunle Olukotun, Basem A. Nayfeh, Lance Hammond, Ken Wilson, Kunyung Chang, ACM SIGPLAN Notices, September 1996

- "Simultaneous multithreading: a platform for next-generation processors", S.J. Eggers, J.S. Emer, H.M. Levy, J.L. Lo, R.L. Stamm, D.M. Tullsen, IEEE Micro ( Volume: 17, Issue: 5, Sept.-Oct. 1997)

- "Niagara: a 32-way multithreaded Sparc processor," P. Kongetira, K. Aingaran and K. Olukotun, IEEE Micro, vol. 25, no. 2, pp. 21-29, March-April 2005


#### 3.5.4. Data-Level Parallelism

- "Subword parallelism with MAX-2", Ruby B. Lee, IEEE Micro, (Volume: 16, Issue: 4, Aug 1996)
  
- "Implementing streaming SIMD extensions on the Pentium III processor", S.K. Raman, V. Pentkovski, J. Keshava, IEEE Micro (Volume: 20, Issue: 4, Jul/Aug 2000)


### 3.6. Exception and Interruption

- "Implementing precise interrupts in pipelined processors", J.E. Smith, A.R. Pleszkun, IEEE Transactions on Computers, (Volume: 37, Issue: 5, May 1988)


## 4. Storage Architecture

### 4.1. Volatile Memories

#### 4.1.1. Dynamic RAM

#### 4.1.2. Static RAM


### 4.2. Non-Volatile Memories

- "Emerging Memory Technologies: Recent Trends and Prospects", Shimeng Yu,  Pai-Yu Chen, IEEE Solid-State Circuits Magazine (Volume: 8, Issue: 2, Spring 2016)


### 4.3. Cache Memories

- "Evaluation techniques for storage hierarchies", R.L. Mattson, J. Gecsei, D. R. Slutz, I. L. Traiger, IBM Systems Journal (Volume: 9, Issue: 2, 1970)

- "Evaluating associativity in CPU caches", M.D. Hill, A.J. Smith, IEEE Transactions on Computers ( Volume: 38, Issue: 12, Dec 1989)

- "Fundamental Limits of Caching", Mohammad Ali Maddah-Ali, Urs Niesen, IEEE Transactions on Information Theory ( Volume: 60, Issue: 5, May 2014)


## 5. Interconnect Architecture

### 5.1. Signaling

#### 5.1.1. Crosstalk

- "Reflection and crosstalk in logic circuit interconnections", John A. DeFalco, IEEE Spectrum (Volume: 7, Issue: 7, July 1970)

#### 5.1.2. Wire Delay

- "The Transient Analysis of Damped Linear Networks with Particular Regard to Wideband Amplifiers", W.C. Elmore, J. Applied Physics, vol. 19(1), 1948

- "International Technology Roadmap for Semiconductors", Semiconductor Industry Association, 2001

- "The future of wires", R. Ho, K.W. Mai, M.A. Horowitz, Proceedings of the IEEE (Volume: 89, Issue: 4, April 2001)

### 5.2. Networks-on-Chip

- "Route packets, not wires: on-chip interconnection networks", W.J. Dally, B. Towles, DAC '01: Proceedings of the 38th annual Design Automation, 2001

- "Evaluating Bufferless Flow Control for On-chip Networks", George Michelogiannakis, Daniel Sanchez, William J. Dally, Christos Kozyrakis, 2010 Fourth ACM/IEEE International Symposium on Networks-on-Chip

- "A survey of research and practices of Network-on-chip", Tobias Bjerregaard, Shankar Mahadevan, ACM Computing Surveys, June 2006

### 5.3. Livelock and Deadlock

- "Some Deadlock Properties of Computer Systems", Richard C. Holt, ACM Computing Surveys, September 1972

- "Deadlock-Free Message Routing in Multiprocessor Interconnection Networks", Dally, Seitz, IEEE Transactions on Computers ( Volume: C-36, Issue: 5, May 1987)
  
- "High Performance Communications In Processor Networks," C. R. Jesshope, P. R. Miller and J. T. Yantchev, The 16th Annual International Symposium on Computer Architecture, 1989, pp. 150-157

### 5.4. Routing on a Chip

- "The Turn Model for Adaptive Routing", C.J. Glass, L.M. Ni, Proceedings the 19th Annual International Symposium on Computer Architecture, 1992

- "A survey of wormhole routing techniques in direct networks", L.M. Ni, P.K. McKinley, Computer ( Volume: 26, Issue: 2, Feb. 1993)

- "Virtual-channel flow control", W.J. Dally, IEEE Transactions on Parallel and Distributed Systems, (Volume: 3, Issue: 2, Mar 1992)


## 6. Distributed Computing Architecture

### 6.1.1. Many-core Microprocessors

- "How to Make a Multiprocessor Computer That Correctly Executes Multiprocess Programs", Lamport, IEEE Transactions on Computers (Volume: C-28, Issue: 9, Sept. 1979)

- "Baring it all to Software: The Raw Machines", E. Waingold, M. Taylor, D. Srikrishna, V. Sarkar, W. Lee, V. Lee, J. Kim, M. Frank, P. Finch, R. Barua, J. Babb, S. Amarasinghe, A. Agarwal, Computer (Volume: 30, Issue:  9, September 1997)

### 6.1.2. Memory Coherency and Protocol

- "Shared memory consistency models: a tutorial", S.V. Adve, K. Gharachorloo, Computer (Volume: 29, Issue: 12, Dec 1996)

## 7. Digital Logic Circuit and its Design

### 7.1. Boolean Algebra and Logic Circuit

#### 7.1.1.Boolean Algebra

- "Elements of Boolean Algebra for the Study of Information-Handling Systems", Robert Serrell, Proceedings of the IRE (Volume: 41, Issue: 10, Oct. 1953)

#### 7.1.2. Logic Gate Primitives

#### 7.1.3. Combinatorial Logic Circuit

- "A Truth Table Method for the Synthesis of Combinational Logic", Sheldon B. Akers, IRE Transactions on Electronic Computers (Volume: EC-10, Issue: 4, Dec. 1961)

### 7.2. Finite State Machine

#### 7.2.1. State Diagram

- "Regular Algebra and Finite Machines", John Horton Conway, Dover Books on Mathematics

#### 7.2.2. Mapping State Diagram to FSM

- "Introduction to the theory of finite-state machines", S. Seshu, McGraw Hill; First Edition, First Printing (January 1, 1962)

#### 7.2.3. Optimization

### 7.3. Synchronous Logic and Pipelining

#### 7.3.1. Clocking, Latches and Flip-Flop

#### 7.3.2. Registers

#### 7.3.3. Pipelining

- "Pipelining of Arithmetic Functions", Thomas G. Hallin and Michael J. Flynn, IEEE Transactions on Computers (Volume: C-21, Issue: 8, Aug. 1972)

### 7.4. Modular and Intellectual Properties

#### 7.4.1. Module: Hierarchical Description

#### 7.4.2. Reuse of Module


## 8. Semiconductor Technology

### 8.1. Band-Gap Model

#### 8.1.1. Band Theory and Its Band-Gap

- "Characteristics of Electrons in Solids", IRE Transactions on Education (Volume: 3, Issue: 4, Dec. 1960)

- "Bandgap and transport properties of Si/sub 1-x/Ge/sub x/ by analysis of nearly ideal Si/Si/sub 1-x/Ge/sub x//Si heterojunction bipolar transistors," C. A. King, J. L. Hoyt and J. F. Gibbons, IEEE Transactions on Electron Devices, vol. 36, no. 10, pp. 2093-2104, Oct. 1989

#### 8.1.2. Doping

- "The influence of heavy doping on the emitter efficiency of a bipolar transistor", H.J.J. De Man, IEEE Transactions on Electron Devices ( Volume: 18, Issue: 10, October 1971)

### 8.2. Transistor

- "The transistor — A new amplifier", Electrical Engineering, vol. 67, no. 8, pp. 740-740, Aug. 1948

- "Some circuit aspects of the transistor", R. M. Ryder, R. J. Kircher, The Bell System Technical Journal (Volume: 28, Issue: 3, July 1949)

#### 8.2.1. Band-Gap and Junction

- "Carrier Generation and Recombination in P-N Junctions and P-N Junction Characteristics", Chih-tang Sah, Robert N. Noyce, William Shockley, Proceedings of the IRE (Volume: 45, Issue: 9, Sept. 1957)

#### 8.2.2. Historical Review of Transistor

- "The invention of the transistor", Proceedings of the IEEE (Volume: 86, Issue: 1, Jan. 1998)

- "Evolution of the MOS transistor-from conception to VLSI", Sah Chih-Tang, Proceedings of the IEEE (Volume: 76, Issue: 10, Oct. 1988)


### 8.3. Fabrication

#### 8.3.1. Fabrication Process

- "Stabilization of Silicon Surfaces by Thermally Grown Oxides", M. M. Atalla, E. Tannenbaum, E. J. Scheibner, Bell System Technical Journal, May 1959

#### 8.3.2. Integrated Circuits

- "Miniature semiconductor integrated circuit", Jack S Kilby, US3115581A, U.S. Patent

- "Semiconductor Device and Lead Structure", Robert N Noyce, US2981877, U.S. Patent

#### 8.3.3. Packaging

- "Packaging technologies for supercomputer system", H. Hamaguchi, T. Watari and A. Dohya, IEEE International Symposium on Circuits and Systems (ISCAS), 1991, pp. 2292-2295 vol.4

### 8.4. Interposer, Die-Stacking, and Chiplet

#### 8.4.1. Interposer

- "Interposer Technologies for High-Performance Applications", Ahmad Usman, Etizaz Shah, Nithanth B. Satishprasad, Jialou Chen, Steven A. Bohlemann, Sajjad H. Shami, Ali A. Eftekhar, Ali Adibi, IEEE Transactions on Components, Packaging and Manufacturing Technology (Volume: 7, Issue: 6, June 2017)

- "Architecture, Chip, and Package Co-Design Flow for 2.5D IC Design Enabling Heterogeneous IP Reuse", Kim, Jinwoo and Murali, Gauthaman and Park, Heechun and Qin, Eric and Kwon, Hyoukjun and Chaitanya, Venkata and Chekuri, Krishna and Dasari, Nihar and Singh, Arvind and Lee, Minah and Torun, Hakki Mert and Roy, Kallol and Swaminathan, Madhavan and Mukhopadhyay, Saibal and Krishna, Tushar and Lim, Sung Kyu, Proceedings of the 56th Annual Design Automation Conference, 2019


#### 8.4.2. Die-Stacking


#### 8.4.3. Chiplet

- "Architecture, Chip, and Package Codesign Flow for Interposer-Based 2.5-D Chiplet Integration Enabling Heterogeneous IP Reuse", Jinwoo Kim, Gauthaman Murali, Heechun Park, Eric Qin, Hyoukjun Kwon, Venkata Chaitanya Krishna Chekuri, Nael Mizanur Rahman, Nihar Dasari, Arvind Singh, Minah Lee, Hakki Mert Torun, Kallol Roy, Madhavan Swaminathan, Saibal Mukhopadhyay, Tushar Krishna, Sung Kyu Lim, IEEE Transactions on Very Large Scale Integration (VLSI) Systems (Volume: 28, Issue: 11, Nov. 2020)

- "A 0.11 pJ/Op, 0.32-128 TOPS, Scalable Multi-Chip-Module-based Deep Neural Network Accelerator Designed with a High-Productivity VLSI Methodology", Brian Zimmer, Jason Clemons, Matthew Fojtik, Nan Jiang, Ben Keller, Alicia Klinefelter, Nathaniel Pinckney, Priyanka Raina, Stephen G. Tell, Yanqing Zhang, William J. Dally, Joel S. Emer, C. Thomas Gray, Stephen W. Keckler, Brucek Khailany, HotChips 31, 2019

- "Design and Analysis of an APU for Exascale Computing", Thiruvengadam Vijayaraghavan, Yasuko Eckert, Gabriel H. Loh, Michael J. Schulte, Mike Ignatowski, Bradford M. Beckmann, William C. Brantley, Joseph L. Greathouse, Wei Huang, Arun Karunanithi, Onur Kayiran, Mitesh Meswani, Indrani Paul, Matthew Poremba, Steven Raasch, Steven K. Reinhardt, Greg Sadowski, Vilas Sridharan, IEEE International Symposium on High Performance Computer Architecture (HPCA), 2017

## 9. Constraint and Performance

### 9.1. Scaling

#### 9.1.1. MOS-FET: Moore's Law

- "Cramming more components onto integrated circuits, Reprinted from Electronics", Gordon E. Moore, IEEE Solid-State Circuits Society Newsletter (Volume: 11, Issue: 3, Sept. 2006) 

#### 9.1.2. Power Consumption: Dennard's Scaling

- "Design of ion-implanted MOSFET's with very small physical dimensions", R.H. Dennard, F.H. Gaensslen, Hwa-Nien Yu, V.L. Rideout, E. Bassous, A.R. LeBlanc, IEEE Journal of Solid-State Circuits ( Volume: 9, Issue: 5, Oct. 1974)


### 9.2. Energy Consumption

- "Computing's energy problem (and what we can do about it)", Mark Horowitz, IEEE International Solid-State Circuits Conference Digest of Technical Papers (ISSCC), 2014

- "Energy dissipation in general purpose microprocessors", R. Gonzalez, M. Horowitz, IEEE Journal of Solid-State Circuits (Volume: 31, Issue: 9, Sep 1996)

- "Is dark silicon useful? Harnessing the four horsemen of the coming dark silicon apocalypse", Michael B. Taylor, DAC Design Automation Conference, 2012

