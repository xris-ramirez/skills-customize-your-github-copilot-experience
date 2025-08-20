# GitHub Copilot AI Agent Instructions for This Repository

## Project Overview
This repository is a collection of Python programming assignments for learning and practicing core skills. Each assignment is self-contained in its own folder under `assignments/`, with a `README.md` describing requirements and a `starter-code.py` file for implementation.

## Directory Structure
- `assignments/` — Main folder for all assignments
  - `python-basics/`, `python-classes/`, `games-in-python/`, `data-analysis/` — Each contains:
    - `README.md` (assignment instructions)
    - `starter-code.py` (starter template)
    - Additional data files as needed (e.g., `data.csv` for data analysis)
- `assets/` — Static files for the web interface (HTML, CSS, JS, images)
- `templates/` — Markdown templates for assignments
- `index.html` — Entry point for the web interface

## Key Patterns & Conventions
- **Assignment Structure:** Each assignment folder is self-contained. Do not mix code or data between assignments.
- **Starter Code:** All Python starter files use clear TODO comments to indicate where students should implement logic. Preserve these comments when updating code.
- **Data Files:** Data analysis assignments expect data files (e.g., `data.csv`) to be in the same folder as the starter code.
- **No Central Build/Test:** There is no global build or test system. Each assignment is run independently (e.g., `python starter-code.py` inside the assignment folder).
- **No External Dependencies (except data-analysis):** Only the `data-analysis` assignment uses external packages (`pandas`, `matplotlib`). Others use only the Python standard library.

## Developer Workflows
- **Running Assignments:**
  - Navigate to the relevant assignment folder and run `python starter-code.py`.
  - For data analysis, ensure `pandas` and `matplotlib` are installed.
- **Adding Assignments:**
  - Create a new subfolder in `assignments/` with a `README.md` and `starter-code.py`.
  - Follow the structure and commenting style of existing assignments.
- **Web Assets:**
  - Static assets for the web interface are in `assets/`. Do not place assignment code here.

## Examples
- See `assignments/games-in-python/README.md` and `starter-code.py` for a typical game assignment structure.
- See `assignments/data-analysis/README.md` and `starter-code.py` for a data analysis pattern with external dependencies.

## Additional Notes
- Do not introduce new dependencies except in data analysis assignments.
- Do not modify files outside the relevant assignment folder unless updating shared assets or templates.
- Preserve assignment instructions and starter code comments for student clarity.
