# Theory of Computer Games 2025 - Portfolio

This repository showcases my coursework for Theory of Computer Games (TCG) 2025, featuring implementations of various game AI algorithms for **Chinese Dark Chess**. Each project demonstrates progressively advanced search and decision-making techniques.

## 📂 Projects Overview

### 1. [HW1: A* Algorithm](https://github.com/nataliepjlin/tcg2025-HW1)
**Puzzle Solver using A\* Search**

A Chinese Dark Chess puzzle solver that finds optimal solutions using the A* algorithm with custom heuristics. 

**Key Features:**
- Efficient state-space search with admissible heuristics
- FEN notation support for board representation
- Optimal path finding with f-cost, g-cost, and h-cost tracking

**Technical Details:**
- Language: C++
- Algorithm: A* with custom evaluation function
- Full implementation report:  [`TCG-HW1-Report.pdf`](https://github.com/nataliepjlin/tcg2025-HW1/blob/main/TCG-HW1-Report.pdf)

**Usage:**
```bash
cd "HW1:A* algorithm/wakasagihime"
make
./wakasagi
# Input FEN string (examples in validator/testcases)
```

---

### 2. [HW2: Monte Carlo Tree Search (MCTS)](https://github.com/nataliepjlin/tcg2025-HW2)
**Game Agent for Full-Bright Chinese Dark Chess**

An intelligent game-playing agent using Monte Carlo Tree Search for Chinese Dark Chess with all pieces face-up (no flipping mechanics).

**Key Features:**
- MCTS with UCB selection policy
- Efficient simulation and backpropagation
- Real-time decision making against various opponents

**Demo Videos:**
- [Playing against Euler (Easy Baseline)](https://youtu.be/Gj1YTdR9MTw)
- [Playing against UwU (Ultra Easy Baseline)](https://youtu.be/QavxhyRQOR0)

**Technical Details:**
- Language: C++
- Algorithm: Monte Carlo Tree Search
- Full implementation report: [`TCG-HW2-Report.pdf`](https://github.com/nataliepjlin/tcg2025-HW2/blob/main/TCG-HW2-Report.pdf)
---

### 3. [Final Project: Advanced Search Algorithms](https://github.com/nataliepjlin/tcg2025-final)
**Competitive Chinese Dark Chess Agent with Advanced Pruning**

A tournament-grade game agent implementing multiple advanced search techniques for standard Chinese Dark Chess (with flipping and hidden information).

**Key Features:**
- **Alpha-Beta Pruning**: Efficient minimax search with cutoffs
- **NegaScout (Principal Variation Search)**: Null window search optimization
- **Star1 Algorithm**: Specialized handling of chance nodes
- Precomputed material evaluation scores
- Time-managed iterative deepening

**Demo Videos:**
- [Playing against classmate's agent](https://youtu.be/p3ERipeTgEA)
- [Playing against baseline agent](https://youtu.be/5hds3gieOu0)

**Technical Details:**
- Language: C++
- Algorithms: Alpha-Beta, NegaScout, Star1
- Full implementation report: [`TCG-final-Report.pdf`](https://github.com/nataliepjlin/tcg2025-final/blob/main/TCG-final-Report.pdf)



**Precompiling Material Scores:**
```bash
cd wakasagihime/alphabeta/cpp
g++ gen_eval.cpp -o gen
./gen  # Generates material_score.bin
# Move material_score.bin to wakasagihime/ directory
```

---

## 🎯 Learning Outcomes

Through these projects, I demonstrated proficiency in:
- **Classical AI Search**:  A* algorithm with heuristic design
- **Stochastic Planning**: Monte Carlo methods for decision-making under uncertainty
- **Adversarial Search**: Minimax, Alpha-Beta pruning, and advanced variants
- **Game Tree Optimization**: NegaScout and chance node handling
- **Performance Engineering**: Efficient state representation and evaluation functions
- **Algorithm Analysis**: Comparative testing and performance benchmarking

## 📊 Skills Demonstrated

- **Languages**: C++
- **Algorithms**: A*, MCTS, Alpha-Beta Pruning, NegaScout, Star1
- **Concepts**: Heuristic search, game trees, probabilistic reasoning, optimization
- **Tools**: Git submodules, makefiles, cross-platform development

---

## 📄 License & Academic Integrity

This repository contains coursework from Theory of Computer Games 2025. All code is provided for portfolio purposes.
