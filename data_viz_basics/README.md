# Data Visualization Practice (Matplotlib & Seaborn)

This repository contains practice code and exercises for learning **data visualization** in Python using [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/).

## 📊 Contents
The notebooks and scripts demonstrate how to:
- Create **line plots** to visualize trends over time.
- Build **bar charts** (simple, grouped, stacked) to compare categories.
- Use **histograms** to explore distributions (with multiple datasets).
- Plot **scatterplots** to study relationships between variables.
- Work with **regression plots** and customize scatterplots (jitter, alpha, size).
- Create **pie charts** for proportions.
- Customize **labels, titles, ticks, legends, and order** for clarity.
- Save figures in `.png` format for use in reports or presentations.

## 📂 Datasets
The exercises use small, illustrative datasets such as:
- **Flight data** (prices, miles, hours, passengers).
- **Chess games data** (`victory_status`, `winner`, etc.).
- **Rental prices** (StreetEasy NYC subset).
- **Water usage** (household consumption categories).
- Other toy datasets provided in CSV format.

## ⚙️ Project Structure
.
├── data_folder/                 # Contains raw datasets (CSV files) used in the exercises
├── saved_images/                # Output folder for saved charts (PNG format)
├── data_viz_basics_project.ipynb # Main notebook covering fundamental visualization concepts
├── plt_project.ipynb            # Additional practice notebook focusing on Matplotlib plotting
├── winning_word_lengths.png     # Example output image (saved from a figure)
├── README.md                    # Project documentation

## 🚀 How to Run
Clone the repo and install the required libraries:
```bash
pip install matplotlib seaborn pandas
