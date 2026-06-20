# Climate Neural Operators Lab

This repository is my scientific machine learning learning lab. I am using it to study Fourier Neural Operators and related neural-operator methods, starting with small PDE benchmarks and building toward climate-field reconstruction for global warming and extreme heat analysis.

A major goal of this project is also to prepare for meaningful open-source contributions to the NeuralOperator ecosystem. Rather than only building a standalone project, I want to understand the library deeply enough to improve documentation, examples, tests, or beginner-friendly workflows that can help other students learn operator learning.

## Motivation

Climate and weather systems produce large physical fields such as temperature, pressure, wind, and sea-surface temperature. These fields are expensive to simulate at high resolution and are often observed through sparse, noisy, or incomplete measurements. Neural operators are a promising approach for learning mappings between physical fields, making them relevant for fast surrogate modeling, climate analysis, and AI for science.

## Goals

- Learn the foundations of Fourier Neural Operators and operator learning.
- Reproduce small NeuralOperator examples such as Darcy flow or other PDE benchmarks.
- Understand the NeuralOperator codebase well enough to contribute useful documentation, examples, tests, or educational material.
- Study how neural operators behave under resolution changes, noise, and missing observations.
- Build toward sparse-to-dense climate-field reconstruction for extreme heat analysis.
- Practice research-style experimentation and production-style ML engineering.

## Contribution Roadmap

1. Run and document existing NeuralOperator examples.
2. Write beginner-friendly notes explaining inputs, outputs, tensor shapes, and training flow.
3. Identify confusing docs, missing explanations, or small issues in examples.
4. Build a clear local reproduction notebook for an FNO benchmark.
5. Compare results against simple baselines such as interpolation or CNN models.
6. Propose a small contribution to NeuralOperator, such as:
   - improved documentation,
   - a clearer tutorial,
   - a beginner-friendly example,
   - a small test,
   - or an educational climate/PDE reconstruction example.

## Project Roadmap

1. Start with a basic FNO/Darcy or PDE benchmark.
2. Visualize predictions, ground truth fields, and error maps.
3. Add experiments for sparse or low-resolution inputs.
4. Evaluate robustness to missing observations and noise.
5. Move toward climate-related field data.
6. Package inference with clean scripts, Docker, and eventually a small API.
