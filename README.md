# AgriWave Investment Screening Automation

## Overview

A Python-based investment screening automation workflow developed to streamline the assessment of a prospective investment in AgriWave Ltd.

The solution automates the transfer of financial and operational assessment data into a structured investment screening template, reducing repetitive manual data entry while improving consistency, traceability and efficiency.

## Key Features

- **Financial Data Mapping:** Populates Income Statement, Balance Sheet and Cash Flow Statement sections.
- **Investment Assessment:** Automates the population of company information and investment screening criteria.
- **Risk Scoring:** Integrates structured risk scores and supporting assessment comments.
- **Excel Automation:** Uses Python and OpenPyXL to populate predefined Excel cells while retaining the original template.
- **Financial Calculations:** Leverages existing spreadsheet formulas to calculate profitability metrics and financial ratios.
- **Output Generation:** Produces a completed investment screening workbook.

## Technology Stack

- Python
- OpenPyXL
- Excel
- Financial Analysis
- Data Processing and Automation

## Project Structure

```text
├── agriwave_populate_template.py
├── requirements.txt
├── input/
├── output/
├── README.md
└── .gitignore
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/jimymugendi/agriwave-investment-screening-automation.git
cd agriwave-investment-screening-automation
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare the input

Place the required blank screening template in the project directory using the filename expected by the script.

### 4. Run the automation

```bash
python agriwave_populate_template.py
```

### 5. Retrieve the output

The completed screening workbook will be generated as:

`AgriWave_Ltd_Completed_Screening_Template.xlsx`

## Workflow

1. Review the company's investment and financial information.
2. Map relevant financial figures and assessment information to the screening template.
3. Execute the Python automation.
4. Populate the corresponding Excel input fields.
5. Allow existing spreadsheet formulas to calculate financial metrics.
6. Generate the completed investment screening workbook.

## Business Value

The solution demonstrates how lightweight Python automation can improve investment screening workflows by reducing repetitive data entry, standardising financial information mapping and making assessment processes more efficient.

## Future Improvements

- Integration with automated PDF financial statement extraction.
- AI-assisted document interpretation and information extraction.
- Automated financial reconciliation and anomaly detection.
- Integration with low-code platforms such as Microsoft Power Automate.
- Configurable assessment criteria and scoring frameworks.

## Disclaimer

This project was developed as a technical demonstration of financial analysis and workflow automation. Any company information or assessment materials used in the original exercise should not be redistributed without appropriate authorisation.
