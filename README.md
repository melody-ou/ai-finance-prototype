## AI Consulting Assistant
## MBA Team Project — Financial Planning and Analysis Prototype

A prototype developed by Team 7 for X500 Agentic AI Strategy & Application at Indiana University’s Kelley School of Business, Summer 2026.

## Business problem

Finance teams must reconcile financial files, calculate budget variances, investigate drivers, and explain results to managers. Our team selected one MVP from a broader consulting-assistant vision to explore this workflow using fictional financial data.

## My contribution

I summarized professor feedback and proposed a focused end-to-end workflow:

Upload → Validate → Calculate → Analyze → Forecast → Display → Explain

I proposed delivery priorities, synthetic-data test scenarios, and a clear five-minute demonstration. I also contributed a presentation draft.

The application implementation was a team effort. This repository presents the group prototype alongside my contribution to scope, requirements, and delivery planning.

## Implemented capabilities

- Upload and validate a chart of accounts, budgets, and actual transactions.
- Calculate budget-versus-actual variances.
- Generate a year-end reforecast.
- Filter results and explore department, account, vendor, and transaction details.
- Display calculated explanations and export reports.

## Technology

- HTML, CSS, and JavaScript for the offline application.
- Python and pandas for financial calculations and verification.
- Node.js for build and regression tools.
- AI-assisted development using Codex.

## Validation

The supplied regression suite was rerun during portfolio preparation: 64 checks passed, with no failures. It includes financial reconciliation against an independent pandas calculation and repeatable-build checks.

Visual browser verification remains a separate check.

## Limitations and learning

This is an educational prototype using fictional data.

The proposed scope included comparing forecasting methods and providing grounded AI explanations. The uploaded version implements a specialized reforecast approach and programmed explanations, without live AI-model calls.

A future iteration would evaluate candidate forecasting methods using historical validation and test whether AI explanations improve users’ understanding.

## Team

Dustin Birn, Trevor Dawson, Zachary Kalemba, Tari Machanzi, and Melody Ou.
