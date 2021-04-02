#   Operating System
**Introduction to OS**

-   Services and Examples

-   Types of OS

    -   Single Tasking

    -   Multiprogramming and Multitasking

    -   Multithreading

        -   Real-world examples

        -   Disadvantages

        -   Examples of Race Condition

    -   Multiprocessing

    -   Multiuser

-   Thread V/S Process

-   User Threads V/S Kernel Threads

**Process Management**

-   Introduction to Program and Process

-   Process States

    -   For Single Tasking Systems.

    -   Multiprogramming Systems 

    -   5-States Model

    -   7-States Model

-   Process Control Block(PCB)

-   Process Scheduler

    -   Long Term Scheduler

    -   Short Term Scheduler

    -   Medium Term Scheduler

-   Scheduling Algorithms

    -   Background

    -   Explaining various times in Scheduling algorithms

    -   Goals of Scheduling Algorithms

-   FCFS Algorithm (Non-Preemptive)

    -   Understanding using a problem

    -   Calculating various times

    -   Characteristics of FCFS Algo

-   SJFS Algorithm (Non-Preemptive)

    -   Understanding using a problem

    -   Calculating various times

    -   Characteristics of SJFS Algo

-   SJF or SRTF Algorithm(Pre-emptive)

    -   Understanding using a problem

    -   Calculating various times

    -   Characteristics of SJF or SRTF Algo

-   Priority Scheduling (Non-Preemptive)

    -   Understanding using a problem

    -   Calculating various times

-   Priority Scheduling (Preemptive)

    -   Understanding using a problem

    -   Calculating various times

-   Problems with Priority Scheduling

-   Round Robin Scheduling (Pre-emptive)

    -   Characteristic

    -   Calculating various times using a problem

-   Multilevel Queue Scheduling

-   Multilevel Queue Scheduling with Feedback

**Process Synchronization**

-   Introduction

-   Consumer and Producer Problem

-   Race Condition

-   Goals of Synchronization Mechanism

    -   Mutual Exclusion

    -   Progress

    -   Bounded Waiting

    -   Performance

-   Overview of Synchronization Mechanism

    -   Disabling Interrupts

    -   Locks(or Mutex)

    -   Semaphores

    -   Monitors

    -   Application of Process Synchronization

-   Locks for Synchronization

    -   Problems of Deposit and Withdrawl problem

    -   TSL Lock mechanism

-   Critical Section

    -   Problems of Deposit and Withdrawl problem

    -   Entry Section

    -   Critical Section 

    -   Exit Section

    -   Non-Critical Section

-   Semaphores

    -   wait() and signal() function

    -   Original importance by Dijkstra

-   Binary Semaphore

    -   Internal Working of Semaphore

    -   Binary Semaphore

    -   Wait and Signal Protocol in Binary Semaphore

-   Monitors

    -   Introduction, Syntax and Working

**Deadlock**

-   Introduction and Understanding

    -   Mutual Exclusion

    -   Hold and Wait

    -   No Preemption

    -   Circular Wait

    -   Resource Allocation Graph

-   Deadlock Handling Mechanism

    -   Deadlock Prevention

    -   Deadlock Avoidance

    -   Detection and Recovery

    -   Ignoring the Deadlock

    -   EDEADLK

-   Deadlock Prevention Mechanism

    -   Mutual Exclusion

    -   Hold and Wait

    -   No Preemption

    -   Circular Wait

-   Deadlock Avoidance Mechanism

    -   Bankers Algorithm

-   Discussion on Deadlock Detection and Recovery

**Memory Management**

-   Working behind the compilation and running of a program

-   Address Binding

    -   Compile Time

    -   Load Time

    -   Run Time

    -   Problems of Runtime Binding

    -   Logical and Physical Address

-   Runtime Binding

    -   Working

-   Memory Management and hierarchy

    -   Access time, capacity and cost

-   Evolution of Memory Management

    -   Single Tasking

    -   Multitasking

    -   Memory Allocation

-   Dynamic Partitioning

    -   Bitmap

    -   Linked List

-   Virtual Memory Introduction

    -   Concept discussion

    -   Performance Impact of Page Fault

-   TLB, Demand Paging, Thrashing, Page Replacement Algorithm

-   Segmentation and Paging with Segmentation

# Database Management System

-   **Introduction to DBMS**

    -   Understanding DBMS

    -   Evolution of DBMS

        -   File-Based

        -   Relational DBMS

        -   NoSQL

