# Does it rain more in Seattle, WA or Medford, OR? 


---

## Project Overview

The purpose of the project is to figure out whether it rains more in Seattle, WA or Medford, OR. This project will be utilizing the precipitation data from the NOAA Global Historical Climatology Network (GHCND). 


- **Objective:** Using data find out whether it rains more in Seattle, WA or Medford, OR.
- **Domain:** Climate Data Analysis
- **Key Techniques:** Statistical testing

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND This is the link for the site containing the daily weather observations from different cities and stations across the United States.
- **Description:** The dataset include the following columns: Date, Station ID, PRCP (precipitation)
- **License:** (if applicable)

---

## Analysis

The analysis compared precipitation between Medford, OR and Seattle, WA using several visualization and statistical techniques. The fist visualization was a line plots to show trends in precipitation over time, providing a visual representation of how rainfall fluctuates throughout the year.Bar plots were used to show the mean monthly precipitation for each city, which highlight the seasonal differences. Lastly, Boxplot show the distribution and variability of rainfall across months, including outliers and median values.  Finally, independent t-tests were conducted for each month to determine whether the differences in mean precipitation between the two cities were statistically significant.

---

## Results

Based on the analysis, Seattle receives more rain through out the year when compared to medford. While Seattle precipitation varies significantly compare to Medford, both cities show a seasonal pattern where more rain is observed during the winter compared to the summer. Therefore, to answer the question, "Does it rain more in Seattle, WA or Medford, OR?", the answer is, yes Seattle receives more precipitation throught the year.

---

## Authors

- Njenga Gakwa - [@jngakwa](https://github.com/jngakwa)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used
- Tutorials or papers referenced
- Inspiration or collaborators
