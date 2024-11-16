# Basic Programming Teacher Assistant (BP TA)

Welcome to the **Basic Programming Teacher Assistant** repository! This project showcases my journey and workflow as a TA for Basic Programming (BP), where I support students and analyze their submissions using Python. Below are the details of the workflow, the tools I use, and a description of the provided code.

---

## Table of Contents
1. [Overview](#overview)
2. [Workflow](#workflow)
3. [Tools and Technologies](#tools-and-technologies)
4. [Code Description](#code-description)
5. [How to Use](#how-to-use)
6. [License](#license)

---

## Overview

As a Basic Programming Teacher Assistant, I streamline the process of student data management and analysis. My main responsibilities include:

- Collecting student data via Google Forms.
- Extracting and processing the data from Google Sheets.
- Performing clustering analysis using Python.
- Visualizing data (previously using Elasticsearch and Kibana).

---

## Workflow

1. **Data Collection**: Students fill out a Google Form.
2. **Data Extraction**: The form responses are automatically saved in a Google Sheet.
3. **Data Analysis**: I use Python to analyze the data, particularly clustering to group students based on their responses.
4. **Visualization**: Previously, I visualized the data on platforms like Elasticsearch and Kibana.

---

## Tools and Technologies

- **Python**: For data analysis and clustering.
- **Google Forms**: To collect student information.
- **Google Sheets**: For data storage and easy access.
- **Elasticsearch and Kibana**: For visualizing data (used earlier in the workflow).
- **Libraries**: Pandas, Scikit-learn, Matplotlib, and more for analysis and clustering.

---

## Code Description

The provided Python script implements the clustering workflow:

1. **Data Extraction**:
   - Connects to the Google Sheets API to retrieve student responses.
   - Cleans and preprocesses the data for analysis.

2. **Clustering**:
   - Uses algorithms such as K-Means (or similar) from Scikit-learn to group students.
   - Determines optimal clusters using methods like the Elbow Method.

3. **Output**:
   - Saves the clustering results.
   - (Optional) Exports visualizations or additional processed data.

You can find the script in this repository as `Clustering-students.py`. Please ensure the necessary dependencies are installed to run it.

---

## How to Use

### Prerequisites

1. Install Python (3.8 or later).
2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```
3. Set up access to your Google Sheets data (e.g., using OAuth credentials if needed).

### Running the Script

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```

2. Run the script:
   ```bash
   python Clustering-students.py
   ```

3. Follow any prompts for API keys or file paths.

