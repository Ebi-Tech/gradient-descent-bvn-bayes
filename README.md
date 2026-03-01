# gradient-descent-bvn-bayes

A small educational repository containing Jupyter notebooks that explore key concepts in gradient descent, bivariate normal distributions, and Bayesian inference. This project was created as part of a formative assessment (Formative 3) and includes example analyses using real-world datasets.

##  Repository Structure

```
Formative_3_Part_1.ipynb   # Gradient descent demonstrations
Formative_3_Part_2_.ipynb  # Bivariate normal distribution analysis
Formative_3_Part_4.ipynb   # Bayesian inference examples
Datasets/                  # CSV data files used in the notebooks
  ├─ AI_Impact_on_Jobs_2030.csv
  └─ IMDB Dataset.csv
README.md                  # This file
```

##  Getting Started

These notebooks can be executed using any Python environment with Jupyter support. We recommend using a virtual environment and installing dependencies via `pip`.

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ebi-Tech/gradient-descent-bvn-bayes.git
   cd gradient-descent-bvn-bayes
   ```
2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate      # macOS/Linux
   venv\Scripts\activate       # Windows
   ```
3. **Install required packages** (notebook kernels may already include common data science libraries):
   ```bash
   pip install -r requirements.txt
   ```
   If a `requirements.txt` file doesn't exist, the notebooks primarily rely on packages such as `numpy`, `pandas`, `matplotlib`, and `scipy`.
4. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```
   or
   ```bash
   jupyter lab
   ```
5. Open the notebooks from the Jupyter interface and run the cells sequentially.

##  Notebook Overview

- **Formative_3_Part_1.ipynb** – Demonstrates gradient descent algorithms, including visualization of loss function minimization and learning rate effects.
- **Formative_3_Part_2_.ipynb** – Analyzes bivariate normal distributions, computing correlations and plotting contour graphs of probability densities.
- **Formative_3_Part_4.ipynb** – Explores Bayesian inference techniques using datasets, such as estimating posterior distributions and applying Bayesian updates.

Each notebook contains explanatory text, code cells, and visualizations to assist with learning the underlying mathematics and programming techniques.

##  Datasets

The `Datasets/` folder includes sample data used within the notebooks:

- `AI_Impact_on_Jobs_2030.csv` – Hypothetical data related to AI's projected impact on employment sectors.
- `IMDB Dataset.csv` – A dataset of movie reviews often used for sentiment analysis tasks.

Feel free to add your own datasets or modify existing ones for experimentation.

##  Contribution

This project is primarily educational. Contributions can include:

- Improving notebook explanations
- Adding additional examples or datasets
- Fixing typos or formatting issues

Fork the repo, make your changes, and submit a pull request.

##  License

This repository is provided for educational purposes. No license is specified; treat it as [CC0](https://creativecommons.org/publicdomain/zero/1.0/) if you wish to reuse the content.

