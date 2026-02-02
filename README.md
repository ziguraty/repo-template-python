# README

Short sentence describing what this project does and who it is for.

## Context & Problem

Explain *why* this exists.

* What problem does it solve?
* Who uses it?
* What process does it automate or improve?

Example:

> This project automates the extraction and normalization data from an API, generating a clean CSV for analysis and dashboards.

## Features

Bullet list of what the project does.

* Fetches data from source X.
* Validates and cleans records.
* Generates CSV / JSON output.
* Logs failures.

This is for *non-technical readers*.

## Prerequisites

These should be **identical in almost all repos**:

- [Python 3.10+](https://www.python.org/).
- [Poetry](https://python-poetry.org/docs/#installation).

## Setup

Clone the repo and install dependencies:

```bash
# clone the repo
git clone <repo-url>
cd <project>

# create env file
cp .env.example .env

# install dependencies
poetry install

# activate virtual env
eval $(poetry env activate)
```

## Task

To see all project's tasks.

```bash
# Need virtual environment activated
# otherwise run 'poetry run task list'
task list
```

