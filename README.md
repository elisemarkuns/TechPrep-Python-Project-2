# TechPrep-Python-Project-2

## Description

A simple Python practice project for the TechPrep program. It demonstrates basic proficiency with Pandas and functions. The script reads a CSV file of student grades, calculates the average across several columns, and assigns a letter grade based on a defined grading scale.

## Features

- **Data Input**: Reads grades from a CSV file (`Data/Grades_Short.csv`).
- **Grade Calculation**: Computes the mean of all grades for each student.
- **Letter Grading**: Automatically assigns letter grades (A+ through F) based on the calculated final score.
- **Data Export**: Saves the modified dataset with the new "Letter_Grade" column to a new CSV file (`Data/Grades_Short_Modified.csv`).

## Requirements

- Python 3.10+ (Required for `match`/`case` statement)
- [pandas](https://pandas.pydata.org/)

## Getting Started

1. **Clone or download** this repository to your local machine.
2. **Ensure** the file structure includes a `Data` folder with your input file `Grades_Short.csv`.
3. **Install** dependencies (if using a virtual environment):
   ```bash
   pip install pandas
   ```

## Usage

Open the notebook file `techprep_python_project_2.ipynb` in **Jupyter Notebook** or **Google Colab**.

1. Ensure the input path matches your local `Data/Grades_Short.csv`.
2. Run the cell.
3. The output CSV will be generated in the same `Data` folder.

## File Structure

```
TechPrep-Python-Project-2/
├── techprep_python_project_2.ipynb
└── Data/
    ├── Grades_Short.csv
    └── Grades_Short_Modified.csv
```

## Notes

This project is a learning exercise focused on understanding how to structure functions and manipulate tabular data in Python. It is not intended for production use.

## Disclaimer

This README.md was written with the help of an LLM.
**All project code is written by me.**
