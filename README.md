# 🎬 IMDb Top 1,000 Movies: Comprehensive Exploratory Data Analysis & Franchise De-Biasing

A comprehensive exploratory data analysis of the IMDb Top 1,000 canonical film catalog spanning a full century of global cinema (1920–2020) and $56.53 Billion in cumulative box office revenue. This project investigates cinematic intelligence, box office revenue concentration, runtime duration economics, genre prevalence, and franchise-versus-standalone intellectual property performance.

---

## 📑 Project Deliverables

- **📄 Full Technical Report (PDF):** [`IMDb_Top_1000_Comprehensive_EDA_Report.pdf`](./IMDb_Top_1000_Comprehensive_EDA_Report.pdf)
- **💻 Analysis Notebook:** [`IMDB_Top_1000_Phase I & II.ipynb`](./IMDB_Top_1000_Phase%20I%20&%20II.ipynb)
- **📊 Dataset Source:** [IMDb Top 1000 Movies Dataset on Kaggle](https://www.kaggle.com/datasets/harshitshankar/imdb-dataset-of-top-1000-movies-and-tv-shows)

---

## 📌 Dataset Overview

- **Records:** 1,000 canonical film releases
- **Attributes:** 16 raw features spanning titles, release years, MPAA certifications, runtimes, multi-label genres, ratings, critic scores, directors, billing cast, votes, and box office gross
- **Geographic & Cultural Coverage:** 100 Years of Global Cinema (1920–2020)
- **Cumulative Financial Volume:** $56.53 Billion Total Theatrical Gross

---

## 🔍 Key Findings & Insights

* **The Franchise Distortion Hypothesis:** Serialized franchise IP commands a **13.05× median gross premium** over pure standalone films ($210.61M vs. $16.14M), capturing 42.4% of total box office revenue despite representing only 11.3% of catalog volume.
* **Critic vs. Audience Disparity:** Professional critic scores (Metascore) exhibit a weak linear correlation (**r = 0.27**) with mainstream audience ratings, showing that critical acclaim is a poor predictor of mass ticket sales.
* **The Epic Runtime Ceiling:** Expanding runtimes from Compact (<100m) to Extended (120–140m) drives strong revenue compounding (+283% then +64%), but entering the Epic tier (>140m) results in a flat plateau (**$36.9M median**) as longer durations eliminate daily screening turnover slots.
* **Asymmetric Genre Multipliers:** Serialized IP heavily distorts genre performance, led by Animation (**19.55× multiplier**) and Comedy (**17.04× multiplier**). Biography (**$36.80M standalone median**) was identified as the optimal non-IP commercial hedge.
* **Universal Correlation Deflation:** Removing franchise blockbusters deflates the global rating-to-gross correlation shift by **$\Delta r = -0.088$**, proving that aggregate catalog metrics are artificially inflated by blockbuster tentpoles.

---

## 📈 Strategic Studio Slate Optimization Model

Studio greenlight committees must abandon single-catalog averages and deploy a bifurcated capital allocation framework:
- **Tier 1 (IP Franchise Engine — ~20% Volume / ~65% Capital):** Focus on Action, Adventure, and Animated IP continuations utilizing extended runtimes (120–150+ min) to capture premium large-format surcharges.
- **Tier 2 (Standalone Portfolio — ~80% Volume / ~35% Capital):** Focus on Biographical Drama, Crime, and Character Studies. **Strictly enforce the Standalone Epic Runtime Cap (100–130 min)** to protect daily theatrical screening turnover.

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.x
- **Core Libraries:**
  - `pandas` & `numpy` (Data cleaning, regex parsing, and schema transformation)
  - `matplotlib` & `seaborn` (Visual analytics dashboards and distribution plots)
  - `reportlab` (Programmatic layout and generation of publication-ready PDF reports)

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/khashayarm13/imdb-top-1000-eda.git](https://github.com/khashayarm13/imdb-top-1000-eda.git)
   cd imdb-top-1000-eda
Download the dataset:
Place imdb_top_1000.csv into the root project directory.

Install required packages:

Bash
pip install pandas numpy matplotlib seaborn reportlab jupyter
Run the Notebook:

Bash
jupyter notebook "IMDB_Top_1000_Phase I & II.ipynb"
👤 Author
Name: Khashayar Mohammadi

GitHub: @khashayarm13