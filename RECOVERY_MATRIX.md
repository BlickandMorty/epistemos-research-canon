# Recovery matrix

This is the separation between “worth publishing as research” and “ready to harden as a standalone project.”

| Family | Historical evidence | Source anchor | Classification | Public destination |
| --- | --- | --- | --- | --- |
| Lattice coordinate substrate | 707 KB / 5,749-line explainer; 122 substrate, 114 kernel, 86 deterministic, 74 EML, and 60 Scope-Rex references | `artifacts/lattice-coordinate-explainer/index.html`; history through `0bebe4644` | Research canon with live-system status annotations | this repo |
| Foundational Seven E1–E7 | natural-language theorem canon plus Lean specifications | `HELIOS_V5_DOC_6_THEOREM_CANON.md`; `lean/Epistemos/Epistemos/E*.lean` | E3 proof-bearing; E4/E5 mixed; remaining named frontier candidates | `epistemos-formal-primitives` |
| Operational H1–H17 | Lean specifications and falsifier protocols | `lean/Epistemos/Epistemos/H*.lean`; `Tools/falsifier/protocols` | open proof obligations | formal repo + this research record |
| Parameter Connectome PCF-1..10 | Lean specifications and product/research mapping | `lean/Epistemos/Epistemos/PCF_*.lean` | open proof obligations | formal repo |
| EML primitive | 241-line Rust operator with 21 unit tests; inverse and derivatives; Lean schema | `agent_core/src/research/eml/operator.rs`; `ccd17bd5` Lean port | working primitive, broader universality thesis open | `primitive-ir-lab` + formal repo |
| Geometry / Info / Operator / Scan / Tropical IRs | 41 Rust files across primitive IR family; generated Lean certificate samples | `agent_core/src/research/*_ir`; `5849ea03`, `ccd17bd5` | working research prototypes with proof-bearing schema lemmas and remaining assumptions | `primitive-ir-lab` + formal repo |
| Deterministic AI/runtime | Swift deterministic PRNG, substrate event paths, preflight and receipt doctrine | `Epistemos/Engine/DeterministicPRNG.swift`; `substrate-rt`; runtime preflight | working deterministic floor; “deterministic AI” ceiling remains research | `deterministic-agent-kernel` |
| Autogenous kernel identity | E7 theorem candidate and explainer architecture | E7, theorem canon, explainer sections | research candidate; not proved | formal repo + this repo |
| Scope-Rex / ACS admission | 21 ACS files, 21 Scope-Rex files, 539-line proof module, tests and audits | `agent_core/src/acs_admission`; `agent_core/src/scope_rex` | real prototype recovered and rebuilt as narrow engine | `scope-rex-admission` |
| Eidos closed citation | 21 Rust files; 421-line provenance verifier with 14 tests; detailed design | `agent_core/src/eidos`; Eidos design | working prototype, rebuilt as minimal honesty layer | `eidos-closed-citation` |
| F-ULP oracle | 282-line oracle, 298-line EML ULP module, Metal kernel, acceptance record | `agent_core/src/research/fulp_oracle`; `Epistemos/Shaders/fulp_oracle.metal` | working verification prototype | `f-ulp-oracle` |
| Lattice/WBO register | 21 files; 843-line register and dedicated falsifier tests | `agent_core/src/lattice_wbo` | working prototype, narrower standalone ledger | `lattice-wbo-ledger` |
| Hyperdynamic schema loop | diff/repair research plus bounded runtime repair modules | `agent_core/src/research/hyperdynamic_schemas`; `agent_core/src/hyperdynamic_loop` | working bounded primitive; autonomous ceiling open | `hyperdynamic-schema-repair` |
| Vault Recall 50 | 1,037-line runner, deterministic fixture, integration tests | `agent_core/src/storage/f_vault_recall_runner.rs` | working benchmark concept | `vault-recall-benchmark` |
| Substrate independence | 662-line implementation and 31 tests | `agent_core/src/research/substrate_independence.rs` | working experimental metric; deserves later dedicated extraction | queued research/build candidate |
| Ternary / Sherry lattice | 11 ternary modules, E8/Leech/sparse-ternary codebooks | `agent_core/src/research/ternary`; `research/sherry_lattice` | promising research prototype, hardware/quality claims need dedicated benchmarks | queued research/build candidate |
| Residency / active assembly / cache-lineage | extensive explainer, falsifier bundles, and integration records | explainer + `docs/falsifiers/F-*RESIDENCY*` | architecture plus partial prototypes | research canon; future benchmark repo |
| Falsifier doctrine | hundreds of protocols, audits, evidence envelopes, and release gates | `Tools/falsifier`; `docs/falsifiers` | reusable methodology, corpus needs curation before wholesale publication | research canon; future protocol toolkit |
| Proof-carrying security pipeline | Epistemos admission receipts + clean-room study of Shannon/OpenAEV orchestration | standalone original code and `INSPIRATION.md` | working defensive authorized lab; no exploit execution | `proof-carrying-security-lab` |

## Easy public wins already extracted

The research archive, formal package, and nine working standalone repos were selected because each has a narrow contract, testable behavior, and a clear line back to the historical work or the documented clean-room security study. The queued candidates are good ideas, but they need more benchmark or dependency cleanup before they should be presented as hardened projects.

## Origin commits and refs worth preserving

- `ccd17bd5244c48bdc7b7f268e8d1a34770bd03d2` — primitive IR Lean schema custody
- `5849ea03053d54da11561a35cddd839cd2595066` — architecture checkpoint preserving Rust primitive work
- `6eecb11517c9689644143ef79a5012c284e52733` — EML closure research slice
- `bb42cf9f14f8b4671bd5a5a8328a14c089c2e819` — Lean custody status
- `origin/codex/t21-vault-recall-contract-2026-05-18` — Vault recall / ACS / Eidos / lattice checkpoint
- `origin/codex/research-snapshot-2026-05-08` — early theorem/research snapshot
- `origin/salvage/T5-*` and `origin/salvage/T7-*` — primitive IR salvage lines
- `origin/phase2-terminal-s-hyperdynamic-loop-2026-05-24` — bounded schema loop line
