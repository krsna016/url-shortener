# c1-url-shortner

[![Language: Python](https://img.shields.io/badge/language-Python-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI Pipeline](https://github.com/krsna016/c1-url-shortner/actions/workflows/ci.yml/badge.svg)](https://github.com/krsna016/c1-url-shortner/actions/workflows/ci.yml)
[![Security: CodeQL](https://github.com/krsna016/c1-url-shortner/actions/workflows/codeql.yml/badge.svg)](https://github.com/krsna016/c1-url-shortner/actions/workflows/codeql.yml)

Professional engineering repository configurations deployed inside your GitHub profile.

---

## Overview & Core Description

A simple URL shortener web application built with Flask.

## Overview

This project provides a web-based URL shortener where users can input long URLs, and the application generates shorter, easy-to-share URLs. The project is built using Flask, Flask-Bootstrap, and Flask-WTF.

## Features

- Shortens long URLs to unique, easily shareable short URLs.
- Utilizes a randomly generated key for short URL creation.
- Stores the mapping of short URLs to original long URLs in a JSON file.
- Responsive web design with Bootstrap for an enhanced user experience.

## Project Structure

- `main/Main.py`: The main Flask application file.
- `templates/index.html`: HTML template for the web interface.
- `json/urls.json`: JSON file to store the mapping of short URLs to original long URLs.

## Usage

- Access the application in your web browser.
- Enter a long URL in the provided form.
- Click the "Shorten" button to generate a short URL.
- The short URL will be displayed, and you can use it to redirect to the original long URL.

## Configuration

- The SECRET_KEY is randomly generated for security purposes.
- Shortened URLs are stored in the json/urls.json file.


## Getting Started

This step involves installing the required Python packages (dependencies) for your project. In a Flask project, dependencies are often listed in a `requirements.txt` file. You can install these dependencies using the following command also make sure to clone the repo using the url given using using your command-prompt / terminal:



1. **Clone the repository:**

   ```bash
   git clone https://github.com/krsna016/upskill-campus-intern.git

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt

---

## System Design & Folder Structure
```text
.github/                  # CI/CD pipelines, Dependabot, and Issue/PR schemas
.editorconfig             # Unified file formatting configuration
.gitattributes            # Normalization variables for LF line endings
.gitignore                # Local environment overrides and cache limits
.pre-commit-config.yaml   # Quality check execution triggers
LICENSE                   # Permissive open-source MIT License
Makefile                  # Development workspace orchestrator
CHANGELOG.md              # Historical version tracking
CONTRIBUTING.md           # Developer onboarding guidelines
CODE_OF_CONDUCT.md        # Communication guidelines
SECURITY.md               # Responsible vulnerability disclosures
```

---

## Tooling & Tech Stack
- **Primary Environment:** Python runtime.
- **Workflow Automation:** GitHub Actions CI, Dependabot, and CodeQL.
- **Standards Checkers:** Git `pre-commit` hook validations.

---

## Quickstart & Local Setup
1. Clone this repository locally:
   ```bash
   git clone https://github.com/krsna016/c1-url-shortner.git
   cd c1-url-shortner
   ```
2. Trigger the local setup runner:
   ```bash
   make help
   ```

---

## Security & Responsible Disclosure
For details on disclosing vulnerabilities or hardcoded secrets, refer directly to our [SECURITY.md](SECURITY.md) guidelines.

---

## License
This repository is licensed under the permissive **MIT License**. For details, see the [LICENSE](LICENSE) file.
