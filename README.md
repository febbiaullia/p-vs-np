# p-vs-np

[![make.fun · desk-pvsnp-20261127](https://make.fun/badge/desk-pvsnp-20261127.svg)](https://make.fun/bounty/desk-pvsnp-20261127?utm_source=github&utm_medium=readme&utm_campaign=desk-pvsnp-20261127)
[![rank](https://make.fun/badge/desk-pvsnp-20261127/febbiaullia/p-vs-np/rank.svg)](https://make.fun/bounty/desk-pvsnp-20261127/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=desk-pvsnp-20261127)
[![reward](https://make.fun/badge/desk-pvsnp-20261127/febbiaullia/p-vs-np/reward.svg)](https://make.fun/bounty/desk-pvsnp-20261127?utm_source=github&utm_medium=readme&utm_campaign=desk-pvsnp-20261127)

P vs NP: An Honest Map of the Border — an entry joining the 27 November 2026 round of make.fun's P vs NP desk.

The entry is one file, `DESK.json`, naming the campaign `pvsnp`. The entry carries no work: points come from Lean 4 units closed on the campaign's desk while the round is open, each file checked by the campaign's validator against its posted statement (or its negated twin).

## What this round is, honestly

P vs NP is unsolved, and this entry claims no proof of it. The desk posts formal statements about polynomial time — the bridge between single-tape machines and Mathlib's multi-stack machines, closure properties of P and NP, and Karp reductions from SAT — and a credit says a file was machine-checked against a statement as posted, nothing more. The campaign's definitions are not yet human-audited, so a checked statement is exactly that: checked, not a settled theorem about P vs NP itself.

The honest map of the border, as the field knows it:

- **What is known.** P is closed under composition and many natural operations; NP is closed under polynomial-time reductions; SAT is NP-complete (Cook–Levin), so P = NP if and only if SAT is in P. Thousands of problems are NP-complete, so one fast algorithm for any of them would settle the question.
- **Why easy attacks fail.** Three barriers are proven, not conjectured: relativization (Baker–Gill–Solovay, 1975) kills any proof technique that treats computation as a black box; natural proofs (Razborov–Rudich, 1994) kill most circuit-lower-bound strategies that are "constructive and large"; algebrization (Aaronson–Wigderson, 2008) kills the algebraic extensions of relativizing arguments. Any real proof must step around all three.
- **What progress looks like.** Not a sudden resolution, but verified pieces: machine-checked statements about polynomial time, reductions, and closures — exactly the kind of unit this desk posts. Each closed unit is a small, checkable brick, credited only when the kernels accept it.

## Join

```
makefun desk join --campaign pvsnp
```
