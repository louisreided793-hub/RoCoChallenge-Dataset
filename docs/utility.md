# Utility of the Real-World RoCo Dataset (for future research use)

This note can be quoted/adapted on the website and in manuscript revisions.

## Why the **real-world** subset is needed

Simulation-only results cannot fully capture contact uncertainty, perception noise, timing mismatch, and correction behaviors in collaborative assembly. The real-world subset provides these effects directly and allows reproducible measurement of robustness.

## What future researchers can do with this data

1. **Human-aware collaborative policy learning**
   - Train policies that decide when to continue autonomously vs. when to assist a human operator.

2. **Error detection and recovery under realistic failures**
   - Benchmark methods that identify wrong assembly states and perform safe correction.

3. **Partial-progress continuation and task resumption**
   - Study planning/control for resumed execution from interrupted or incomplete assemblies.

4. **Sim-to-real transfer and adaptation**
   - Evaluate domain adaptation, representation learning, and policy transfer from synthetic to real trajectories.

5. **Multimodal representation learning for manipulation**
   - Use synchronized RGB + proprioception + action logs for sequence modeling and temporal grounding.

6. **Benchmarking industrially relevant generalization**
   - Compare methods on order constraints, safety-aware correction, and completion under uncertainty.

## Suggested one-paragraph website statement

The RoCo real-world subset is designed as a forward-looking resource for robust collaborative assembly research. Beyond reporting challenge scores, it supports future work on human-aware decision making, error recovery, and sim-to-real transfer by exposing realistic sensing and execution imperfections that are hard to model in simulation alone.
