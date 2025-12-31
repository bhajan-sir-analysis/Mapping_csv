📌 Project Overview

This project demonstrates a complete data cleaning and mapping workflow using CSV-based input data.

The objective of this project is to:

Process raw job data

Clean invalid or missing values

Extract meaningful fields (experience, salary, company, etc.)

Map structured output into a final CSV format

Validate the full pipeline using command-line execution

This project is designed to show real-world data handling, mapping logic, and transformation workflow.

📁 Project Structure

Mapping_csv/
│
├── bd_jobs.csv                # Raw input data

├── clean_bd_jobs.csv          # Cleaned intermediate data

├── final_mapped_jobs.csv      # Final mapped output

├── cmd-screenshots.pdf        # Execution screenshots (CMD)

├── how_to_mapping.mp4         # Full mapping demo video

└── README.md                  # Project documentation

⚙️ Workflow Explanation

1️⃣ Input Processing

Reads raw data from bd_jobs.csv

Removes invalid or incomplete rows

Normalizes columns for further processing

2️⃣ Data Cleaning

Removes unwanted values

Standardizes company and job fields

Prepares clean dataset (clean_bd_jobs.csv)

3️⃣ Mapping Logic

For each job record:

Extracts experience level

Attempts salary detection (if available)

Handles missing values safely

Maps cleaned values to final structure

4️⃣ Output Generation

Final output is saved as:

final_mapped_jobs.csv


All jobs are processed sequentially

Execution status is logged in CMD

🖥️ Execution Proof

✔ Command-line execution screenshots are available in:

📄 cmd-screenshots.pdf

These screenshots show:

Job-by-job mapping

Experience extraction

Salary detection attempts

Successful completion logs

Final output confirmation

✔ Full walkthrough video is available in:

🎥 how_to_mapping.mp4

📊 Sample Output

The final output file includes:

Company Name

Experience Level

Salary (if available)

Cleaned job fields

Structured mapping results

This output is ready for:

Further analysis

Upload to systems

Reporting or dashboards

🔐 Important Note

This repository demonstrates workflow and results

Source code is intentionally not shared

Input/output files and execution proof are provided for reference

Suitable for data mapping, validation, and pipeline demonstration

✅ Use Case

This project is useful for:

Data cleaning pipelines

Job data analysis

CSV mapping workflows

Demonstrating data processing capability

Client or stakeholder validation

📌 Status

✔ Pipeline tested

✔ Output verified

✔ Mapping completed successfully

✔ Ready for review
