# India's Renewable Energy Generation (2017–2025)

An interactive Tableau dashboard exploring how India's renewable energy generation has changed over time, by source and by year.

**[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/mehar.naaz/viz/IndiasRenewableEnergyGeneration2017-2025/Dashboard1)**

![Dashboard screenshot](image/dashboard.png)

## Why I built this

During my MS in Data Science, my research project focused on forecasting India's state-wise renewable energy generation. For this project, I took the same data and turned it into a dashboard that anyone can explore without needing to read a report.

## What the dashboard shows

1. **Monthly generation by source:** how each renewable source has moved month to month
2. **Wind vs solar by year:** how the two biggest growth sources compare
3. **2024 source shares:** which sources made up the largest portion of generation in 2024
4. **Large Hydro from March 2023:** the effect of Large Hydro being classified as renewable from this date

## Key insights

- Solar and Wind are the most contributing sources while recent data shows that solar climbed above wind in generation per year.
- Solar completely overtook wind in 2024 data reports 
- Large Hydro is a pretty big contributor but it was not recognized as renewable energy which led to be its data being excluded from earlier reports.

## Data

- **Source:** https://mnre.gov.in/
- **Coverage:** monthly generation by source, 2017–2025
- **Unit:** MU (million units)
- **Note on Large Hydro:** it was not classified as renewable before March 2023 in the source, so totals before and after that date are not directly comparable unless it is excluded.

## Data preparation


## Tools

- Tableau Public (dashboard)
- [Excel / Python (pandas)]

## Repository structure

```
├── data/          # cleaned dataset (or link to the original source)
├── images/        # dashboard screenshots
└── README.md
```

## About me

I'm Mehar Naaz, a Data Science graduate (MS) with a background in bioinformatics and microbiology, building my skills in data analysis and visualization. I'm interested in applying data science to biology and sustainability.

- LinkedIn: www.linkedin.com/in/meharnaaz
- Tableau: https://public.tableau.com/app/profile/mehar.naaz/vizzes
