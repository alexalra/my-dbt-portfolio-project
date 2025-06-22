# 🧠 DBT Fundamentals Project

This project is part of the **DBT Fundamentals Course**, designed to teach core concepts and best practices for building modern data transformation pipelines using **dbt (data build tool)**.

As part of the course, I completed hands-on exercises and built a sample dbt project, which includes models, sources, seeds, tests, and documentation — all structured according to dbt’s modular and scalable framework.

---

## ✅ What I Learned

Through this course, I gained practical experience with the following key concepts:

- ✅ **ETL vs ELT Workflows** – Understanding the modern ELT paradigm and dbt’s role in it
- ✅ **DBT Models, Tests, Sources, and Macros** – Creating and managing modular SQL models with built-in quality checks
- ✅ **YAML Configuration & Jinja Templating** – Using configuration files and dynamic logic to build reusable and maintainable code
- ✅ **Modular Project Structure and Naming Conventions** – Organizing dbt projects for clarity, scale, and collaboration
- ✅ **Data Lineage using `ref()` and `source()`** – Enabling dependency-aware builds and lineage tracking in dbt
- ✅ **Building and Testing Data Pipelines** – Writing and validating transformations that ensure data integrity
- ✅ **Documenting Models for Clarity and Collaboration** – Using dbt Docs to generate documentation and promote shared understanding
- ✅ **Deploying and Scheduling Jobs in dbt Cloud** – Running transformations in production with scheduling and CI/CD integration

---

## 📁 Project Structure

The repository includes:

- `/models/` – Staging, intermediate, and mart models
- `/seeds/` – Sample CSV data for loading into the warehouse
- `/macros/` – Reusable logic and custom functions
- `/snapshots/` – (if used) Track slowly changing dimensions
- `/tests/` – Custom and generic data tests
- `dbt_project.yml` – Project configuration file
- `README.md` – You’re reading it!

---

## 🚀 Try It Yourself

To run this project:

1. Clone the repo  
2. Install dbt (e.g., `pip install dbt-core` or use dbt Cloud)
3. Set up your connection profile in `profiles.yml`
4. Run dbt commands like:
   ```bash
   dbt seed
   dbt run
   dbt test
   dbt docs generate
   dbt docs serve
