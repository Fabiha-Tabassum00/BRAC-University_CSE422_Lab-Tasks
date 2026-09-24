# Artificial Intelligence — Academic Lab Work

Lab assignments from a university Artificial Intelligence course, implemented in Python using Jupyter/Colab notebooks. The work spans classical AI search and optimization algorithms through to machine learning with scikit-learn.

## Skills Demonstrated

- **Informed search** — A* pathfinding with heuristics and a priority queue
- **Optimization** — genetic algorithms (population generation, fitness, selection, crossover, mutation)
- **Adversarial search** — minimax with alpha-beta pruning for two-player games
- **Data preprocessing** — handling missing values, imputation, and feature scaling with pandas and scikit-learn
- **Machine learning** — linear and logistic regression, train/test splitting, and model evaluation
- **Core libraries** — NumPy, pandas, scikit-learn, Matplotlib, Seaborn, SymPy

## Labs

| Lab | Topic | Techniques |
|-----|-------|------------|
| [Lab-1](Lab-1) | Informed Search | A* algorithm with heuristics |
| [Lab-2](Lab-2) | Genetic Algorithm | Selection, crossover, mutation |
| [Lab-3](Lab-3) | Adversarial Search | Minimax with alpha-beta pruning |
| [Lab-4](Lab-4) | Data Preprocessing | Imputation, scaling, exploration |
| [Lab-5](Lab-5) | Machine Learning | Regression models & evaluation |

---

## Lab 1 — Informed Search (A*)

Implements the **A\* search algorithm** to find the shortest path through a graph. Reads a graph with heuristic values and edge distances from an input file, then uses a priority queue (`heapq`) to expand nodes by combined path cost and heuristic, writing the resulting path and cost to an output file.

**Files:** `Lab_Assignment01.ipynb`, `Lab_Assignment01_InputFile.txt`

---

## Lab 2 — Genetic Algorithm

A **genetic algorithm** for a scheduling/assignment problem. Generates an initial population of binary chromosomes, then evolves them over generations using fitness evaluation, two-point crossover, and mutation to search for an optimal configuration.

**Files:** `Lab_Assignment02.ipynb`, `Lab_Assignment02.txt`

---

## Lab 3 — Adversarial Search (Minimax)

Implements **minimax with alpha-beta pruning** for a two-player game scenario, evaluating game states to choose optimal moves and simulating the outcome of a match between two players.

**Files:** `Lab_Assignment03.ipynb`, `input.txt`

---

## Lab 4 — Data Preprocessing

Prepares a real dataset (Wine Quality) for machine learning using pandas and scikit-learn. Covers loading and exploring the data, handling missing values with `SimpleImputer`, feature scaling with `MinMaxScaler`, and visualizing distributions with Matplotlib and Seaborn.

**Files:** `Lab_Assignment04.ipynb`

---

## Lab 5 — Machine Learning

Builds and evaluates machine learning models on the preprocessed dataset:

- **Regression models** — training linear and logistic regression models with scikit-learn.
- **Model evaluation** — using `train_test_split`, `accuracy_score`, and `classification_report` to measure performance.
- **Regression theory** (`Regression_Analysis.ipynb`) — deriving the regression cost function and gradients symbolically with SymPy.

**Files:** `Lab_Assignment05.ipynb`, `Regression_Analysis.ipynb`

---

## Tools

Python · Jupyter / Google Colab · NumPy · pandas · scikit-learn · Matplotlib · Seaborn · SymPy

## Author

**Fabiha Tabassum Poroma**
