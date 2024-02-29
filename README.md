# CSCK502-Reasoning-and-Intelligent-Systems-January-2024

This project is a simple software application in Python that solves a puzzle game similar to Sudoku using genetic algorithms. The objective is to fill a grid of size 4x4 with four different letters so that each column, each row, and each of the four sub-grids of size 2x2 contain each of the letters only once (‘W’,’O’,’R’,D’).

## Setup and Running the Application

1. Clone the repository or download the code to your local system.

2. Run the application in code editor or web application such as Colaboratory.

Notes:
You might change the below factors to generate different results.
```
population_size = 300
mutation_rate = 0.1
crossover_probability = 0.9
num_generations = 300
```

## Testing

One partially completed grid is defined for testing the system functionalities:
```
partial_grid = [
    ['W', 'O', 'R', None],
    [None, 'D', None, None],
    [None, None, None, None],
    ['D', None, None, None]
]
```