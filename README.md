# 🎬 Netflix Movies Analysis

![Python](https://1688370117923.png?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

> Exploratory data analysis of Netflix movies to uncover trends in content distribution, genre popularity, ratings, and viewer preferences.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Dataset](#-dataset)
- [Tech Stack](#-tech-stack)
- [Analysis Performed](#-analysis-performed)
- [Key Insights](#-key-insights)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 Overview

Netflix hosts thousands of movies and TV shows across a wide range of genres and countries. This project performs an in-depth exploratory data analysis (EDA) on Netflix movie data to understand content trends, identify popular genres, and analyze release patterns over time.

The goal is to extract actionable insights that can help understand Netflix's content strategy and audience preferences.

---

## 🎯 Problem Statement

Streaming platforms like Netflix continuously expand their content libraries. Identifying which genres perform well, how release trends have evolved, and what kinds of content dominate the platform can provide valuable insights for:

- **Content strategists** looking to understand platform trends
- **Data enthusiasts** exploring real-world streaming data
- **Researchers** studying digital media consumption patterns

---

## 📊 Dataset

The dataset contains metadata for Netflix movies, including the following features:

| Feature | Description |
|---|---|
| `Title` | Movie name |
| `Release Year` | Year the movie was released |
| `Genre` | Movie genre(s) |
| `Duration` | Runtime in minutes |
| `Rating` | Content rating (e.g., PG, R, TV-MA) |
| `Country` | Country of origin |
| `Director` | Director(s) of the movie |
| `Cast` | Main cast members |

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.8+** | Core programming language |
| **Pandas** | Data manipulation and preprocessing |
| **Matplotlib** | Static visualizations |
| **Seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 🔍 Analysis Performed

The following analyses were carried out:

- **Release Trend Analysis** — Number of movies released per year
- **Genre Distribution** — Most common genres on the platform
- **Rating Distribution** — Breakdown of content ratings
- **Top Directors** — Directors with the most titles on Netflix
- **Duration Analysis** — Distribution of movie runtimes
- **Country-wise Distribution** — Geographic breakdown of content

---

## 💡 Key Insights

- 📈 **Rising Content Volume** — Netflix has significantly increased its movie releases in recent years, reflecting aggressive content expansion.
- 🎭 **Genre Dominance** — Drama and Comedy are the most prevalent genres, collectively making up a large share of the catalog.
- 🎬 **Director Concentration** — A small number of directors contribute multiple titles, suggesting strategic partnerships or franchise content.
- ⏱ **Standard Runtimes** — Movie durations are largely clustered within the typical feature-length range (80–120 minutes).
- 🌍 **US-Centric, but Growing Globally** — While the US dominates in volume, international content from India, UK, and other regions is growing steadily.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/netflix-movies-analysis.git
   cd netflix-movies-analysis
   ```

2. **Create a virtual environment** *(optional but recommended)*
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. Open `netflix_analysis.ipynb` and run the cells.

---

## 📁 Project Structure

```
netflix-movies-analysis/
│
├── data/
│   └── netflix_movies.csv        # Raw dataset
│
├── notebooks/
│   └── netflix_analysis.ipynb    # Main analysis notebook
│
├── visuals/
│   ├── movies_per_year.png
│   ├── genre_distribution.png
│   ├── rating_distribution.png
│   ├── top_directors.png
│   └── duration_distribution.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the analysis or add new features:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ using Python & Jupyter Notebook</p>
