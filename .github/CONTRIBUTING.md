# Contributing to Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine

Thank you for considering contributing to the Crawl4AI project! We welcome your contributions to improve our LLM-optimized web crawler and scraper.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to `chirag.dev@example.com` or through GitHub Issues.

## 2. How to Contribute

We accept contributions in various forms, including:

*   **Bug Reports:** If you find a bug, please open an issue and provide as much detail as possible, including steps to reproduce the bug.
*   **Feature Requests:** Suggest new features or improvements by opening an issue.
*   **Pull Requests:** The preferred method for contributing bug fixes and new features. Please follow the development workflow outlined below.

## 3. Development Workflow

Our development process prioritizes quality, efficiency, and alignment with the latest industry standards (December 2025).

### 3.1. Prerequisites

*   **Python:** Ensure you have Python 3.10+ installed.
*   **uv:** Install and use `uv` for package management and environment handling.
    bash
    curl -LsSf https://github.com/astral-sh/uv/releases/download/v0.1.17/uv-linux_x86_64.tar.gz | tar xz -C ~/.local/bin uv
    # Or follow official installation instructions: https://github.com/astral-sh/uv
    
*   **Git:** Familiarity with Git version control.

### 3.2. Environment Setup

1.  **Fork the Repository:** Fork `chirag127/Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine` to your GitHub account.
2.  **Clone Your Fork:** Clone your forked repository locally.
    bash
    git clone git@github.com:chirag127/Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine.git
    cd Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine
    
3.  **Create a Virtual Environment:** Use `uv` to create and activate a virtual environment.
    bash
    uv venv
    source .venv/bin/activate
    
4.  **Install Dependencies:** Install all development dependencies.
    bash
    uv install --frozen-lockfile
    

### 3.3. Making Changes

1.  **Create a New Branch:** Start a new feature branch for your contribution.
    bash
    git checkout -b feature/your-feature-name
    
2.  **Code:** Implement your changes, adhering to the project's coding standards and architectural principles (Modular Monolith, DRY, SOLID).
3.  **Test:** Write comprehensive tests for your changes using Pytest.
    bash
    pytest
    
4.  **Lint and Format:** Ensure your code adheres to our linting and formatting standards using Ruff.
    bash
    ruff check .
    ruff format .
    
5.  **Commit:** Commit your changes with clear and concise messages.
    bash
    git add .
    git commit -m "feat: Add new feature X and fix bug Y"
    

### 3.4. Submitting a Pull Request

1.  **Push Your Branch:** Push your feature branch to your fork.
    bash
    git push origin feature/your-feature-name
    
2.  **Open a Pull Request:** Navigate to the original repository (`chirag127/Crawl4AI-LLM-Optimized-Web-Crawler-And-Scraper-Python-Engine`) and open a new Pull Request from your feature branch.
3.  **Describe Your Changes:** Provide a clear and detailed description of your changes, referencing any related issues.
4.  **Review:** Your Pull Request will be reviewed by the maintainers. Be prepared to address feedback and make revisions.

## 4. Project Standards & Principles

*   **Architecture:** Modular Monolith, following principles of SOLID, DRY, and YAGNI.
*   **Language:** Python 3.10+.
*   **Package Management:** `uv`.
*   **Linting & Formatting:** `Ruff`.
*   **Testing:** `Pytest`.
*   **LLM Integration:** Focus on robust, error-handled interactions with LLM providers (e.g., OpenAI).
*   **Output Format:** Clean, structured Markdown.

## 5. AI Agent Directives

This project is designed to be understood and extended by AI agents. Refer to the `AGENTS.md` file for detailed directives, including the tech stack, architectural patterns, and verification commands.

## 6. Reporting Security Vulnerabilities

We take security seriously. If you discover a security vulnerability, please follow the guidelines in `.github/SECURITY.md`.

## 7. Questions?

If you have any questions, feel free to open an issue.

---