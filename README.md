# Database Design & Management System for R&D Projects

A relational database system designed to manage research projects, budgets, team roles, and deliverables. Built as part of a university project using SQLite and SQLiteStudio.

## Features

- Research project tracking (timelines, status, deliverables)
- Budget management and expense tracking
- Team role assignment and allocation
- Funding analysis and financial reporting
- Performance monitoring queries

## Files

| File | Description |
|------|-------------|
| `rd_database.sql` | Database schema — tables, relationships, and constraints |
| `queries.sql` | Reporting queries — JOINs, GROUP BY, aggregations for financial and operational analysis |

## Tech Stack

- **Database:** SQLite
- **Tool:** SQLiteStudio
- **Language:** SQL

## Sample Queries

The `queries.sql` file includes queries for:

- Expense tracking per project and budget category
- Funding source analysis
- Team member allocation across projects
- Project performance and deliverable monitoring

## Setup

1. Open SQLiteStudio
2. Create a new database or open an existing one
3. Run `rd_database.sql` to create the schema
4. Run `queries.sql` to execute the reporting queries

## Author

Özgür Akyol — Management Information Systems, Kadir Has University
