# Big Data Customer Segmentation

This project leverages Apache Spark to analyze transactional data from an online retail store, aiming to uncover actionable insights into customer behavior and enable data-driven marketing strategies.

## Dataset

- **Source:** [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Size:** 541,909 transactions

## Objective

Segment customers based on their purchasing patterns using Recency, Frequency, and Monetary Value (RFM) analysis.
## Getting Started

### Requirements

- Python 3.8+
- Apache Spark 3.5.5
- Java 8
- Jupyter Notebook or Google Colab

### Installation

```sh
# Install Java and Spark (for Colab)
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!wget -q https://dlcdn.apache.org/spark/spark-3.5.5/spark-3.5.5-bin-hadoop3.tgz
!tar xf spark-3.5.5-bin-hadoop3.tgz
!pip install -q findspark openpyxl
```

### Usage

1. Upload the dataset (`Online Retail.xlsx`) to your notebook/Colab environment.
2. Run the notebook or the script.
3. Outputs include:
    - Data cleaning summary
    - RFM segmentation
    - Top revenue countries
    - Most sold items
    - Monthly trends

## Example Results

- **Top Countries by Revenue:**
    - United Kingdom: £7,308,391
    - Netherlands: £285,446
- **Most Sold Items:** (see notebook for details)

## Project Structure

- `README.md` — Project overview and instructions
- `DSAI4202_Big_Data_Project_Sana_Duha.ipynb` — Main analysis notebook
- `DSAI4202 Information Retrieval Duha and Sana.pdf` — Report
