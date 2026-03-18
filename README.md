# Excel Salary Benchmarking Dashboard

![Dashboard_gif](https://github.com/user-attachments/assets/a71c042e-bb91-4e2c-afda-1658d28b6e42)


An interactive Excel project for exploring salary patterns across data roles, countries, and employment types.

This workbook transforms a large job-market dataset into a compact analytical dashboard. By selecting a **job title**, **country**, and **employment type**, the user can quickly compare compensation patterns and related market signals.

## Dataset snapshot

**Records:** 32,672 rows  
**Fields:** 16 columns  
**Countries represented:** 111

This scope gives the project enough depth for filtering, segmentation, and comparative analysis.

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
- 
  <img width="284" height="293" alt="Job_title_list" src="https://github.com/user-attachments/assets/acbcfda9-e55e-46a7-98e9-16396d8d514a" />
<img width="566" height="429" alt="job_title_chart" src="https://github.com/user-attachments/assets/937d29c3-a15e-486a-a78f-8719165599b5" />

- filter by **country**,
- 
  <img width="264" height="338" alt="country_list" src="https://github.com/user-attachments/assets/211c15e2-07af-42e4-8b37-f98d46f0cf66" />
<img width="544" height="411" alt="country_chart" src="https://github.com/user-attachments/assets/3fe213ac-abc5-4c26-b415-86856161586a" />

- filter by **employment type**,
  
  <img width="187" height="195" alt="type_list" src="https://github.com/user-attachments/assets/60853dc4-3762-4cee-8833-4ea2d32b4d87" />
<img width="553" height="430" alt="type_chart" src="https://github.com/user-attachments/assets/8b98bfa0-353b-470f-9703-acefe1f45528" />

- review salary benchmarks for the selected combination,
- and compare supporting views across role, geography, and platform.



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

**Łukasz Filipek**  Aspiring Data Analyst with a background in project management and cost control.

---

This project uses Excel as a structured environment for analysis, comparison, and decision support.
