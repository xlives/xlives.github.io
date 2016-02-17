---
published: true
title: Monotonic Logic vs Non-monotonic Logic
layout: post
---
## Monotonic Logic

Monotonicity of entailment is a property of logical systems which states that the hypotheses of any derived fact may be freely extended with additional assumptions, i.e. given a new premise, those logical systems can only entail new fact. 

### Description Logics

By its nature, Description Logics (DLs) is a monotonic logic because they only infer new fact, if possible. If some contradictions have found during the inference procedure, they will just say that the new knowledge base is not satisfiable (or inconsistent).

## Non-monotonic Logic

Non-monotonic logics are devised to capture and represent defeasible inferences, i.e. a kind of inference in which reasoners draw tentative conclusions, enabling reasoners to retract their conclusions based on further evidence. 

A monotonic logic cannot handle various reasoning tasks such as **reasoning by default**, **abductive reasoning**, **belief revision**, and so on.

## References

1. [Wikipedia: Non-monotonic logic](https://en.wikipedia.org/wiki/Non-monotonic_logic)
2. [Wikipedia: Monotonicity of entailment](https://en.wikipedia.org/wiki/Monotonicity_of_entailment)