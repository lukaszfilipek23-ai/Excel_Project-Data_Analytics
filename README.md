# Excel Salary Benchmarking Dashboard

![Dashboard_gif](https://github.com/user-attachments/assets/a71c042e-bb91-4e2c-afda-1658d28b6e42)


An interactive Excel project for exploring salary patterns across data roles, countries, and employment types.

This workbook transforms a large job-market dataset into a compact analytical dashboard. By selecting a **job title**, **country**, and **employment type**, the user can quickly compare compensation patterns and related market signals.

## Project overview

The goal of this project is to make salary data easier to explore and interpret inside Excel.

Rather than presenting a static report, the workbook is structured as a small analytical system with:
- a source data sheet,
- controlled user inputs,
- helper logic for selections and calculations,
- and a dashboard layer for clear interpretation.

The result is an Excel-based tool for salary benchmarking rather than a workbook made only for display.

## What the workbook does

The dashboard allows the user to:
- select a **job title**,
- filter by **country**,
- filter by **employment type**,
- review salary benchmarks for the selected combination,
- and compare supporting views across role, geography, and platform.

## Dataset snapshot

**Records:** 32,672 rows  
**Fields:** 16 columns  
**Countries represented:** 111

This scope gives the project enough depth for filtering, segmentation, and comparative analysis.

## Analytical focus

The workbook is designed to answer practical questions such as:
- What is the typical salary for a selected role?
- How do salaries differ by country?
- How does employment type influence compensation?
- Which platforms appear most often for the selected scenario?

These questions make the dashboard useful for structured comparison, not only visual exploration.

## Excel techniques used

### Data organization
- Separation of raw data, helper logic, and presentation sheets
- Workbook layout designed for repeatable analysis
- Structured ranges supporting cleaner formulas and easier maintenance

### Formulas and logic
- `MEDIAN()` for salary benchmarking
- `IF()` for conditional logic
- `COUNTIFS()` for filtered counts
- `FILTER()` for dynamic list generation
- `XLOOKUP()` for lookup logic
- search-based matching for schedule-type filtering

### Input control and usability
- Data Validation drop-downs for controlled user selections
- Helper sheet feeding validated lists into the dashboard
- Separation between support calculations and user-facing output
- Interactive layout designed for quick exploration

## Workbook structure

A practical way to describe the architecture of the workbook is:

- **Raw data layer** → `Data`
- **Input and control layer** → `Salary_Calculator`
- **Helper sheet for validated selections** → `Data_Validation`
- **Analytical support sheets** → `Title`, `Country`, `Type`, `Platform`
- **Presentation layer** → dashboard view inside `Salary_Calculator`

This structure keeps the workbook readable and makes the analysis easier to extend.

## Build approach

The project follows a simple analytical sequence:
1. organize the source data,
2. separate helper logic from presentation,
3. control user input through validated selections,
4. surface only the outputs most useful for interpretation.

This approach improves clarity and reduces the friction of manual exploration.

## Repository contents

[Salary Benchmarking Dashboard](https://github.com/lukaszfilipek23-ai/Excel_Project-Data_Analytics/blob/main/Projekt_excel_1.xlsx) — final Excel workbook


## Author

**Łukasz Filipek**  Transitioning into Data Analytics with a background in project management and cost control.

---

This project uses Excel as a structured environment for analysis, comparison, and decision support.
