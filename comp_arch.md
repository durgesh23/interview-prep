# Computer System Architecture

## Bit Operations
1. Set a bit
2. Clear a bit
3. Toggle a bit

## Pipeling

1. Consider a simple pipeline in a computer processor that has four stages: Fetch (F), Decode (D), Execute (E), and Writeback (W).

   1. Explain the basic concept of pipelining as it applies to a processor.
   2. If each stage takes 1 nanosecond to complete, how long would it take to complete a single instruction in a non-pipelined processor versus a pipelined processor?
   3. What are the potential benefits and drawbacks of using a pipelined processor?
   4. How would the pipeline be affected if a data hazard occurs between two instructions in the Execute stage? What could be done to handle this situation?

2.

## Virtual Memory

1. what do u mean by virtual memory
   1. what problem does it solve
      1. How does i solve not enough memory problem
      2. Holes in address space
      3. Security of data
      4.
2. Page Tables
3. Example of address translation using Page Table
4. Page Fault
   1. When does page fault occur
   2. Page is slow process how do you solve it
   3. how do you mak epage tables faster
      Ans: Cacheing ( TLB Cache)
5. VM of your Laptop?

## Cache.
   1. What is Cache?
      1. Cache Hit ?
      2. Cache Miss?
      3. Hit time?
      4. Hit Ratio?
   2. Principle of Locality
      1. Temporal Locality
      2. Spatial Localtiy
      3.
   3. Types of Cache/
      1. Associate Cache
      2. Direct Mapped Cache
      3. Set Associative Cache
         1. What is associativity?
   4. What is Cache Co-herence?
      1. Snoopy Bus Protocol?
         1. update protocol:
            1. Write back?
            2. Write Through?
#### Problem
1. 32 KB 2 way set associative cache, 16B block size
   1. Offset?
      1. `2^4 = 16 bytes
   2. No of Cache Locations?
      1. `32KB/16*2 = 1K`
   3. What index size we need?
   4.
   5. What is Cache Size?

## Architecture
1. What is Von Neuman Machine?
   The Von Neumann architecture consists of a single, shared memory for programs and data, a single bus for memory access, an arithmetic unit, and a program control unit.
   ![Von Neumann architecture](./Von_Neumann.png)
2. What is Harvard Architecture?
   Harvard architecture refers to a memory structure in which the processor is connected to two independent memory banks via two independent sets of buses.
   ![Harvard architecture](./Harvard.png)
3. CISC vs RISC?
4. What is Pipeling?
   1. Problems of executing multiple instructions at the same time?
      1. Structutal Hazard
         1. RAW: Read after Write
         2. WAW:
      2. Data Hazard
      3. Control Hazard
   2. 3 step?
   3. 4 steps?
   4. ARMV8 how many pipeling steps?
4.

# Embedded Concepts
1. I2C
2. SPI
3. UART
4.