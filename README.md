# Advanced Programming for Data Science (AP_DS)

[![Course](https://img.shields.io/badge/Course-AP__DS-blue.svg)](#)
[![Class](https://img.shields.io/badge/Class-I5--AMS--DAS--B-purple.svg)](#)
[![Academic Year](https://img.shields.io/badge/Academic%20Year-2026--2027-green.svg)](#)
[![Python](https://img.shields.io/badge/Language-Python%203.10%2B-yellow.svg)](#)
[![Branch](https://img.shields.io/badge/Branch-main-red.svg)](#)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)

Welcome to the primary (**main**) branch of the **Advanced Programming for Data Science (AP_DS)** repository. This repository hosts coursework, practical lab implementations (Travaux Pratiques / TP), lectures, and project deliverables for Year 5 (I5) in the **Applied Mathematics & Statistics - Data Science (AMS-DAS)** program during the **2026–2027** academic year.

The **`main`** branch serves as the central showcase and landing page, summarizing the overall repository structure, branch ecosystem, deliverables, and engineering standards.

---

## 👤 Student Profile

- **Student Name:** Vandeth Sothy
- **Student ID:** `e20220240`
- **Class:** I5-AMS-DAS-B
- **Program:** Applied Mathematics & Statistics – Data Science (AMS-DAS)
- **Academic Year:** 2026–2027
- **Repository:** [github.com/sothy8/AP_DS](https://github.com/sothy8/AP_DS)

---

## 🧭 Repository Ecosystem & Branch Directory

This repository is organized into targeted Git branches tailored for specific components of the course:

```text
AP_DS/ (Repository Root)
│
├── 🚀 main        <- Primary landing page, release-ready deliverables, and consolidated materials
├── 🌐 General     <- Detailed course syllabus, curriculum modules, learning objectives, and activities
├── 💻 TP          <- Weekly practical lab exercises (TP1, TP2, ...), reports (PDF/DOCX), and source code
```

### Quick Branch Navigation

| Branch | Purpose | Description & Links |
| :--- | :--- | :--- |
| **[`main`](https://github.com/sothy8/AP_DS/tree/main)** | **Central Hub & Showcase** | Project overview, setup guidelines, branch directory, and release milestones. |
| **[`General`](https://github.com/sothy8/AP_DS/tree/General)** | **Coursework & Syllabus** | In-depth breakdown of lectures, modules, competencies, and grading activities. |
| **[`TP`](https://github.com/sothy8/AP_DS/tree/TP)** | **Practical Works (Labs)** | Hands-on code submissions, Jupyter notebooks, scripts, and formal reports. |

---

## 🎯 Course Focus & Core Competencies

The **Advanced Programming for Data Science** course bridges software engineering best practices with data-centric programming:

1. **Python Software Engineering & Clean Code:** Writing robust, PEP 8-compliant, modular code with effective packaging, functions, and modules.
2. **Advanced Object-Oriented Programming (OOP):** Designing reusable architectures using encapsulation, inheritance, polymorphism, custom dunder methods, decorators, and generators.
3. **High-Performance Numerical Computing:** Leveraging NumPy vectorization, array manipulation, memory efficiency, and broadcasting.
4. **Data Wrangling Pipelines:** End-to-end data processing with Pandas, handling missing data, time series, multi-indexing, and data aggregation.
5. **Exploratory Data Analysis & Visualization:** Data storytelling and visual analytics using Matplotlib, Seaborn, and Plotly.
6. **Machine Learning Pipeline Delivery:** Structuring maintainable Scikit-Learn workflows, preprocessing transformers, model evaluation, and export.
7. **Testing, Profiling & Debugging:** Systematic debugging with pdb/breakpoints, unit testing, and code profiling.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sothy8/AP_DS.git
cd AP_DS
```

### 2. Explore Specific Branches

Switch between branches depending on what you wish to review:

```bash
# Switch to practical works and lab reports
git checkout TP

# Switch to the general course overview and syllabus
git checkout General
```

### 3. Environment Setup

It is recommended to run the coursework in an isolated Python virtual environment:

```bash
# Create virtual environment
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate       # On macOS/Linux
# .\venv\Scripts\activate      # On Windows

# Upgrade pip
pip install --upgrade pip
```

---

## 🧰 Tools & Technology Stack

- **Language:** Python 3.10+
- **Data & Scientific Libraries:** NumPy, Pandas, SciPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-Learn
- **Development Tools:** VS Code, JupyterLab / Jupyter Notebook, Git & GitHub
- **Linters & Formatters:** Flake8, Black, PEP 8 Linters