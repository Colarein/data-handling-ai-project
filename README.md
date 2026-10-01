# Data Handling and Infrastructure for AI

This repository contains my project work for the **Data Handling and Infrastructure** module.

The project will focus on building an end-to-end machine learning system, with emphasis on data handling, storage, reproducibility, model development and deployment.

## Project Status

The final project idea and dataset are currently being reviewed and will be added once confirmed.

## Repository Structure

```text
data-handling-ai-project/
├── README.md
├── requirements.txt
├── notebooks/
│   └── project.ipynb
└── data/
    └── README.md
```

- `notebooks/` — main project notebook and analysis
- `data/` — dataset documentation and download/storage information
- `requirements.txt` — Python dependencies required to reproduce the project

## Setup

Create a virtual environment:

```bash
python3 -m venv .venv
```

Activate it on macOS/Linux:

```bash
source .venv/bin/activate
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Launch JupyterLab:

```bash
jupyter lab
```

Then open:

```text
notebooks/project.ipynb
```

## Data

Raw datasets will not be committed directly to this repository.

The `data/README.md` file will document the final dataset source, licence, download instructions and storage approach once the dataset has been confirmed.

## Reproducibility

Project dependencies are recorded in `requirements.txt` so that the Python environment can be recreated on another machine.

## Current Milestone

Milestone 1 — Data Source, ML Task and Storage Architecture.
