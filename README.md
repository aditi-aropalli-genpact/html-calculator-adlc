# Simple HTML Calculator — ADLC Pipeline

This repository contains the complete outputs of an **Autonomous Software Development Lifecycle (ADLC)** pipeline executed on the concept of a **Simple HTML Calculator** — a single-file HTML5/CSS3/JavaScript calculator application.

## Pipeline Summary

| Step | Artifact | Status |
|------|----------|--------|
| 1. Requirements Analysis | `02_RA_Simple_HTML_Calculator_v1.0.docx` | ✅ Complete |
| 2. Solution Design Document | `03_SDD_Simple_HTML_Calculator_v1.0.docx` | ✅ Complete |
| 3. Code Generation | `source/index.html` | ✅ Complete |
| 4. Security Analysis | `05_Security_Analysis_Report.docx` | ✅ Complete |
| 5. Security Fix & Refactoring | `06_Security_Validation_Report.docx` | ✅ Complete |
| 6. Test Case Generation | `08_Test_Cases_Simple_HTML_Calculator.docx` | ✅ Complete |

## Deliverables

- `01_BRD_Simple_HTML_Calculator_v1.0.docx` — Business Requirements Document
- `02_RA_Simple_HTML_Calculator_v1.0.docx` — Requirements Analysis
- `03_SDD_Simple_HTML_Calculator_v1.0.docx` — Solution Design Document (with diagrams)
- `05_Security_Analysis_Report.docx` — Security & code quality analysis
- `06_Security_Validation_Report.docx` — Remediation validation report
- `08_Test_Cases_Simple_HTML_Calculator.docx` — Test cases with RTM
- `source/index.html` — The working HTML calculator (single file)
- `Simple_HTML_Calculator_Developer_Summary.docx` — Developer reference guide
- `diagrams/` — Architecture, DFD, and Workflow diagrams

## Calculator Features

- Basic arithmetic: +, -, *, /
- Keyboard input support
- Responsive design (desktop & mobile)
- Error handling (division by zero)
- Decimal point support
- Percentage calculation
- Operator precedence (* and / before + and -)
- Zero external dependencies

## How to Use

Open `source/index.html` in any modern web browser.

## Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling (Flexbox/Grid, responsive)
- **JavaScript (ES6+)** — Logic (tokenizer-based expression parser)
