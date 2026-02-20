# AI-Assisted Programming - Labs Template (Legacy)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/danielcregg/aiap-labs-template_old?style=flat-square)

A starter template for an AI-Assisted Programming lab course. Students use **GitHub Codespaces** and **GitHub Copilot** to complete a series of Python programming tasks covering functions, classes, sorting and search algorithms, data structures, and benchmarking.

> **Note:** This is the legacy version of the labs template. Consider checking for an updated version of this repository.

---

## Prerequisites

- A [GitHub](https://github.com) account with access to **GitHub Codespaces**
- **GitHub Copilot** enabled on your account
- Basic familiarity with Python

---

## Getting Started

1. **Open in Codespace** -- Click the **Code** button on the repository page and select **Create codespace on main**.
2. **Wait for Setup** -- The dev container will automatically install Python and all required dependencies.
3. **Start Working** -- Open `setup_lab.py` and follow the TODO comments for each task.

### Verify Your Environment

After the Codespace finishes building, confirm everything is working:

```bash
python --version
pip list
```

Ensure GitHub Copilot is active by checking the status bar in VS Code.

---

## Lab Structure

All tasks are contained in a single file, `setup_lab.py`:

| Task | Description |
|------|-------------|
| 1 | Create a greeting function |
| 2 | Build a statistics function (mean, median, mode) |
| 3 | Implement a Calculator class with basic operations |
| 4 | Implement bubble sort, quick sort, and merge sort |
| 5 | Implement linear search and binary search |
| 6 | Create a custom data structure with insert, search, and delete |
| 7 | Write a benchmarking function for algorithm performance |

---

## Usage

Complete each TODO in `setup_lab.py`, then test your implementations:

```bash
python setup_lab.py
```

### Dependencies

Install manually if needed:

```bash
pip install -r requirements.txt
```

The `requirements.txt` includes `numpy` and `pandas`.

---

## Submission Checklist

- [ ] All tasks in `setup_lab.py` are completed
- [ ] Code is tested and runs without errors
- [ ] Changes are committed with clear, descriptive messages
- [ ] Work is pushed to GitHub

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Copilot not responding | Verify you are signed in to GitHub and have Copilot access |
| Import errors | Run `pip install -r requirements.txt` |
| Extension issues | Reload the VS Code window (`Ctrl+Shift+P` > *Reload Window*) |

---

## License

This project is licensed under the [MIT License](LICENSE).
