
# 📊 Exploring GitHub Dataset with BigQuery & Colab

This project explores **GitHub repository metadata** using **Google BigQuery** and visualizes insights in **Google Colab** with `matplotlib` and `pandas`.
The analysis includes schema exploration, query optimization, and visualizations of repo features like languages, file sizes, commit messages, and README characteristics.

---

## 📂 Project Overview

* ✅ Learn to query BigQuery GitHub public dataset efficiently.
* ✅ Optimize SQL queries for performance.
* ✅ Visualize repo-related features (languages, file sizes, commit messages).
* ✅ Explore what makes a repo "good" (popularity via watch counts).
* ✅ Analyze the role of README files in repo popularity.

This work was completed as **Project 2** for a Database/Big Data course, using **Google Colab + BigQuery** integration.

---

## ⚙️ Technologies Used

* **Python 3**
* **Google Colab** (Jupyter-like environment)
* **Google BigQuery** (`google-cloud-bigquery`)
* **Matplotlib** (visualizations)
* **Pandas** (data manipulation for plotting)

---

## 📦 Installation & Requirements

Install dependencies locally (if not running on Colab):

```bash
pip install google-cloud-bigquery pandas matplotlib
```

Authenticate with Google Cloud before running queries:

```python
from google.colab import auth
auth.authenticate_user()
```

---

## ▶️ How to Run

1. Open the notebook (`2021_CE_58_project2.ipynb`) in **Google Colab**.
2. Authenticate with your **Google Cloud account**.
3. Replace `project_id` with your own project:

   ```python
   project_id = "your-gcp-project-id"
   ```
4. Run cells sequentially to:

   * Execute SQL queries (`%%bigquery` magic or `client.query()`)
   * Fetch results into Pandas DataFrames
   * Visualize using **matplotlib**

---

## 📊 Example Visualizations

The project produces charts such as:

* **Top 20 Languages by Repo Count** 📑
* **File Size Distribution** 📦
* **Commit Message Length Distribution** ✍️
* **Correlation Between README Length & Watch Count** 📈

---

## 📝 Key Learnings

* Query efficiency matters: Optimized queries cut down processing cost/time dramatically.
* Repo popularity is correlated with:

  * Popular programming languages used.
  * Concise but meaningful commit messages.
  * Presence & length of a **README.md** file.

---

## 👤 Author

**A.G. Hasan Zarook**
📍 University of Engineering and Technology, Lahore

