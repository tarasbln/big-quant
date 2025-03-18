# Contributing to BIG Quant

Thank you for your interest in contributing to **BIG Quant**, a collaborative quantitative finance project by the **Berlin Investment Group (BIG)**, under the umbrella of **Berliner Börsenkreis e.V.**. We welcome contributions from students, researchers, finance professionals, and anyone passionate about quantitative finance and algorithmic trading.

By contributing, you help bridge the gap between academic theory and practical financial applications.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Issues](#reporting-issues)
- [Code Review Process](#code-review-process)
- [Code of Conduct](#code-of-conduct)
- [Community & Contact](#community--contact)

---

## Getting Started

### Fork and Clone
1. Fork the repository by clicking the "Fork" button at the top right of the GitHub page.
2. Clone your fork to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/big-quant.git
   cd big-quant
   ```

### Set Up Environment
- Create and activate a virtual environment:
  ```bash
  python -m venv venv
  source venv/bin/activate  # Linux/Mac
  .\venv\Scripts\activate  # Windows
  ```
- Install required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

---

## Contribution Guidelines

### Branching Strategy
- Always create a new branch for your contribution:
  ```bash
  git checkout -b feature/your-feature-name
  ```

### Repository Structure
Adhere to the existing repository structure:
```
/research/           # Whitepapers and academic research
/strategies/         # Trading strategies and backtesting
/education/          # Tutorials and learning resources
/data/               # Datasets and scripts
/notebooks/          # Jupyter notebooks
/scripts/            # Analysis scripts
/docs/               # Project documentation
```

### Committing Changes
- Commit frequently with meaningful and descriptive commit messages:
  ```bash
  git commit -m "Add: brief description of your contribution"
  ```

### Push and Open Pull Request
- Push your branch to GitHub:
  ```bash
  git push origin feature/your-feature-name
  ```
- Open a pull request on GitHub with a descriptive title and clear explanation.
- Link related issues if applicable.

---

## Pull Request Guidelines
- Clearly describe the objective of your changes.
- Keep your PRs focused; split unrelated changes into multiple PRs.
- Ensure code readability, maintainability, and adherence to project style.
- Include tests or examples demonstrating your changes when applicable.

---

## Reporting Issues
- Submit detailed reports through [GitHub Issues](https://github.com/tarasbln/big-quant/issues).
- Clearly state the problem, expected behavior, steps to reproduce, and your environment details (OS, Python version, etc.).

---

## Code Review Process
- All pull requests will undergo a review by project maintainers.
- Address review feedback promptly and professionally.
- Maintain respectful and constructive communication during the review process.

---

## Code of Conduct
All participants must adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) to maintain a welcoming and professional community environment.

---

## Community & Contact
- **Website**: [BIG - Berlin Investment Group](https://berliner-boersenkreis.de/big/)
- **Events & Workshops**: Stay updated through our website for opportunities to engage and collaborate.

Thank you for contributing to **BIG Quant** and helping advance the field of quantitative finance!