# 05-05-2025
# ✅ Project Setup Log: `skin-cnn`

## 1. Environment Setup
- Installed **Python 3.11** (TensorFlow doesn't support 3.13 yet).
- Created and activated a **virtual environment** using `venv`.
- Installed all required packages using the `--break-system-packages` flag due to Homebrew's Python restrictions.
- Generated a `requirements.txt` file with core packages like:
  - `tensorflow`
  - `opencv-python`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `jupyter`

---

## 2. Folder Structure
- Set up project directories: `data/`, `models/`, `notebooks/`, `outputs/`, `src/`, and `docs/`.
- Each folder includes a `README.md` placeholder to keep them in version control.
- Configured `.gitignore` to exclude:
  - `venv/`
  - `__pycache__/`
  - `data/`
  - `outputs/`
  - `models/`

---

## 3. GitHub Setup
- Created the `skin-cnn` repository and pushed the initial project files.
- Set `main` as the default branch.
- Created a development branch: `feature-model-v1`.
- Commit messages include details about Python version choice and system package handling.

---

## 4. Community Standards & Issue Templates
- Added a `CODE_OF_CONDUCT.md` file in the `.github/` folder.
- Created a `bug_report.yml` issue form using GitHub’s new issue form format.
  - Includes dropdowns, input fields, and a required Code of Conduct checkbox.
- Added a `config.yml` to organize issue templates and disable blank issues.
- Verified everything works by opening the "New Issue" tab and seeing the form rendered correctly.

---

## 5. GitHub Pages Deployment
- Created a `docs/` folder and added a basic `index.md`.
- Configured **GitHub Pages** to deploy from the `main` branch's `/docs` folder.
- Verified that the site is live at:
  [https://browntd.github.io/skin-cnn/](https://browntd.github.io/skin-cnn/)
- Created a **GitHub Project Board** (starting with a Bug Tracker) to organize tasks and bugs visually.
- Tested both issue templates and Pages deployment—everything is working as expected.

---

### TensorFlow Tutorial - https://www.youtube.com/watch?v=ea5Z1smiR3U&utm_source=chatgpt.com
- `05-06-2025` Video 3 - Timestamp 14:31
