# BITS Pilani Digital – Advanced Grading Console

A web-based grading application designed to simplify and streamline student grading for BITS Pilani Digital courses.

## Features

- Upload Excel files containing student marks
- Validate BITS IDs, courses, and marks
- Detect duplicate student IDs and invalid marks
- Support `.xlsx` and `.xls` files
- Select courses from a unique course dropdown
- Configure grade ranges from A to E
- Validate grade ranges for gaps and overlaps
- Reset grade ranges to default values
- Display course marks distribution
- Show overall course statistics:
  - Minimum
  - Maximum
  - Average
  - Median
- Display grade-wise student counts
- Track grading time with a timer
- Export finalized grades as a CSV file

## Excel File Format

The uploaded Excel file should contain exactly three columns:

| BITS ID | Course | Total Marks |
|----------|--------|-------------|
| 2026EM1100101 | Data Preprocess | 78 |
| 2026EM1100102 | Data Preprocess | 85 |
| 2026EM1100103 | Statistical Modelling | 72 |

### Validation Rules

- BITS ID is required and must be unique.
- Course is required.
- Total Marks must be a whole number.
- Marks must be between 0 and 100.
- - Decimal marks are not allowed.
- `NC` is not accepted in the grading file.
- Invalid records must be corrected before grading.

## Default Grade Ranges

| Grade | Marks |
|-------|-------|
| A | 80–100 |
| A- | 70–79 |
| B | 60–69 |
| B- | 50–59 |
| C | 40–49 |
| C- | 30–39 |
| D | 20–29 |
| E | 0–19 |

Grade ranges can be adjusted within the application, provided they remain continuous and valid.

## Technologies Used

- HTML
- CSS
- JavaScript
- SheetJS
- HTML Canvas

## Running the Application

No installation or configuration is required.

The application runs directly in a web browser. Upload the Excel file, select the course, configure the grade ranges if required, and finalize the grading.

## Project Objective

This project was developed as part of the **Debug. Reimagine. Deploy.** challenge, focusing on identifying bugs, improving usability, validating input data, and delivering a working browser-based grading application.
