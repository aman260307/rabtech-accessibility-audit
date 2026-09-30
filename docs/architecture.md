# RabTech Accessibility Audit - Architecture

## 1. Project Overview

This project documents an accessibility audit of the India Government portal and defines a proposed repository architecture for future accessibility improvements.

## 2. Website Audited

https://www.india.gov.in/

## 3. Audit Tools

- Google Chrome Lighthouse
- Manual Keyboard Testing

## 4. Proposed Architecture

The project follows a simple full-stack web application structure:

- Client: Frontend user interface
- Server: Backend/API services
- Docs: Accessibility audit and architecture documentation
- Tests: Testing and validation resources

## 5. Repository Structure

```text
rabtech-accessibility-audit/
│
├── client/
│   ├── index.html
│   └── style.css
│
├── server/
│   └── README.md
│
├── docs/
│   ├── audit-report.md
│   └── architecture.md
│
├── tests/
│   └── README.md
│
├── screenshots/
│   └── Lighthouse accessibility results
│
├── README.md
└── accessibility-audit.xlsx
