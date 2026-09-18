# Aeshma-Daeva

I build stateful AI and decision systems that preserve provenance, distinguish
observation from inference, update conclusions under conflicting evidence, and
constrain action to what the current evidence supports.

My current research line connects recurrent-state engineering, controlled
experimentation, and evidence-bounded system design. The projects below are
separate artifacts with explicit boundaries rather than one monolithic agent.

## Research map

| Project | Engineering question | What to inspect |
| --- | --- | --- |
| [Demian Substrate](https://github.com/Aeshma-Daeva/Demian-Substrate) | What state must be preserved for a recurrent system to continue the same trajectory after interruption? | Explicit state channels, deterministic checkpoint/restore, surface-only controls, ablations, and non-semantic audio probes. |
| [Demian Lab](https://github.com/Aeshma-Daeva/Demian-Lab) | Which architectural claims survive controlled experiments and negative results? | EEG-derived observer trajectories, perturbation studies, well-log sequence adaptation, evidence summaries, and claim limits. |
| [Demian EEG](https://github.com/Aeshma-Daeva/Demian-EEG) | Does temporal order and complete hidden state measurably affect continuation under an EEG-like signal stream? | Synthetic fixture, spectral adapter, shuffled-order comparison, full-state restore, and surface-only control. |
| [Demian Geo](https://github.com/Aeshma-Daeva/Demian-Geo) | Can the same substrate process a different sequential domain without crossing group or future-information boundaries? | Per-well reset, row provenance, group-aware evaluation helper, and explicit no-lift claim. |
| [Zenith Epistemic Runtime](https://github.com/Aeshma-Daeva/Zenith-Epistemic-Runtime) | How should changing evidence constrain belief standing and action authority? | Typed justification lifecycle, contradiction, refresh, fail-closed authority, append-only history, and deterministic restore. |
| [NullFrame](https://github.com/Aeshma-Daeva/NullFrame) | How can a reviewer move from a concept to the code, control, and evidence behind it? | An authored project atlas linking recurrent state, memory, ablations, restore controls, and canonical sources. |

## Shared method

- Keep raw observation separate from interpretation and risk.
- Treat confidence as an estimate, not execution authority.
- Preserve provenance, contradictions, null results, and failed branches.
- Use restore controls and ablations to test whether a mechanism is causal.
- Label historical, synthetic, local, and held-out evidence separately.
- Prefer a narrow reproducible claim over a broad architectural story.

The work does not infer consciousness, identity, agency, or understanding from
state continuity, channel names, or model behavior. Those terms require evidence
that the current projects do not claim to provide.

## Suggested review order

1. Start with the [Demian Substrate README](https://github.com/Aeshma-Daeva/Demian-Substrate#readme) and its full-state versus surface-only restore control.
2. Run [Demian EEG](https://github.com/Aeshma-Daeva/Demian-EEG) or [Demian Geo](https://github.com/Aeshma-Daeva/Demian-Geo) to inspect two bounded, heterogeneous adapters.
3. Inspect [Zenith Epistemic Runtime](https://github.com/Aeshma-Daeva/Zenith-Epistemic-Runtime) for the explicit transition from evidence standing to action authority.
4. Continue to the [Demian Lab case studies](https://github.com/Aeshma-Daeva/Demian-Lab/blob/main/docs/CASE_STUDIES.md) for experiment context and negative claims.
5. Use [NullFrame](https://github.com/Aeshma-Daeva/NullFrame#readme) as the map between concepts, source, experiments, and controls.

Public repositories contain the inspectable subset of a broader local research
workspace. Private operational systems and datasets are not presented as
publicly reproducible artifacts.
