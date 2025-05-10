### Modules and their functionalities outlined

1. ProfilerWrapper - Covers system-level runtime bottlenecks.

   Captures compute, memory, and time metrics.

   Allows trace inspection and integration with Torch Profiler GUI.

   Covers system-level runtime bottlenecks.

2. HookManager - Covers training dynamics (vanishing/exploding gradients, dead neurons).

   Captures gradients and activations at the layer level.

   Supports granular visibility into training signal flow.

3. Analyzer - Covers analysis, cross-correlation, and prioritization.

   Central brain — interprets profiler + hook outputs.

   Quantifies and ranks problems.

4. Reporter - Covers presentation and usability.

   Converts results into usable output: CSVs, plots, maps.

   Interfaces well with papers, debugging, or monitoring dashboards.

5. Runner - Covers reproducibility, config-based execution.

   Unifies everything into a reproducible, automated flow.

   Load model → attach hooks → profile → analyze → report.


Arsh Kapoor
Hooks.py - experimenting on how hooks work and what output is generated (10-05-2025)
