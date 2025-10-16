# Student Grade Evaluator

A simple Python program that evaluates student scores and assigns corresponding grades according to a standardized grading system.

## Features

- **Grade Calculation**: Converts numerical scores to letter grades (A, B, C, D, F)
- **Input Validation**: Detects and handles invalid scores outside the 0-100 range
- **Batch Processing**: Can process multiple student scores at once
- **Flexible Output**: Supports both individual and batch grading with student numbering

## Grading System

| Score Range | Grade |
|-------------|-------|
| 80 - 100    | A     |
| 70 - 79     | B     |
| 60 - 69     | C     |
| 50 - 59     | D     |
| 0 - 49      | F     |

Error Handling
Validates that scores are within 0-100 range

Provides clear error messages for invalid inputs

Returns None for invalid scores while continuing processing

Requirements
Python 3.6+

No external dependencies required
