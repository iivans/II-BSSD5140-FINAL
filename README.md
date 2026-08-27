# BSSD 5410 Final Submission Repository

This repository contains coursework and project files for the BSSD 5410 Final submitted by student Isaac Ivans. It features a comprehensive final project implementing a genetic algorithm for maze pathfinding, practical coding solutions for steganography and matrix generation, and written exam responses covering algorithms, time complexity, and data structures.

## Final Project: Genetic Algorithm Maze Pathfinding

The final project simulates an artificial intelligence agent solving a maze through evolutionary computing visualized via Pygame. You can execute the simulation either via the self-contained script named `II-BSSD-5410-FinalProject-ALL-IN-ONE.py` or through the modular version named `II-BSSD-5410-FinalProject-Brokenup.py`. The modular implementation splits functionality across `config.py` for environment constants, maze layout data, and parameters like a population size of 1500 and move limit of 700, `genetic_algorithm.py` for fitness scoring, movement validation, and chromosome generation, and `visualization.py` for Pygame-based real-time graphics rendering.

## Coding Exam Solutions

The coding exam components include `II-BSSD-5410-FinalQ1.py`, which implements Least Significant Bit image steganography using the Pillow library to hide and extract text messages within image pixels. Additionally, `II-BSSD-5410-FinalQ2.py` dynamically builds and prints numerical matrices based on user inputs for grid size ranging from one to eight, chosen starting corners, and stop limits.

## Written Exam Documentation

The document `FINAL-TEST-BSSD3410-5410.pdf` provides written exam answers explaining genetic algorithms versus dynamic programming, Big O time complexity calculations, Run-Length Encoding performance across different image patterns, and criteria for choosing between graphs, trees, or dictionaries. It also explores sorting complexity comparisons between bucket sort and quicksort, radix sort parameters, Markov text generator window sizes, and Minimax evaluation node values with alpha-beta pruning traversal states.

## Requirements and Installation

Running the project scripts requires a standard Python environment alongside the Pygame package for the visual maze simulation and the Pillow library for image steganography processing.
