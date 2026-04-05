# 🎬 Movie Industry Analysis: ROI & Collaborations

This project provides data-driven insights for a rookie movie producer to guide investment and casting decisions. By analyzing a dataset of 3,000 movies, we identify trends in profitability, global market performance, and professional collaboration networks.

## ❓ Business Questions Addressed

The analysis was designed to answer the following specific questions:

1.  **Which movie made the highest profit?** Who were its producer and director? Identify the actors in that film.
2.  **Global ROI Trends:** This data has information about movies made in different languages. Which language has the highest average ROI (return on investment)?
3.  **Genre Diversity:** Find out the unique genres of movies in this dataset.
4.  **Industry Power Players:** Make a table of all the producers and directors of each movie. Find the top 3 producers who have produced movies with the highest average RoI?
5.  **Star Power Analysis:** Which actor has acted in the most number of movies? Deep dive into the movies, genres, and profits corresponding to this actor.
6.  **The "Dream Team":** Top 3 directors prefer which actors the most?

## 📊 Key Findings

  * **Highest Profit Movie:** *Furious 7* with a profit of **$1,316,249,360**.
  * **Most Profitable Language:** **Korean (ko)** cinema shows the highest average ROI in this dataset.
  * **Most Prolific Actor:** **Samuel L. Jackson**, appearing in the highest frequency of films.
  * **Top ROI Producer:** **Charles Chaplin Productions**.

## 🛠️ Technical Stack

  * **Language:** Python 3
  * **Environment:** [Google Colab](https://colab.research.google.com/drive/1kqGB-0F07pJeaI91XUKuwC7YjeKTy421)
  * **Key Libraries:**
      * `pandas` & `numpy`: Data cleaning and ROI calculations.
      * `matplotlib`: Data visualization (Histograms, Box plots, and Grouped Bar Charts).
      * `ast`: Used `ast.literal_eval` to parse complex JSON-formatted strings in the `cast` and `crew` columns.

## 📈 Visualizations

The project includes several key plots to visualize the data:

  * **Top 10 Profitable Movies** (Horizontal Bar Chart)
  * **ROI Distribution for Top Producers** (Scatter Plot)
  * **Profit Distribution for Lead Actors** (Histogram & Box Plot)
  * **Director-Actor Collaboration Matrix** (Multi-category Bar Chart)
