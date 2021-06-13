![Photo by <a href="https://unsplash.com/@jakobowens1?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jakob Owens</a> on <a href="https://unsplash.com/@halemade/likes?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  ](./images/jakob-owens-sOWoC7fA5DA-unsplash.jpg)

# film recommendations

**Authors**: <br>[Taylor Hale Robert](mailto:taylorhale11@gmail.com)
                <br>[Naomi Weinberger](mailto:weinberger.naomi@gmail.com)
                <br>[Harrison Gu](mailto:Harrison.s.gu@gmail.com)


## Overview

This project analyzes the climate over the last 20 years in the film industry. Descriptive analysis of film characteristics by film ROI shows that particular characteristics are common across the highest revenue films. Microsoft can use this analysis to determine the best direction for profitable product development and launch.

## Data Sources & Features

We worked across 3 different data sources for this anaylysis:

- IMDB data was used for our genre and director analysis
- TMDb, from which we used both the provided datasets and accessed the API
- The Numbers, as a provided data set

We used ROI as a metric for the majority of most of our analysis, in an effort to discern characteristics of films that most consistently yield valuable returns.
## Analysis

After our initial analysis revealed a positive correlation between hgih budget and high %ROI, we continued our analysis and created our visualizations based on a subset of films with budgets >= 100 mil. 

We broke out the data by budget, MPAA rating, genre, release timing and runtime to understand how these characteristics of the films varied agains %ROI. 

## Conclusions

This analysis leads to five recommendations for MS2021:

- **Produce films with a budget greater than 100mil** Films with the highest investments have the highest rate of return.
- **Pay attention to film MPAA rating** Films with the highest investments have the highest rate of return.
- **Work within the most popular genres.** Films with the highest investments have the highest rate of return.
- **Hire highly rated directors** Films with the highest investments have the highest rate of return.
- **Make films that run between 90-130 minutes.** Films outside of this range drop drastically in performance.
- **Release films on Friday, ideally in the months of March-April or November-December** ROI is highest during these periods, regardless of genre.

### Next Steps

Further analyses could yield additional insights and improve understanding of the industry:

- **Analyze the effect of streaming services on box office releases** This modeling could use already available data, such as breed and intake condition.
- **Explore relationship between physical location and film performance** 

## For More Information

See the full analysis in the [Jupyter Notebook](./2000-2020_film_analysis.ipynb) or review this [presentation](./Film_Recommendations_Presentation.pdf).

For additional info, contact the authors at:<br>
[Taylor Hale Robert](mailto:taylorhale11@gmail.com)
<br>[Naomi Weinberger](mailto:weinberger.naomi@gmail.com)
<br>[Harrison Gu](mailto:Harrison.s.gu@gmail.com)


## Repository Structure

```
├── code
│   ├── __init__.py
│   ├── data_preparation.ipynb
│   └── eda_notebook.ipynb
├── data
├── images
├── __init__.py
├── README.md
├── Film_Recommendations_Presentation.pdf
└── 2000-2020_film_analysis.ipynb
