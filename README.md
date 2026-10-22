# DSA Practice

[![CI](https://github.com/Rmuk655/DSA-Practice/actions/workflows/ci.yml/badge.svg)](https://github.com/Rmuk655/DSA-Practice/actions/workflows/ci.yml)

C++ solutions to competitive-programming and interview problems. This repository combines the former `Codeforces-Solutions` and `LeetCode-Solutions` repositories; the history of both is kept.

| Folder | Contents | Profile |
|---|---|---|
| [`Codeforces/`](Codeforces) | 34 solutions across 12 contests, indexed by contest with a link to each problem | [muk_r1](https://codeforces.com/profile/muk_r1) |
| [`LeetCode/`](LeetCode) | 28 problems grouped by technique (graphs, dynamic programming, binary search, trees, arrays and greedy); each folder has the problem statement and the solution | [rmuk](https://leetcode.com/u/rmuk/) |

These are selected solutions, not a full record of activity; the profiles above show everything solved.

## Building

- **Codeforces:** every file is a complete program. Compile one with `g++ -std=c++17 Codeforces/2264A_Rumb_Needs_a_Hand.cpp`. CI checks that all of them compile (`g++ -std=c++17 -fsyntax-only`).
- **LeetCode:** each file contains only the `Solution` class that is submitted to the judge, so it does not compile on its own and CI does not cover it.
