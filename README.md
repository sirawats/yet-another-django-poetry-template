<p align="center">
  <a href="https://www.djangoproject.com" target="blank"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqwPdqgkrKMfhAhX2gEAbLFfQK1T6r94FEZw&s" height="100" alt="django logo"/></a>
  <a href="https://python-poetry.org/" target="blank"><img src="https://python-poetry.org/images/logo-origami.svg" height="100" alt="uv logo" /></a>
  <a href="https://pre-commit.com/" target="blank"><img src="https://pre-commit.com/logo.svg" height="100" alt="pre-commit logo" /></a>
  <a href="https://github.com/astral-sh/ruff" target="blank"><img src="https://raw.githubusercontent.com/astral-sh/ruff/8c20f14e62ddaf7b6d62674f300f5d19cbdc5acb/docs/assets/bolt.svg" height="100" alt="ruff logo" style="background-color: #ef5552" /></a>
  <a href="https://bandit.readthedocs.io/" target="blank"><img src="https://raw.githubusercontent.com/pycqa/bandit/main/logo/logo.svg" height="100" alt="bandit logo" /></a>
  <a href="https://docs.pytest.org/" target="blank"><img src="https://raw.githubusercontent.com/pytest-dev/pytest/main/doc/en/img/pytest_logo_curves.svg" height="100" alt="pytest logo" /></a>
</p>

<p align="center">
  <a href="https://docs.docker.com/" target="blank"><img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" height="60" alt="Docker logo" /></a>
  <a href="https://github.com/features/actions" target="blank"><img src="https://avatars.githubusercontent.com/u/44036562" height="60" alt="GitHub Actions logo" /></a>
</p>

# yet-another-django-poetry-template

**yet-another-django-poetry-template** is a highly opinionated, modern FastAPI template designed to kickstart your next Python web application with best practices and a well-structured codebase. This template is built with a carefully selected stack of cutting-edge tools and libraries, aiming to provide an optimal balance of performance, maintainability, and developer productivity.

## Powered by

- 🐍 **Python 3.12**
  - Latest features for enhanced performance and productivity
  - Up to 10-60% faster than previous versions in certain benchmarks

- 📦 **[Poetry](https://python-poetry.org/)**
  - Modern Python dependency management and packaging tool
  - Handles virtualenv creation, package installation, and dependency resolution automatically
  - Lock file ensures reproducible installations across environments
  - Simple command-line interface for managing project dependencies




- 🎯  **[Django](https://www.djangoproject.com/)**
  - Robust, battle-tested web framework with "batteries included" philosophy
  - Built-in admin interface, ORM, authentication, and security features
  - Extensive ecosystem of reusable apps and middleware
  - Excellent documentation and large community support

- 🗃️ **[SQLAlchemy](https://www.sqlalchemy.org/)**
  - Powerful ORM with multi-database support and complex query capabilities
  - Performance optimization features and extensive ecosystem

- 🐘 **[Asyncpg](https://magicstack.github.io/asyncpg)**
  - High-performance PostgreSQL driver with async/await support
  - Up to 3x faster than psycopg2 for common operations

- 🔄 **[Alembic](https://alembic.sqlalchemy.org)**
  - Lightweight database migration tool with auto-generated migrations
  - Supports rollback, branching, and merging of migration scripts

- 🦀 **[Ruff](https://docs.astral.sh/ruff)**
  - Fast Python linter written in Rust, up to 100x faster than traditional linters
  - Supports auto-fixing and easy configuration with pyproject.toml

- 🧪 **[Pytest](https://docs.pytest.org)**
  - Robust testing framework with async support and powerful assertions
  - Rich ecosystem of plugins for extended functionality

- 🐳 **[Docker](https://www.docker.com/)**
  - Containerization solution for consistent environments across development and production
  - Simplifies deployment, scaling, and management of microservices

## Why Choose yet-another-django-poetry-template?

This template is perfect for developers who want to start a new Django project with a solid foundation, adhering to modern best practices. It abstracts the boilerplate setup and configuration, allowing you to focus on building features and writing clean, maintainable code. With this template, you'll have:


- A pre-configured development environment with Docker for easy setup.
- A robust and scalable architecture that follows best practices.
- Tools and configurations that enforce code quality and consistency.
- A seamless workflow for testing and deployment.

## Prerequisites
- [Python](https://www.python.org/downloads) (tested on 3.12)
- [uv](https://docs.astral.sh/uv/getting-started/installation/)
    ```bash
    # macOS and Linux
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
- [Docker](https://docs.docker.com/engine/install/) (optional)

## Getting Started

Clone the repository and follow the setup instructions to get your project up and running in minutes. Whether you're building a small API service or a complex, scalable application, **yet-another-django-poetry-template** is the perfect starting point for your next project.

#### 1. Install virtual environment and dependencies using Poetry
```bash
poetry install
```

#### 2. Copy environment variables
```bash
cp .env.example .env
```
## Development
- Create Django migrations
  ```bash
  poetry run python manage.py makemigrations
  ```

- Apply migrations
  ```bash
  poetry run python manage.py migrate
  ```

- Run development server
  ```bash
  poetry run python manage.py runserver
  ```

- Create a superuser
  ```bash
  poetry run python manage.py createsuperuser
  ```
