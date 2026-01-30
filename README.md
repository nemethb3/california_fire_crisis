# California Fire Crisis

## Overview
This project analyzes wildfire activity in California using publicly available wildfire data. The goal is to explore basic patterns such as fire size and acreage burned through simple summaries and visualizations. The project produces reproducible analysis outputs from the dataset.

---

## Data
The wildfire data used in this project comes from the following public source:

- BuzzFeed News Wildfire Trends (2018):  
  https://github.com/BuzzFeedNews/2018-07-wildfire-trends

The data is expected to be available locally at:

data/2018-07-wildfire-trends/

Data files are provided in tabular formats (e.g., CSV). This directory must exist for the analysis to run.

---

## Environment Setup
This project uses Python 3 and manages dependencies with `uv`.

From the project root, install dependencies and set up the environment:

uv sync
This command creates a virtual environment and installs all required dependencies based on uv.lock.

Reproducing Results
To reproduce a basic analysis result:

Ensure the wildfire data is present in data/2018-07-wildfire-trends/.

Activate the environment created by uv.

Run the analysis script or notebook from the project root.

The code will generate a summary output or visualization based on the wildfire data.

This reproduces a core result of the project using the provided dataset and environment.

Troubleshooting / Known Issues
Missing data: Confirm the wildfire dataset exists at the expected path.

Python version: Python 3 is required.

Dependency issues: If packages fail to install, ensure uv is installed and up to date.




---
This repository was created as part of the CMSE 492: Modern Tools for the Data Science Professional course at Michigan State University in Spring 2026 with the assistance of the Codex AI agent.
