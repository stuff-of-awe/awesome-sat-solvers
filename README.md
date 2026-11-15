<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome SAT solvers and SAT proof certificates

Modern CDCL SAT solvers, benchmark instances, proof formats and verification chains. A SAT model, UNSAT derivation and checked certificate require different evidence.

**Status:** starter collection, 2026-11-15. Curator: unassigned. These are independently written short annotations of external resources; no benchmark, integration, solver invocation or checker execution has been performed for this starter.

## Learn and get started

- [CaDiCaL](https://github.com/arminbiere/cadical) — A modern CDCL SAT engine with proof and solver interfaces.
- [Kissat](https://github.com/arminbiere/kissat) — An efficient SAT solver; compare configurations and proof output before benchmarking.
- [MiniSat](https://github.com/niklasso/minisat) — Classic reference solver with influential CDCL engineering.

## References and implementations

- [CryptoMiniSat](https://github.com/msoos/cryptominisat) — SAT solving with XOR-awareness and additional interfaces.
- [SAT Live solver index](https://www.satlive.org/solvers/) — Discover other solvers, licences and links; verify entry freshness.
- [SAT Competition](https://satcompetition.github.io/2026/output.html) — Locate current certification and benchmark pipelines; categories and rules change.

## Benchmark, examples and community paths

- [CakeML verified proof checkers](https://www.cakeml.org/checkers.html) — Find mechanised LPR/CakePB checking work and stated proof boundaries.
- [VeriPB](https://veripb.org/) — Pseudo-Boolean proof ecosystem, distinct from ordinary CNF SAT.

## First exercise — not executed here

For a tiny DIMACS CNF, request both a satisfying assignment and an unsatisfiability proof on separate test instances; check the model and replay a proof only with compatible checker and format.

## Evidence and interoperability

Never equate 'UNSAT' exit code with a checked proof. Track CNF preprocessing, certificate conversions, assumptions, output format, checker version and the actual theorem proved about the checker.

Capture provenance (source commit, tool and checker versions, flags, inputs, assumptions, certificate formats, output status, elapsed time, licence) before using an entry in a research/assurance claim.

## Upstream survey, curation and contribution

A preliminary survey on 2026-11-15 compared broader resources such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification), [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources), plus canonical projects above. This is not an exhaustive survey and no external descriptions were imported. The focused value here is evidence-aware navigation and links from the [ECHIDNA coverage ledger](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc). Inclusion is not an endorsement, and upstream materials retain their respective licences.

Contribute fixes and additional learning material through an [issue](https://github.com/stuff-of-awe/awesome-sat-solvers/issues) or [PR](https://github.com/stuff-of-awe/awesome-sat-solvers/pulls); see [maintenance policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Original annotations are CC-BY-SA-4.0. Collectors and maintainers are invited; quarterly review is a goal, not evidence of actual review.
