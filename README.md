# Oracle Arena: Predicting NBA Games

COSC 426 / 526 - Final Project
Due: May 2nd, 2025

This assignment focuses on using previous NBA statistics to predict the outcomes for a given game. We used the [NBA API](https://github.com/swar/nba_api) to collect data from the 2018 to recent seasons. We use a database that is inaccessible to the public, so we have provided CSV files with the most up-to-date data (May 2, 2025). We then use classical ML and Deep Learning techniques to predict the outcomes of the nba games.

## Links

- The Poster is provided as poster.pdf
- The Presentation is provided as presentation.pdf
- The Abstract will be provided on May 9th as paper.pdf, and it will also be submitted to Canvas.

## Installation

The deliverable for this assignment is a Jupyter notebook. You can install Jupyter Notebook by following the instructions [here](https://jupyter.org/install).

With conda, you can install the required packages by running the following command in your terminal:

```bash
conda create -n oracle python=3.11 
conda activate oracle
pip install -r requirements.txt
```

Or you can use regular Python3.11 and pip to install the required packages:

```bash
pip install -r requirements.txt
```

From here, you can run the Jupyter notebooks by opening the files in Jupyter Notebook and running the code cells.

## Usage

### Data collection

Feel free to run the cells in csv_population.ipynb. This takes a long time to run, so we have provided the csv files in the Data folder. The others in data_collection/ are not necessary to run, as they are just for creating the Data folder contents.

### Machine Learning

Model results are all in the data_extraction folder.

- Regular Season Win Predictions: winpred_reg.ipynb
- Playoff Win Predictions: winpred_playoff.ipynb
- Regular Season Total Score Predictions: pointspred_reg.ipynb
- Playoff Total Score Predictions: pointspred_playoff.ipynb

## Contact Information

This project was written by Ryan Peruski and Triton Eden, students at the University of Tennessee. If you have any questions, please feel free to reach out to Ryan at [this email](mailto:yhg461@vols.utk.edu)

## Acknowledgments

Thank you to the University of Tennessee department of EECS for providing the opportunity to learn and grow in the field of computer science, as well as our professor of this current class, Dr. Jack Marquez, and our TAs.
