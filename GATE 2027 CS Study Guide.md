# GATE 2027 CS Study Guide

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

Sep 28, 2026 · @Bhasad Zindagi

GATE 2027 runs 6–21 February 2027, which gives you about 18 weeks from today. Register first: the no-late-fee deadline was extended to Oct 5, 2026, and the late-fee window closes Oct 12, 2026.

## Exam at a glance

| Item | Detail |
| --- | --- |
| Organiser | IIT Madras ([official site](https://gate2027.iitm.ac.in/)) |
| Exam dates | 6, 7, 13, 14, 20, 21 Feb 2027; CS date and session not yet announced. Plan for the earliest, Feb 6, 2027 |
| Sessions | Forenoon 9:30–12:30, afternoon 2:30–5:30 |
| Results | 19 March 2027 |
| Paper | 3 hours, computer-based, 65 questions, 100 marks |
| Split | General Aptitude 15 marks (10 Qs) + CS incl. Engineering Maths 85 marks (55 Qs) |
| Question types | MCQ, MSQ (multiple correct), NAT (type a number) |
| Negative marking | MCQ only: −1/3 on 1-mark, −2/3 on 2-mark. MSQ and NAT have none |
| Calculator | On-screen virtual calculator only; practise with it |

Sources: [IIT Madras press release](https://www.iitm.ac.in/happenings/press-releases-and-coverages/iit-madras-announces-dates-syllabus-revision-new-paper), [registration extension](https://testbook.com/news/gate-2027-official-website/), [session timings](https://www.freejobalert.com/articles/gate-exam-date-2027-out-direct-link-to-check-full-schedule-online-3068567), [marking scheme](https://bohikitap.in/gate-2027-information-brochure-is-out).

## Syllabus analysis: 2026 vs 2027

Study from the GATE 2027 syllabus, not 2026. Eight of the ten sections are word-for-word the same; Digital Logic and COA gained design depth, and Computer Networks was cut sharply. General Aptitude (verbal, quantitative, analytical, spatial) is unchanged.

| # | Section | GATE 2027 topics | Change vs 2026 |
| --- | --- | --- | --- |
| 1 | Engineering Maths | Discrete maths (logic, sets, relations, functions, posets, lattices, monoids, groups, graphs, combinatorics, recurrences, generating functions); linear algebra (matrices, determinants, linear systems, eigenvalues, LU); calculus (limits, continuity, maxima–minima, MVT, integration); probability and statistics (distributions, mean/median/mode/SD, Bayes) | Same |
| 2 | Digital Logic | Boolean algebra and minimisation (algebraic, K-map, tabular/Quine–McCluskey); design of combinational and sequential circuits; fixed and floating point | Now names K-map and tabular method explicitly; asks for circuit design |
| 3 | COA | Instruction set, addressing modes; ALU design; control unit design (hardwired, microprogrammed); memory interfacing, hierarchy performance, cache mapping; interrupt and DMA; pipelining and hazards | Added control-unit design and memory interfacing; secondary storage dropped |
| 4 | Programming & DS | C, recursion, arrays, stacks, queues, linked lists, trees, BSTs, binary heaps, graphs | Same |
| 5 | Algorithms | Searching, sorting, hashing; asymptotic complexity; greedy, DP, divide and conquer; graph traversals, MST, shortest paths | Same |
| 6 | Theory of Computation | Regex and FA; CFG and PDA; regular and CFLs, pumping lemma; Turing machines, undecidability | Same |
| 7 | Compiler Design | Lexing, parsing, SDT; runtime environments; intermediate code; local optimisation; constant propagation, liveness, CSE | Same |
| 8 | Operating System | System calls, processes, threads, IPC, synchronisation; deadlock; CPU and I/O scheduling; memory management, virtual memory; file systems | Same |
| 9 | Databases | ER model; relational algebra, tuple calculus, SQL; constraints, normal forms; file organisation, B and B+ tree indexing; transactions, concurrency control | Same |
| 10 | Computer Networks | Layering; circuit, packet and virtual-circuit switching + performance metrics; error detection, MAC, Ethernet; distance-vector and link-state routing; IPv4 fragmentation, CIDR, NAT; TCP flow and congestion control, sockets; DNS, HTTP | Trimmed: framing, bridging, flooding, ARP/DHCP/ICMP, UDP, SMTP, FTP and email removed; performance metrics (delay, throughput) added |

What this means for you: skip the removed CN topics, spend extra time on CN numericals (delays, throughput, window sizes), and practise control-unit and cache-mapping questions in COA.

Sources: [GATE 2027 CS syllabus (IIT Madras)](https://gate2027.iitm.ac.in/static/doc/GATE2027_Syllabus/CS_GATE2027_Syllabus.pdf), [GATE 2026 CS syllabus (IIT Guwahati)](https://gate2026.iitg.ac.in/doc/GATE2026_Syllabus/CS_2026_Syllabus.pdf).

## Weightage and priority

No subject is skippable, but GA, Maths and Programming + Algorithms together carry about half the paper. Figures below are approximate averages, not official.

&#91;embedded content: approximate · from past-paper analyses, 2023–2026\]

**Priority tiers for a 4-month plan**

- **Tier 1 — highest return per hour:** General Aptitude, Engineering Maths (especially discrete maths and probability), Programming & DS + Algorithms (these two alone gave 16–18 marks in 2023–2025).
- **Tier 2 — steady, predictable marks:** Operating System, COA, Databases, Computer Networks, Theory of Computation.
- **Tier 3 — small but quick to finish:** Digital Logic, Compiler Design. Each takes about a week and questions repeat patterns closely.

Sources: [GO Classes weightage analysis 2023–2025](https://www.goclasses.in/blog/a-strategic-analysis-of-subject-wise-weightage-trends-in-gate-cse-2023-2025), [PW subject-wise weightage](https://www.pw.live/gate/exams/gate-cse-subject-wise-weightage).

## 19-week plan

The plan has three phases: learn every subtopic by 10 Jan (weeks 1–15), revise with subject tests (week 16), then full mocks until the exam (weeks 17–19). It assumes about 6 focused hours a day, 6 days a week, with Sunday for catch-up and a weekly test.

**Every day, on top of the week's subject:** 30 minutes of General Aptitude, and 1 hour of previous-year questions (PYQs) on whatever you studied that day.

| Week | Starts | Main subject | Finish-line check |
| --- | --- | --- | --- |
| 1 | 28 Sep | Register for GATE. Discrete Maths I: logic, sets, relations, posets, lattices, functions | Logic + set theory PYQs |
| 2 | 5 Oct | Discrete Maths II: groups, graphs, counting, recurrences, generating functions | All discrete maths PYQs |
| 3 | 12 Oct | Programming in C, recursion, stacks, queues | Trace 30 C output questions by hand |
| 4 | 19 Oct | Linked lists, trees, BST/AVL, heaps, graphs, hashing | DS PYQs done |
| 5 | 26 Oct | Algorithms I: asymptotics, recurrences, searching, sorting, divide and conquer, greedy | Master theorem without notes |
| 6 | 2 Nov | Algorithms II: dynamic programming, graph traversals, MST, shortest paths | Algorithms PYQs done |
| 7 | 9 Nov | OS I: processes, threads, scheduling, synchronisation, deadlock | Gantt charts + semaphore PYQs |
| 8 | 16 Nov | OS II: memory, paging, virtual memory, file systems. Plus linear algebra | OS + linear algebra PYQs |
| 9 | 23 Nov | Calculus + Digital Logic I: number representation, floating point, minimisation, combinational design | Digital logic PYQs |
| 10 | 30 Nov | Digital Logic II: sequential design. COA I: ISA, addressing, control unit, memory, cache | Cache numericals timed |
| 11 | 7 Dec | COA II: I/O, DMA, pipelining. Probability. Databases I: ER, relational algebra | Pipeline + probability PYQs |
| 12 | 14 Dec | Databases II: SQL, FDs, normal forms, indexing, B+ trees, transactions | DBMS PYQs done |
| 13 | 21 Dec | Computer Networks (2027 syllabus only) | Subnetting, window size, delay numericals |
| 14 | 28 Dec | Theory of Computation | Closure/decidability table from memory |
| 15 | 4 Jan | Compiler Design; full diagnostic mock on 10 Jan | Every subtopic covered once |
| 16 | 11 Jan | Revision: two subjects a day + subject tests | Scoring 60%+ on subject tests |
| 17 | 18 Jan | Full mocks + analysis, weak-topic fixes | Each mock reviewed within 24 hours |
| 18 | 25 Jan | GATE 2024–2026 papers as timed mocks | Mock scores trending up |
| 19 | 1 Feb | Short-note revision, rest the day before | Calm and slept on exam eve |

If the CS paper lands on 13–21 Feb, stretch weeks 17–19 rather than learning anything new.

Day-by-day checklist for all 131 days: Daily planner

## Study material by subject

Use one lecture series to learn, one standard book to look things up, and PYQs to test. With 18 weeks you won't read the books cover to cover; open them only for chapters where the lectures felt thin.

| Subject | Learn from (free video) | Reference book | Topics that repeat in GATE |
| --- | --- | --- | --- |
| General Aptitude | Solve past GATE GA sections | R.S. Aggarwal, *Quantitative Aptitude* | Ratios, percentages, data interpretation, paper folding, analogies |
| Discrete Maths | Gate Smashers or Kiran Sir (YouTube); NPTEL Discrete Maths | Kenneth Rosen, *Discrete Mathematics and Its Applications* | Predicate logic, POSET/lattice, group properties, graph colouring, counting |
| Linear Algebra & Calculus | Gilbert Strang, MIT OCW 18.06 (selected lectures) | Strang, *Introduction to Linear Algebra* | Eigenvalues, rank, determinants, maxima–minima |
| Probability & Stats | NPTEL probability lectures | Sheldon Ross, *A First Course in Probability* | Bayes, expectation, binomial and Poisson |
| Digital Logic | Neso Academy (YouTube) | Morris Mano, *Digital Design* | K-maps, MUX functions, counters, IEEE 754 floats |
| COA | Gate Smashers / Ravindrababu Ravula (YouTube) | Hamacher, *Computer Organization* | Cache mapping, pipeline speedup, addressing modes, DMA |
| C & Data Structures | Any C refresher + Abdul Bari DS lectures | Kernighan & Ritchie, *The C Programming Language* | Pointer and recursion output, tree traversals, heap operations |
| Algorithms | Abdul Bari (YouTube); MIT OCW 6.006 | Cormen et al., *CLRS* | Recurrences, DP, Dijkstra/MST, sorting complexity |
| Theory of Computation | Neso Academy or Ravindrababu Ravula | Peter Linz, *Formal Languages and Automata* | Minimal DFA, closure properties, decidability |
| Compiler Design | Gate Smashers compiler playlist | Aho et al., *Compilers* (Dragon book) | FIRST/FOLLOW, LL(1)/LR tables, SDT, liveness |
| Operating System | Gate Smashers OS playlist | Silberschatz (Galvin), *Operating System Concepts* | Scheduling, semaphores, Banker's, paging and TLB numericals |
| Databases | Gate Smashers DBMS playlist | Korth (Silberschatz), *Database System Concepts* | Normal forms, SQL output, B+ tree order, serialisability |
| Computer Networks | Neso Academy / Gate Smashers CN | Kurose & Ross, *Computer Networking* | Subnetting/CIDR, sliding window, TCP congestion window, delays |

**Practice sources, in order of priority**

1. [GATE Overflow](https://gateoverflow.in/) — every CS PYQ since 1987 with discussed solutions, sorted by topic. Your main practice bank.
2. Official past papers and answer keys on the GATE website — use the 2024–2026 papers as timed mocks late in the plan.
3. One paid test series for full mocks (for example GO Classes, Made Easy or Applied Roots). Pick one; the brand matters less than reviewing every mock.
4. The GATE mock-test interface on the official site, to get used to the virtual calculator.

Every YouTube playlist, organised by week and subject: Video playlists

Every subject's YouTube playlist, plus PYQ solution videos: Video Playlists

## Practice, mocks and revision

The score comes from how you review mistakes, not from how many questions you attempt.

- **Short notes as you go:** one page per topic, only formulas, traps and question patterns. These become your whole revision material in weeks 15–19.
- **Error log:** for every wrong or guessed question, write the topic, why you got it wrong (concept, calculation, misread), and the fix. Reread it every Sunday.
- **PYQs by topic first, by year later:** solve topic-wise from GATE Overflow while learning; save the last three years' full papers for timed mocks.
- **Mock review:** spend as long reviewing a mock as taking it. Re-solve every wrong question without looking at the solution.
- **Spaced revision:** revisit each subject roughly 1 day, 1 week and 1 month after finishing it, using your short notes.
- **MSQ practice:** MSQs have no partial credit, so train yourself to check every option independently.

## Exam-day tactics

- **First pass (about 90 minutes):** do General Aptitude and every question you can solve confidently. Mark the rest.
- **Second pass:** long numericals and marked questions. NAT and MSQ carry no negative marks, so always answer them.
- **MCQ guesses:** guess only if you can eliminate at least two options; a blind guess costs 1/3 or 2/3 of a mark.
- **Calculator:** use the on-screen calculator only for arithmetic you can't do quickly by hand; it is slow.
- **Last 10 minutes:** check NAT answers for units and rounding, and make sure no NAT or MSQ is left blank.
- **Admit card:** download it in January and carry it with a valid photo ID; entry isn't allowed without it.
