# PYQ Analysis: GATE CS 2021–2026 vs the 2027 Syllabus

In GATE CS papers from 2021 to 2026, almost every question falls inside the 2027 syllabus. Only 1 of 525 CS questions clearly depended on a topic the revision removed, and at most 5 more might have. What you need beyond the syllabus text is depth on a small set of things GATE keeps asking, listed below, plus extra practice on the four 2027 additions that recent papers rarely test.

## What was analysed

I went through every question in 10 papers, 620 questions in total, using the topic tags on GATE Overflow. Each question was then mapped to a section of the official 2027 syllabus.

| Paper | Questions covered |
| --- | --- |
| 2021 Set 1, 2021 Set 2 | 65 + 65 (complete) |
| 2022, 2023 (one set each) | 65 + 65 (complete) |
| 2024 Set 1 | 35 of 65 (one page of the question list couldn't be read) |
| 2024 Set 2 | 65 (complete) |
| 2025 Set 1, 2025 Set 2 | 65 + 65 (complete) |
| 2026 Set 1, 2026 Set 2 | 65 + 65 (complete) |

Marks per subject use the 9 complete papers only. Topic counts use all 620 questions. Subject totals can differ by 1–2 marks from coaching-institute tables, because some questions sit between two subjects (a heap question can count as Data Structures or Algorithms). As a cross-check, my question-type counts match the published ones for 2023 (34 MCQ, 15 MSQ, 16 NAT) and 2026 Set 2 (11 MSQ, 19 NAT).

## Where the marks come from

&#91;embedded content: GATE Overflow topic tags · 9 complete papers, 2021–2026\]

No single CS subject is worth more than about 9 marks on average, so every one of them matters. The engineering maths subjects together average 15 marks, about the same as General Aptitude. Discrete Maths and Algorithms swing the most from paper to paper, by as much as 7–10 marks.

## Topics asked almost every year

These 16 topics showed up in at least 7 of the 10 papers. Treat them as near-certain questions: master every question type on each, not just the concept.

| Topic | Subject | Papers (of 10) | Marks across all 10 papers | What the questions look like |
| --- | --- | --- | --- | --- |
| Number representation, 2's complement, IEEE 754 | Digital Logic | 10 | 21 | Range and overflow, converting to or from IEEE 754 bit patterns, Booth's multiplication |
| TCP | Computer Networks | 10 | 19 | Congestion window after timeouts, sliding-window sizes, sequence numbers, handshake |
| CPU scheduling | Operating System | 10 | 15 | Gantt chart then average waiting/turnaround time; SRTF and round robin most common |
| C output tracing | Programming & DS | 9 | 26 | Pointers, arrays, strings, recursion, static variables: predict the printed value |
| Pipelining | COA | 9 | 17 | Cycles for n instructions with stalls, speedup, hazards and forwarding |
| Normalisation and FDs | Databases | 9 | 16 | Candidate keys, highest normal form, lossless and dependency-preserving decomposition |
| Cache memory | COA | 8 | 26 | Tag/index/offset bits, hit/miss sequences, multi-level average access time |
| Finite automata | Theory of Computation | 8 | 18 | States in the minimal DFA, which strings or languages a DFA accepts |
| Syntax-directed translation | Compiler Design | 7 | 12 | Evaluate an SDT on an input, S- vs L-attributed |
| Minimum spanning trees | Algorithms | 7 | 15 | MST weight, uniqueness, effect of changing edge weights, MST vs shortest path |
| Time complexity of code | Algorithms | 7 | 12 | Complexity of loops or recursive code, comparing growth rates |
| Binary search trees | Programming & DS | 7 | 12 | Tree after insertions, traversal orders, number of possible BSTs |
| Transactions and concurrency | Databases | 7 | 12 | Conflict serialisability, recoverability, 2PL |
| Boolean algebra and K-maps | Digital Logic | 7 | 10 | Minimal SOP, number of prime implicants, functional completeness |
| Matrices and eigenvalues | Linear Algebra | 7 | 14 | Eigenvalue properties, determinant, rank, solutions of linear systems |
| Context-free languages | Theory of Computation | 7 | 15 | Is a language regular, CFL or neither; closure properties |

Cache memory and C output tracing carry the most marks of any single topic (26 each across the 10 papers). Both are numerical or tracing questions, so they reward speed built from practice, not reading.

## How each subject is asked

The question format differs a lot by subject, and it should change how you practise.

| Subject | MSQ share | NAT share | What it means for practice |
| --- | --- | --- | --- |
| Theory of Computation | 44% | 13% | Multi-correct statements on closure and decidability. Know the full closure/decidability tables cold; one wrong tick loses the whole question |
| Operating System | 42% | 38% | Both statement-checking and numericals. Practise "which of these are true" on synchronisation and paging |
| Discrete Maths | 40% | 27% | Statement-heavy on functions, relations, groups and graphs. Learn counter-examples |
| Digital Logic | 37% | 21% | Statements about number systems and Boolean functions |
| COA | 17% | 48% | Mostly numerical. Drill cache, pipeline and instruction-format calculations with the on-screen calculator |
| Programming & DS | 14% | 38% | Tracing code to an exact number. Always dry-run on paper |
| Probability, Calculus | 11–23% | 47–54% | Numerical answers; show every step, since there are no options to check against |

Shares are of all CS questions in that subject across the 10 papers. There is no negative marking on MSQ or NAT, so never leave those blank.

### Trends to plan around

&#91;embedded content: GATE Overflow topic tags · 9 complete papers, 2021–2026\]

- **Maths is shifting away from discrete maths.** It fell from 13 marks in 2022 to 3–4 in 2025 Set 2 and 2026 Set 2. Calculus rose to 3 marks in both 2026 papers after 1–2 marks in every earlier paper. Don't skip calculus and probability because they look small.
- **MSQs are rising, unevenly.** 2026 Set 1 had 24 MSQs, the most of any paper analysed, against 11 in 2026 Set 2. Plan for either extreme.
- **COA has grown**, from 5–6 marks in 2021 to 8–11 in 2025–2026, mostly cache and pipelining numericals.
- **Algorithms swings the most** (6 to 13 marks), so a weak algorithms base is the biggest risk on a bad day.

## What to learn beyond the syllabus text

The syllabus names broad areas, and GATE asks specific skills inside them that the text never mentions. These 10 came up in recent papers and weren't in your planner yet. Each is now added to the day shown.

| Add this | Where it was asked | What to be able to do | Planner day |
| --- | --- | --- | --- |
| Byte ordering (little- vs big-endian) | 2021 Set 2, 2-mark MSQ | Say which byte sits at which address for a multi-byte value, and read a value back from memory | Wed 25 Nov |
| Hamming code | 2021 Set 1, 2 marks | Place parity bits, find and correct a single-bit error | Tue 22 Dec |
| Probability applied to networks | 2025 Set 1, 2-mark NAT | Success/collision probability for stations sending in a slot, expected number of attempts | Wed 23 Dec |
| Disk structure and access time | 2024 Set 2, 2026 Set 1, both 2-mark NAT | Seek + rotational latency + transfer time, disk capacity, sector addressing. "Secondary storage" left the COA text, but disks are still asked through OS I/O scheduling | Thu 19 Nov |
| Backpatching | 2025 Set 2, 1 mark | Fill jump targets for Boolean expressions and control flow in three-address code | Fri 8 Jan |
| Operator-precedence parsing | 2024 Set 1, 1-mark NAT | Build precedence relations, parse a string step by step | Wed 6 Jan |
| Eigenvalue multiplicity | 2026 Set 1, 1 mark | Algebraic vs geometric multiplicity, when a matrix is diagonalisable | Sat 21 Nov |
| Counting super keys | 2026 Set 1, 2-mark NAT | Count super keys from the candidate keys using inclusion–exclusion | Tue 15 Dec |
| Modified binary search | 2025 Set 2, 2 marks (bitonic array) | Search bitonic and rotated sorted arrays in O(log n) | Wed 28 Oct |
| "What does this code compute?" | 2021 Set 1 and Set 2 (3 questions) | Trace an unfamiliar function on small inputs until you see the pattern (GCD, sum of digits, reversal, and so on) | Fri 16 Oct, plus one per Sunday test |

One more pattern to prepare for: **GATE sometimes defines a new term inside the question** and asks you to apply it. 2026 Set 2 defined a Jaccard coefficient on graph neighbourhoods. Read these slowly and try the definition on a tiny example first.

The PYQs also confirm that these less-obvious planner items are worth their day: Booth's multiplication (2025 Set 2), Huffman codes (2021 Set 2), stop-and-wait and sliding-window efficiency (4 papers), double hashing and linear probing (2025, 2026), balls-in-bins counting (2022), symbol tables (2025 Set 1) and graph matching (2026 Set 1).

## 2027 additions with few recent PYQs

Four topics added or spelled out in the 2027 syllabus were barely tested from 2021 to 2026, so recent papers won't give you enough practice on them. The syllabus now names them explicitly, so prepare them fully anyway, using older papers and textbook exercises.

| Topic | Recent PYQs (2021–2026) | Where to practise |
| --- | --- | --- |
| Control unit design: hardwired and microprogrammed | None | Older GATE: CSE 1996, 1997, 1999, 2002, 2004 (Q67), 2013 (Q28); GATE IT 2004, 2005 (two questions), 2006, 2008. Control-word size, horizontal vs vertical microinstructions, control memory size |
| Memory interfacing | 1 (2023, 2 marks) | Number of chips for a given memory, address lines, chip-select decoding, interleaving; Hamacher's memory chapter exercises |
| ALU and datapath design | 1 (2025 Set 1, datapath MSQ) | Micro-operations for an instruction on a single-bus datapath, control signals per step |
| Tabular (Quine–McCluskey) minimisation | None | Work 4–5 functions fully by hand, including prime implicant charts; Morris Mano chapter 3 exercises |

Design of sequential circuits, also emphasised in 2027, is already well covered by recent papers: counters or flip-flops appeared in 2021 Set 1, 2023, 2025 Set 1, 2025 Set 2 and 2026 Set 1.

## What to skip in old PYQs

The 2027 revision mostly trimmed Computer Networks. When you practise from GATE Overflow, skip questions whose main topic is one of these:

- **Computer Networks:** UDP, ARP, DHCP, ICMP, SMTP, FTP and email, framing, bridging, and flooding as a routing method. In 2021–2026 only one question clearly depended on these (ARP alongside TCP, 2025 Set 2, 1 mark). Five more were tagged only as general network or application-layer protocol questions (2021 Set 1, 2022, 2024 Set 1, both 2026 papers), so check each before skipping it.
- **COA:** questions purely about secondary-storage devices under COA. Keep disk access time and disk scheduling, which are still part of OS.

Everything else in the 2021–2026 papers is still examinable, so all other PYQs from these years are useful practice.

## Changes made to your daily planner

- Added the 10 skills from "What to learn beyond the syllabus text" to their days.
- Added control-unit, memory-interfacing and tabular-method practice from older papers to Thu 3 Dec, Fri 4 Dec and Fri 27 Nov.
- Sunday tests now include one "what does this code compute?" question and a check of every MSQ option.

## Sources

- GATE Overflow question lists by paper: [2021 Set 1](https://gateoverflow.in/tag/gatecse-2021-set1), [2021 Set 2](https://gateoverflow.in/tag/gatecse-2021-set2), [2022](https://gateoverflow.in/tag/gatecse-2022), [2023](https://gateoverflow.in/tag/gatecse-2023), [2024 Set 1](https://gateoverflow.in/tag/gatecse2024-set1), [2024 Set 2](https://gateoverflow.in/tag/gatecse-2024-set2), [2025 Set 1](https://gateoverflow.in/tag/gatecse2025-set1), [2025 Set 2](https://gateoverflow.in/tag/gatecse2025-set2), [2026 Set 1](https://gateoverflow.in/tag/gatecse-2026-set1), [2026 Set 2](https://gateoverflow.in/tag/gatecse-2026-set2)
- [GATE Overflow microprogramming questions](https://gateoverflow.in/tag/microprogramming) (older control-unit PYQs)
- [GATE 2027 CS syllabus, IIT Madras](https://gate2027.iitm.ac.in/static/doc/GATE2027_Syllabus/CS_GATE2027_Syllabus.pdf)
- Cross-checks: [GO Classes 2023–2025 weightage analysis](https://www.goclasses.in/blog/a-strategic-analysis-of-subject-wise-weightage-trends-in-gate-cse-2023-2025), [GeeksforGeeks GATE CSE 2026 Shift 2 analysis](https://www.geeksforgeeks.org/gate/gate-cse-2026-shift-2-comprehensive-paper-analysis-with-answer-key/)