-   **ER and Relational Model**

    -   ER Model

        -   Understanding Entity Set, Relationship Set and Attributes.

    -   Keys

        -   Candidate Key

        -   Super Key

        -   Primary Key

        -   Problems involving identifying keys.

    -   ER Diagram

        -   Participation 

        -   Weak Entity Set

    -   Foreign Key

        -   Introduction and Identifying foreign keys

        -   Understanding Referential Integrity

-   **Database Designing**

    -   Normalization

        -   Data Redundancy

        -   Data Integrity

        -   Objects of Good DB design

        -   Understanding Anomalies

            -   Updation Anomaly

            -   Insertion Anomaly

            -   Deletion Anomaly

    -   Functional Dependency

        -   Explanation using DB tables

        -   Need for Functional Dependency

        -   Trivial and Non-trivial

    -   First Normal Form

    -   Second Normal Form

    -   Third Normal Form

    -   BCNF

-   **SQL**

    -   Introduction

        -   DDL, DQL, DML, DCL

        -   Understanding the creation of tables using SQL commands

        -   INSERT, SELECT, FROM

    -   Joins in SQL

        -   Cross Product

        -   Inner Join - Equal and Natural Join

        -   Outer Join - Left, Right and Full Join

        -   Self Join

    -   Aggregate Functions and Group By

        -   SUM, MAX, MIN, COUNT, AVG

        -   Group BY

        -   Difference b/w WHERE & HAVING

    -   Subqueries

        -   Understanding querying from the table using SQL commands

        -   Various problems in subqueries

    -   Correlated subqueries

-   **Indexing**

    -   Indexing in Database

        -   Introduction to Clustered and Non clustered indexing

    -   Clustered Index

        -   Sparse and Dense Index

    -   Non-clustered Index

    -   Multilevel Indexing B & B+ Trees

-   **Transaction and Concurrency Control**

    -   Introduction and ACID properties

    -   Conflict Serializability

        -   Conflicting operators in Transactions

        -   Given and Serial Schedule

        -   Precedence Graph

    -   View Serializability

        -   Initial Read

        -   Updated Read

        -   Final Write

    -   Recoverable, Cascadeless and Strict Schedule

    -   Two-Phase Locking Protocol

        -   Understanding Shared and Exclusive Locks

        -   Growing and Shrinking phase

    -   Problems with basic two-phase locking

        -   Deadlock

        -   Recoverability

    -   Conservative, Strict and Rigorous 2PL

        -   Difference between them

    -   Timestamp Based Protocols

        -   Rules to find:

        -   TS

        -   RTS

        -   WTS

#  Computer Networks:

-   **Introduction to CN**

    -   Network Criteria Discussion

    -   OSI Model

        -   The need for such a model

        -   Various layers at Sender and Receiver side

    -   TCP/IP Model

        -   The need for such a model

        -   Various layers at Sender and Receiver side

        -   Protocol Data Units

-   **Data Link Layer**

    -   Introduction

        -   Explanation using Home and Office network

        -   Functionalities

            -   Framing

            -   Error Detection

            -   Error Flow Control

            -   Multiple Access

    -   Delays

        -   Transmission Delay

        -   Propagation Delay

        -   Queuing Delay

        -   Processing Delay

    -   Error and Flow Control Protocols

        -   Stop and Wait

        -   Selective Repeat Protocol

        -   Sliding Window Background

        -   Go Back N

-   **Network Layer**

    -   Introduction

        -   Functionalities

    -   Circuit Switching V/S Packet Switching

        -   Difference and explanation

    -   Network Address Translation

        -   Identifying private and public IPs

    -   Classful Addressing

        -   Problems

    -   Subnetting

        -   Subnet Mask

        -   The division into two or more networks

        -   Problems

    -   Classless Addressing

        -   Classless Inter-Domain Routing

        -   Problem with classful addressing

    -   Routing Algorithms

        -   Exterior Gateway Protocols

        -   Interior Gateway Protocols

        -   Static V/S Dynamic Routing Algorithms

        -   Unicast, Broadcast, Multicast & Anycast

        -   Cost of Links

        -   Goals of Routing Algos

    -   Distance Vector Routing

        -   Introduction

        -   Algorithm

        -   Problems

        -   Routing Information Protocols

    -   Link State Routing

        -   Introduction

        -   Algorithm

        -   Use

-   **Transport Layer**

    -   Introduction

        -   Use and Examples

    -   TCP V/S UDP

        -   Difference and explanation

-   **Application Layer**

    -   Introduction

        -   Working of various layers

    -   Understanding and background of Domain Name System

    -   Address Resolution Protocol (ARP)

        -   Working

    -   Dynamic Host Configuration Protocol (DHCP)

        -   Working at Home and Office Network

