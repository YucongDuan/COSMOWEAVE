# COSMOWEAVE

**Causal-Tuning World Model and Life-Futures Simulator**

COSMOWEAVE is an offline research system for studying a core hypothesis:
worlds are not defined by raw information volume, but by the selective alignment
between physical propagation modes and causally effective information flow. Life is
modeled as a local process that maintains and rewrites the channels selecting its own
future. Consciousness-related organization is treated as a stronger, consequence-bearing
form of reliable global routing, not as a language claim.

## 1. Project overview

The project contains three linked experiments:

1. **Informational tuning field** - compares awake-like directional routing with
   anesthesia-like diffuse information flow. The diffuse condition can carry more total
   transfer entropy while having much lower directional tuning and reliability.
2. **Adaptive world model** - predicts a world whose states and transition rules both
   change. Variants compare a fixed model, a feature-growing model, and a rule-rewriting
   model.
3. **Life futures simulator** - runs eight architectures across six environmental regimes
   and identifies synthetic attractors such as noise saturation, locked optimization,
   self-rewriting hybrid life, distributed collective life, and cosmic channel engineering.

## 2. Core problem

Most world models predict the next state inside a fixed state space under fixed rules.
Open-ended life changes its boundaries, variables, learning rules, and environment. A
world model for life therefore has to model both state transitions and rule transitions.

## 3. Key innovations

- separates information quantity from directional causal reliability;
- represents world dynamics as propagation plus mutable constraints;
- allows state-space growth when persistent residuals cannot be expressed;
- allows learning rules to become objects of learning;
- compares survival, tuning, model accuracy, future openness, and lineage change without
  collapsing them into one universal life score;
- preserves a hard evidence boundary: no simulation result certifies phenomenal consciousness.

## 4. System architecture

```text
physical field
  -> directional information routing
  -> adaptive state-and-rule world model
  -> local constraint reconstruction
  -> life architecture experiments
  -> future attractor analysis
  -> evidence ledger and run proof
```

## 5. Directory structure

```text
src/cosmoweave/       package source
outputs/              deterministic reference results
docs/figures/         original figures
tests/                 automated tests
schemas/               JSON schema
examples/              example configuration
studio/                offline interactive report
run_demo.py            run the full reference suite
run_tests.py           run automated tests
```

## 6. Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

Or install the wheel from `dist/`.

## 7. Quick start

```bash
python run_demo.py
```

The command writes JSON and CSV results to `outputs/`.

## 8. Command examples

```bash
python -m cosmoweave --output outputs --seeds 12
python run_tests.py
```

## 9. Input and output formats

Input configuration is JSON. Outputs include:

- `field_results.json`
- `world_model_results.json`
- `life_future_results.json`
- `metrics.json`
- `ledger.json`
- `run_proof.json`
- summary CSV files

## 10. Configuration

Edit `examples/default_config.json` or pass the number of life-future seeds on the command line.

## 11. Test instructions

```bash
python run_tests.py
```

Expected result: all tests pass.

## 12. Reproducibility

All reference runs use explicit deterministic seeds. `run_proof.json` records SHA-256 hashes
for the major output files. `ledger.json` contains a hash-chained experiment history.

## 13. Evidence boundaries

The system demonstrates mechanisms in synthetic worlds. It does **not** prove:

- that informational tuning is sufficient for consciousness;
- that the universe is literally an information field;
- that synthetic attractor frequencies are real-world probabilities;
- that any reference process has subjective experience;
- that cosmic-scale life will necessarily emerge.

## 14. Limitations

- transfer entropy is estimated after coarse discretization;
- the physical field is a small toroidal grid;
- life futures use abstract architectures rather than molecular or astrophysical simulation;
- calendar horizons in the report are conditional interpretations, not calibrated forecasts;
- no external API, robot, network, shell, or autonomous deployment is included.

## 15. Security and privacy

The project is offline and uses only synthetic data. It has no network or credential interface.

## 16. Governance

Metric changes require a versioned definition, counterexample, migration note, deterministic
regression test, and explicit downgrade of any affected prior claim.

## 17. Contribution guide

See `CONTRIBUTING.md`.

## 18. License

Apache-2.0.

## 19. Changelog

See `CHANGELOG.md`.

## 20. Citation

See `CITATION.cff`.

## Reference run snapshot

- field runs: 8
- adaptive world-model runs: 15
- life-future runs: 96
- ledger verified: True
- phenomenal claim: NOT_CERTIFIED
