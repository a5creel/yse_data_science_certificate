# GitHub Copilot Instructions — Yale Environmental Data Science Certificate

## About This Repository

This is the teaching repository for the **Yale School of the Environment (YSE) Environmental Data Science Certificate Program**. The lead mentor and instructor is **Andie Creel**. All lecture materials are delivered as **Jupyter notebooks** (`.ipynb`) and target students who are environmental professionals or researchers with little to no prior coding experience.

---

## Program Philosophy

- **Audience:** Environmental professionals, grad students, and researchers. Not CS students.
- **Tone:** Friendly, practical, applied. Use environmental examples whenever possible (parks, species, pollution, deforestation, climate, etc.).
- **Pedagogy:** Existing lectures each have a **complete instructor notebook** and a parallel **student worksheet**. New lectures in `new_lectures_2026/` are instructor notebooks only — no worksheets.
- **Language progression:** Start in R, then introduce Python as a second language with explicit R↔Python comparisons.
- **Core message:** "Coding is just coding" — concepts transfer across languages.

---

## Existing Lectures (`final_lecture_material/`)

All current production lectures live here as paired `.ipynb` files: `<topic>.ipynb` (full) + `<topic>_worksheet.ipynb` (student version).

| # | Folder | Topic | Language | Key Concepts |
|---|--------|-------|----------|--------------|
| 1 | `1_think_like_computer/` | Thinking Like a Computer | (slides) | What is programming, pseudocode, debugging strategies, problem decomposition |
| 2 | `2_base_R_I/` | Base R, Part I | R | Data types (numeric, character, logical), variables, vectors, matrices, lists, data frames, `$` operator, indexing |
| 3 | `3_base_R_II/` | Base R, Part II | R | Functions, scope, error handling (`try`, `tryCatch`), for loops, if-else, apply functions, simulation models |
| 4 | `4_data_manip_tidyverse/` | Data Cleaning with Tidyverse | R | `dplyr`: `mutate`, `filter`, `select`, `group_by`, `summarise`, `if_else`, pipes (`%>%`) |
| 5 | `5_intro_data_management/` | Introduction to Datasets | R | `read.csv`, `read_csv`, `vroom`, `head`, `tail`, `dim`, `summary`, `glimpse`, big data considerations |
| 6 | `6_data_viz/` | Data Visualization | R | `ggplot2`: histograms, boxplots, bar charts, scatter plots, color aesthetics, `facet_wrap`, `labs` |
| 7 | `7_intro_to_coding_python/` | Introduction to Python | Python | Data types, variables, lists, NumPy arrays, Pandas DataFrames, `iloc`/`loc`, functions (`def`), for loops, if-else |
| 8 | `8_python_datasets/` | Python Datasets & Data Manipulation | Python | `pd.read_csv`, DataFrame exploration, `assign`, `np.where`, boolean indexing, `dropna`, `groupby`, `agg`, matplotlib, seaborn |
| 9 | `9_data_manip_part_II/` | Advanced Data Manipulation (Tidyverse II) | R | `dplyr` joins (`left_join`, `inner_join`, etc.), `tidyr` pivots (`pivot_longer`, `pivot_wider`) |

---

## Problem Sets (`problem_sets/`)

Auto-graded assessments. Each maps to 1–2 lectures.

| File | Covers | Key Skills |
|------|--------|------------|
| `1_pset_base_R.ipynb` | Lectures 2–3 | Vectors, data frames, for loops |
| `2_pset_R_and_data.ipynb` | Lectures 4–6 | `filter`, `mutate`, `group_by`, `summarise`, ggplot |
| `3_pset_intro_python.ipynb` | Lectures 7–8 | Python variables, NumPy, functions, loops, conditionals |

---

## Archived Materials (`old_R_lecture_material/`)

Earlier `.Rmd` versions of lectures, kept for reference. Do not modify.

| File | Notes |
|------|-------|
| `2_base_R_I.Rmd` | Predecessor to Lecture 2 |
| `3_base_R_II.Rmd` | Predecessor to Lecture 3 |
| `4_data_manip_tidyverse_partI.Rmd` | Predecessor to Lecture 4 |
| `5_data_manip_tidyverse_partII.Rmd` | Additional tidyverse content (now merged into Lectures 4 & 9) |
| `6-7_data_manage_vis/` | R Projects setup, file structure, ggplot visualization |
| `9_github.Rmd` | Git/GitHub: repos, commit, push/pull, PATs, forking — **not yet ported to notebook format** |


---

## Conventions for New Lectures

When developing new lectures, follow these conventions established in the existing material:

1. **File naming:** `<number>_<short_snake_case_topic>/` folder containing `<topic>.ipynb`. No worksheet needed for new lectures.
2. **Notebook language:** Use an R or Python kernel in Jupyter. Match the kernel to the language of the lecture.
3. **Environmental examples:** Always use environmental, ecological, or climate data for examples (not generic toy data like iris or mtcars unless explicitly needed for comparison).
5. **Pacing:** Lectures are ~45–60 minutes of live delivery. Keep code cells short and digestible.
6. **Tone:** Write markdown explanations in plain English. Avoid jargon. Define every new term the first time it is used.
7. **R style:** Use tidyverse conventions. Prefer `<-` for assignment, `%>%` pipes, and `dplyr`/`tidyr` verbs over base R equivalents unless teaching base R explicitly.
8. **Python style:** Use `pandas` and `numpy`. Prefer `assign()` and method chaining over in-place mutation where readable.
9. **Parallel structure:** When introducing Python, explicitly note the R equivalent and vice versa.9. **New lectures location:** New 2026 lectures go in `new_lectures_2026/` as a single instructor notebook only.
---

## Data Files

| File | Used In | Description |
|------|---------|-------------|
| `final_lecture_material/5_intro_data_management/mpg.csv` | Lectures 5, 6 | Vehicle MPG data (manufacturer, class, displacement, hwy mpg) |
| `final_lecture_material/8_python_datasets/mpg.csv` | Lectures 7, 8 | Same MPG dataset, copy for Python lectures |
| `old_R_lecture_material/6-7_data_manage_vis/data/raw_data/mpg.csv` | Old material | Archived copy |
