# Climate Neural Operators Lab

This repository is a learning and research-engineering project for scientific machine learning. I am using it to study Fourier Neural Operators and related neural-operator methods, starting with small PDE benchmarks and building toward climate-field reconstruction for global warming and extreme heat analysis.

## Motivation

Climate and weather systems produce large physical fields such as temperature, pressure, wind, and sea-surface temperature. These fields are often expensive to simulate at high resolution and may be observed through sparse or incomplete measurements. Neural operators are a promising approach for learning mappings between physical fields, which makes them relevant for fast surrogate modeling, climate analysis, and AI for science.

## Goals

- Learn the foundations of Fourier Neural Operators and operator learning.
- Reproduce small NeuralOperator examples such as Darcy flow or other PDE benchmarks.
- Study how model performance changes with resolution, noise, and missing observations.
- Build toward sparse-to-dense climate-field reconstruction for extreme heat analysis.
- Practice production-style ML engineering with clean code, reproducible experiments, testing, Docker, and model-serving APIs.

## Planned Roadmap

1. Run and document a basic NeuralOperator/FNO example.
2. Reproduce predictions, ground truth fields, and error maps.
3. Compare FNO results against simple baselines such as interpolation or CNN models.
4. Add experiments for sparse or low-resolution inputs.
5. Move toward climate-related field data.
6. Package inference with FastAPI and Docker.

## Status

Early learning stage. Initial focus is understanding NeuralOperator examples, documenting what I learn, and building a clean project structure.
