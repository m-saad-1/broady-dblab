# Broady DBLab Academic Task

This repository contains the academic submission work for the Broady DBLab assignment.

The implementation is aligned with PostgreSQL and Prisma, while the assignment brief uses MySQL-style wording. Academic artifacts here preserve the same normalized schema, ERD design, and dataflow required by the project.

## Repository Contents

- `DBLab_ProjectUpdate.pdf` — assignment brief and author instructions
- `ERD_Documentation.pdf` — completed Module 1 ERD deliverable
- `academic-task-plan.md` — milestone plan and implementation checklist
- `NORMALIZATION.md` — Milestone 2 normalization write-up
- `DATAFLOW.md` — Milestone 3 dataset preparation and dataflow
- `csv/` — synthetic dataset exports for Milestone 3
- `sql/milestone-4-ddl.sql` — PostgreSQL DDL for Milestone 4
- `sql/milestone-5-dml.sql` — data load/validation script for Milestone 5
- `FINAL_SUBMISSION_GUIDE.md` — final submission checklist and packaging instructions
- `academic-erd-simplified.md` — compact ERD reference table
- `academic-erd.drawio` — visual ERD diagram source

## Milestone Overview

1. **Milestone 2:** ERD normalization and schema design (2NF / 3NF)
2. **Milestone 3:** Synthetic dataset generation, preprocessing, and dataflow documentation
3. **Milestone 4:** PostgreSQL DDL implementation with keys, constraints, and indexes
4. **Milestone 5:** Data population and validation using CSV loads and SQL scripts

## Key Notes

- The academic artifacts are intentionally separated from any production Broady source code.
- The data model is preserved while focusing on normalization, integrity, and referential consistency.
- The dataset exports are structured as clean CSV files suitable for loading into PostgreSQL.
- The DDL script includes primary keys, foreign keys, not-null constraints, unique constraints, and indexed columns.

## Current Status

- Milestones 2 through 5 are complete and documented.
- `FINAL_SUBMISSION_GUIDE.md` contains the final packaging and delivery steps.

Refer to the milestone-specific documents for details on assumptions, schema decisions, data generation, and load order.
