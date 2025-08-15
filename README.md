# Reality Codex Project

The Reality Codex is an interactive knowledge web for the Local Informational Universe Hypothesis (LIUH). It combines rigorous physics and information theory with clear mechanisms for how perception renders a shared world. The site is built with MkDocs Material and auto-published with GitHub Pages.

**Live site:** https://YOUR_USERNAME.github.io/reality-codex-site/  
*(replace YOUR_USERNAME after Pages is live)*

---

## Browse the Codex

The Codex lives under the `docs/` folder and is published as a website with sidebar navigation and search. Start at the homepage:

- [Home](docs/index.md)

Core topics already defined or in progress:

- [Hilbert Rendering Zone](docs/hilbert-rendering-zone.md)
- [Informational Substrate](docs/informational-substrate.md)
- [Quasi-crystalline Structure](docs/quasicrystalline-structure.md)
- [Bose-Einstein Condensate](docs/bose-einstein-condensate.md)
- [Informational Collapse Hierarchy](docs/informational-collapse-hierarchy.md)
- [Entanglement](docs/entanglement.md)
- [Wave Function Collapse](docs/wave-function-collapse.md)
- [Reductionist Point of View](docs/reductionist-point-of-view.md)
- [Nested HRZ Model](docs/nested-hrz-model.md)
- [Codex Interaction Models](docs/codex-interaction-models.md)

---

## Planned sections (add as separate pages)

These are all the subjects we expect to include so a visitor can get the *entire* book from the Codex. Create each page in `docs/` with the exact filename shown, then add it to `mkdocs.yml` under `nav:`.

### Mechanisms and math
- [Coherence](docs/coherence.md)
- [Probability and the Born Rule](docs/probability-and-born-rule.md)
- [Decoherence and Environment as Witness](docs/decoherence-and-environment-as-witness.md)
- [Quantum Darwinism](docs/quantum-darwinism.md)
- [Open Quantum Systems](docs/open-quantum-systems.md)
- [Measurement Theory POVM and CPTP Maps](docs/measurement-theory-povm-cptp.md)
- [Non-Markovian Dynamics](docs/non-markovian-dynamics.md)
- [Indefinite Causal Order](docs/indefinite-causal-order.md)
- [Temporal Entanglement](docs/temporal-entanglement.md)
- [Delayed-choice and Quantum Eraser](docs/delayed-choice-and-eraser.md)
- [Wigners Friend Scenarios](docs/wigners-friend.md)
- [Quantum Zeno Effect](docs/quantum-zeno-effect.md)
- [Holographic Principle](docs/holographic-principle.md)
- [AdS CFT Duality](docs/ads-cft-duality.md)
- [Holographic Error Correction](docs/holographic-error-correction.md)
- [Tensor Networks and MERA](docs/tensor-networks-mera.md)
- [E8 and Penrose Connections](docs/e8-and-penrose.md)
- [Quasicrystal Geometry Deep Dive](docs/quasicrystal-geometry-deep-dive.md)

### HRZ and consciousness
- [HRZ Brain Interface](docs/hrz-brain-interface.md)
- [Predictive Processing and Priors](docs/predictive-processing-and-priors.md)
- [Memory Rendering and Drift](docs/memory-rendering-and-drift.md)
- [Anticipation and Pre-render](docs/anticipation-and-pre-render.md)
- [Multi-HRZ Synchronization](docs/multi-hrz-synchronization.md)
- [Collective Rendering](docs/collective-rendering.md)
- [Ethics and Safety](docs/ethics-and-safety.md)

### Biology and information
- [Levinthal Paradox](docs/levinthal-paradox.md)
- [Funneled Energy Landscapes](docs/funneled-energy-landscapes.md)
- [AlphaFold and Structure Prediction](docs/alphafold-and-structure-prediction.md)
- [Bioelectric Patterning](docs/bioelectric-patterning.md)
- [Quantum Biology Evidence](docs/quantum-biology-evidence.md)

### Cosmology and gravity
- [Black Hole Rendering Engine](docs/black-hole-rendering-engine.md)
- [ER EPR and Entanglement Geometry](docs/er-epr-and-entanglement-geometry.md)
- [Arrow of Time as Statistical Emergence](docs/arrow-of-time-statistical-emergent.md)
- [Cosmological Constant and Information](docs/cosmological-constant-and-information.md)
- [Variable Physical Constants](docs/variable-constants.md)
- [Multiverse and Interface Models](docs/multiverse-and-interfaces.md)

### Comparative frameworks
- [Copenhagen Interpretation](docs/copenhagen-interpretation.md)
- [Many Worlds](docs/many-worlds.md)
- [QBism](docs/qbism.md)
- [Relational Quantum Mechanics](docs/relational-quantum-mechanics.md)
- [Objective Collapse Models](docs/objective-collapse-models.md)
- [Integrated Information Theory](docs/integrated-information-theory.md)
- [Orch OR](docs/orch-or.md)
- [Emergence and Effective Field Views](docs/emergence-and-effective-fields.md)
- [Constructor Theory](docs/constructor-theory.md)
- [Holography vs LIUH](docs/holography-vs-liuh.md)
- [Simulation Analogy vs LIUH](docs/simulation-analogy-vs-liuh.md)
- [Hoffman Interface Theory](docs/hoffman-interface-theory.md)

### Experiments and falsifiability
- [Experimental Hooks Overview](docs/experimental-hooks.md)
- [QRNG Influence Protocol](docs/qrng-influence-protocol.md)
- [Double Session Feedback Test](docs/double-session-feedback-test.md)
- [Codex Mediated Coherence Tests](docs/codex-mediated-coherence-tests.md)
- [Timing Offsets in Entanglement](docs/timing-offsets-in-entanglement.md)
- [Perception Latency Assays](docs/perception-latency-assays.md)
- [Closed Loop Rendering Trials](docs/closed-loop-rendering-trials.md)

### Tools and resources
- [Glossary](docs/glossary.md)
- [FAQ](docs/faq.md)
- [Diagrams and Figures](docs/diagrams-gallery.md)
- [References](docs/references.md)
- [Changelog](docs/changelog.md)
- [Contribution Guide](docs/contribution-guide.md)

---

## Repository structure

- `mkdocs.yml`  site navigation and theme config  
- `docs/`  all content pages  
- `.github/workflows/deploy.yml`  GitHub Actions workflow that builds and publishes the site

Live site builds automatically on each push to `main`. If a link 404s check that the filename in `docs/` matches the `mkdocs.yml` entry exactly.

---

## How to add a new page

1. Create a new file in `docs/` using lowercase and hyphens, for example `docs/coherence.md`.  
2. Put at least a header so the build can succeed:
