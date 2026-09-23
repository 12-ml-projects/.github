# 12 ML Projects

Twelve machine learning projects. Doing this because it's fun.

Each project is its own repository, or even a collection of repositories. The aim of the project is to do generally do things, or understand them, from scratch before using them in the present or subsequent projects.

## The projects

| # | Project | What it covers | Status |
|---|---------|----------------|--------|
| 1 | [hand-rolled-nn](https://github.com/12-ml-projects/hand-rolled-simple-neural-networks) | CNNs, FFNNs, automatic differentiation, backpropagation, tensors, ONNX | Done |
| 1 | [board-games](https://github.com/12-ml-projects/board-games) | game engines, minimax algorithm, Elo ladders, Bradley-Terry model, basic reinforcement learning, AlphaZero | Done |
| 3 | — | LLMs, tokenization, scaling laws, model compression, context free grammars, information theory, LoRA | In Progress |

## Stack
The CI tooling is consistent across repositories—tox, black, isort, autoflake, flake8, mypy. Pytest for testing. MLflow for experiment tracking, when necessary. PyTorch is a common visitor across repositories. GitHub Actions for CI.

## The Book
The eventual plan is to compile all the work into a book, alongside theory, exploration, history and other asides. Few books I read online, especially surrounding machine learning, actually aim to show the implementation or exploration of machine learning. Many focus on the technologies, the skills, etc., that are surely marketable and tranferable, but less inspired or fun than a good project.
I have generally decided not to write in parallel with implementing the projects, as it turned out that writing the book was taking me much longer than implementing the projects themselves. The chapters are better written after the fact.

The repository for the Hugo-based book can be found at https://github.com/12-ml-projects/12-ml-projects-book
