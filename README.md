# epistemos-research-canon

This is the research layer I did not want to lose when Epistemos changed direction.

The center of the repo is the long [lattice coordinate explainer](explainer/index.html): 5,749 lines covering the typed coordinate substrate, autogenous kernel, deterministic runtime, EML, Scope-Rex, Eidos, lattice/WBO accounting, residency, theorem families, falsifiers, and the line between the floor and the research ceiling.

I am publishing it as research, not quietly turning every heading into a product claim.

## What is here

- the full lattice-coordinate explainer
- E1–E7 / H1–H17 theorem canon
- unified substrate and Scope-Rex plans
- deterministic runtime preflight
- Eidos closed-citation design
- F-ULP and F-Vault-Recall witness contracts
- ACS admission-field design
- EML/Lean/substrate audits
- newer primitive-upgrade research

## How to read it

The documents use four different kinds of statement. I keep them separate in [RECOVERY_MATRIX.md](RECOVERY_MATRIX.md):

- recovered working source
- typed/formal source with proof terms
- theorem candidate or open proof obligation
- architecture/research proposal

The existence of a design document does not mean the entire design shipped. The standalone implementation repos are where I put the pieces that now have focused code, tests, and CI.

## Why keep unfinished research public

Some of the most useful work here is not a finished theorem or library. It is the vocabulary, the failure conditions, the falsifiers, and the way multiple systems were being connected. I would rather publish that honestly than erase it or dress it up as finished.

## Provenance

Recovered from the regular `BlickandMorty/Epistemos` repository, not `Epistemos-RETRO`. The snapshot here comes from Epistemos main commit `987f0a976` with earlier source anchors listed in the recovery matrix. All copied material is from my own project history.

