# AI--Assignment
This project contains implementations of fundamental AI algorithms and games, including Alpha-Beta Pruning visualization, Hidden Markov Model (Viterbi algorithm), and an interactive Tic-Tac-Toe game with AI.
Project Overview
The project consists of three main Python modules demonstrating key concepts in artificial intelligence:

1. Alpha-Beta Pruning (alpha_beta_prunning.py)
An implementation of the Alpha-Beta pruning algorithm with game tree visualization. This algorithm optimizes the minimax algorithm by eliminating branches that don't need to be evaluated.

Features:

Builds game tree structures
Visualizes the pruning process using Graphviz
Generates visual output showing which branches were pruned
Tracks alpha and beta values during execution
2. Hidden Markov Model - Viterbi Algorithm (hmm_viterbi.py)
Implementation of the Viterbi algorithm for finding the most likely sequence of hidden states in a Hidden Markov Model.

Features:

Solves the decoding problem in HMMs
Computes optimal hidden state sequences
Visualizes probability matrices using matplotlib
Supports custom transition and emission probabilities
3. Tic-Tac-Toe with AI (tic_tac_toe.py)
An interactive Tic-Tac-Toe game where you can play against an AI opponent powered by the Minimax algorithm.

Features:

Human vs AI gameplay
AI uses minimax with alpha-beta pruning
Interactive command-line interface
Tracks game state and win conditions
Requirements
Before running the project, ensure you have Python 3.6+ installed.

Dependencies
All required Python packages are listed in requirements.txt:

contourpy (1.3.3) - Required for matplotlib
cycler - Required for matplotlib
graphviz - For generating game tree visualizations
kiwisolver - Required for matplotlib
matplotlib - For plotting and visualization
numpy - For numerical computations in Viterbi algorithm
packaging - Dependency management
Pillow - Image processing library
pyparsing - Parsing utilities
