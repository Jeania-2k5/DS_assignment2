# 🎬 Movie Industry Analysis: ROI & Collaborations

This project was developed for a rookie movie producer to provide data-driven insights into the film industry. Using a dataset of 3,000 movies, this analysis explores profitability, language trends, and key professional networks (directors and actors) to guide investment and casting decisions.

## 📊 Key Features

  * **Profitability Analysis:** Identification of the highest-grossing films and their Return on Investment (ROI).
  * **Language Insights:** Discovery of which languages yield the highest average ROI (identifying high-performing international markets like Korean cinema).
  * **Professional Networking:** \* Mapping the top 3 producers by average ROI.
      * Identifying the most prolific actors (e.g., Samuel L. Jackson).
      * **Collaboration Mapping:** A visualization of the top 3 directors and their most frequent actor collaborators.

## 🛠️ Technical Stack

  * **Language:** Python 3
  * **Environment:** Google Colab / Jupyter Notebook
  * **Libraries:**
      * `pandas`: Data manipulation and cleaning.
      * `numpy`: Numerical operations and ROI calculations.
      * `matplotlib`: Data visualization (Bar charts, Histograms, Box plots).
      * `ast`: Parsing JSON-like strings in the metadata.

## 📁 Dataset Details

The analysis uses an IMDB dataset (`imdb_data (1).csv`) containing:

  * **Financials:** Budget and Revenue.
  * **Metadata:** Genres, Production Companies, Cast, and Crew.
  * **Calculated Metrics:** \* $Profit = Revenue - Budget$
      * $ROI = \frac{Profit}{Budget}$
