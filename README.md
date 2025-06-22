Movie Data Correlation Project

This project investigates financial patterns in the film industry by analyzing a dataset of over 7,000 movies. The primary objective was to identify how specific features, such as budget, genre, and score, relate to a movie’s gross revenue. All work was conducted using Python, leveraging libraries like Pandas and NumPy for data manipulation, and Seaborn and Matplotlib for statistical visualization.

The dataset was imported from a CSV file and cleaned by identifying and managing missing values. Columns with float types were converted to integers where appropriate, and object-type features were encoded into numerical categories to support correlation calculations. The data was sorted and filtered to highlight top-grossing films, followed by the removal of duplicate production companies to avoid skewed visualizations.

A strong positive correlation was identified between a film’s budget and its gross revenue, with a Pearson coefficient of 0.74. Similarly, the number of votes a film received also showed a notable correlation with revenue (0.63), suggesting that public engagement is a significant indicator of box office performance. These relationships were visualized using both scatter plots and regression lines to highlight trends. Further insights were obtained through a full correlation matrix and heatmap, revealing how various movie attributes interact with one another.

This analysis demonstrates how accessible Python libraries and exploratory data techniques can be used to uncover meaningful business trends. It offers insight into the importance of investment size, audience approval, and other quantifiable factors that can influence financial outcomes in the entertainment sector.

The project was completed in Jupyter Notebook and utilizes a tech stack that includes Python, Pandas, NumPy, Seaborn, and Matplotlib.
