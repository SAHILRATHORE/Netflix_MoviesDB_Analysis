# 🎬 Netflix Movie Analysis

This project explores and analyzes a dataset of Netflix movies to
uncover insights such as popularity trends, genre distribution, and
audience ratings. Using **Python, Pandas, Matplotlib, and Jupyter
Notebook**, we perform data cleaning, aggregation, and visualization to
better understand the content available on Netflix.

------------------------------------------------------------------------

## 📌 Features

-   **Data Cleaning & Preprocessing**
    -   Handling missing values\
    -   Formatting release dates\
    -   Preparing categorical and numerical data
-   **Exploratory Data Analysis (EDA)**
    -   Most common genres on Netflix\
    -   Popularity trends over time\
    -   Average popularity, votes, and ratings grouped by genre\
    -   Identifying the most popular movies
-   **Visualizations**
    -   Bar charts of genre distributions\
    -   Popularity vs. genres\
    -   Average ratings and vote counts per genre

------------------------------------------------------------------------

## 📂 Dataset

The dataset (`mymoviedb.csv`) contains information about Netflix movies
with the following key features:\
- **Release_Date** -- Movie release date\
- **Title** -- Movie title\
- **Popularity** -- Popularity score\
- **Vote_Count** -- Number of audience votes\
- **Vote_Average** -- Average rating\
- **Genre** -- Movie genre(s)

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 3\
-   Pandas\
-   Matplotlib / Seaborn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone the repository:

    ``` bash
    git clone https://github.com/your-username/Netflix-Analysis.git
    cd Netflix-Analysis
    ```

2.  Create a virtual environment & activate it:

    ``` bash
    python -m venv .env
    source .env/bin/activate   # Mac/Linux
    .env\Scripts\activate      # Windows
    ```

3.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

4.  Open the notebook:

    ``` bash
    jupyter notebook NetFlix_movie.ipynb
    ```

------------------------------------------------------------------------

## 📊 Sample Insights

-   The most common genres on Netflix are **Action, Drama, and
    Adventure**.\
-   **Spider-Man: No Way Home** is the most popular movie in the
    dataset.\
-   Average popularity varies significantly across genres, with
    **Science Fiction and Action** leading.

------------------------------------------------------------------------

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!

------------------------------------------------------------------------

## 📜 License

This project is licensed under the **MIT License**.
