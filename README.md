# Data Architecture & Behavioral Survey Code Book
**Technical Stack: R, Quarto, Markdown**

This repository contains the comprehensive Data Dictionary and Code Book for a large-scale mobile usage behavior survey. It serves as the foundational "Source of Truth" for downstream statistical analysis and predictive modeling.

## Data Governance & Preparation
* **Schema Definition:** Systematically mapped survey variables to standardized data types and categorical levels.
* **Variable Encoding:** Established binary and ordinal scales (e.g., Usage Frequency, Device Interaction) to ensure data compatibility for R-based statistical packages.
* **Metadata Documentation:** Authored a technical roadmap for the dataset, defining the context, constraints, and units for every observation.
* **Reproducible Documentation:** Built with Quarto to maintain a live, syncable reference for the research team.

## Project Structure
* `project_4_phone_survey_code_book.qmd`: The primary source file defining the dataset's architecture.
* `data_dictionary/`: Detailed breakdowns of survey response logic and encoding.
