## Sudoku pair

A pair of sudokus that have different numbers filled in all cells with same cell locations

## how to run the program

```bash
# for generator
python3 sudoku_generator.py <k> [<output_file_path>]
# for solver
python3 sudoku_solver.py <k> <input_file_path> [<output_file_path>]
# Note that [<output_file_path>] is optional
```

## Test cases

- There are test cases in the `test` folder
- to use test cases run the following

```bash
python3 sudoku_solver.py <k> tests/test<x>.csv
```
