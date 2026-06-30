# Analyzing Crime in Los Angeles

A data analysis project exploring 185,000+ LAPD crime records to identify when crimes are most likely to occur, where nighttime crimes concentrate, and which demographics are most frequently affected, supporting the kind of resource allocation decisions a police department would actually use to deploy patrols and prevention efforts.

## Overview

Conducted in Python using pandas for data cleaning and transformation, including parsing military time into usable hour values and binning continuous victim ages using `pd.cut()`. Visualized with matplotlib across six distinct chart types: bar charts, a density curve, a box plot, and a lollipop chart.

## Key Insights

- **Peak crime hour:** 12:00 PM — crime activity peaks at midday rather than overnight, a counterintuitive finding with direct implications for patrol scheduling.
- **Peak nighttime crime area:** Central division (10pm–3:59am window) — also ranks among the top areas for overall crime volume.
- **Most affected age group:** 26-34, accounting for over 47,000 incidents, nearly double the 18-25 group.
- Victim age distribution is broadly similar across sex, with differences mainly in outliers rather than central tendency.

## Tools Used

- Python (pandas, matplotlib)
- DataCamp DataLab

## Dataset

Modified version of the LA Open Data crime dataset, provided via DataCamp (185,715 rows, 12 columns).

## Visualizations

Six visualizations were built for this analysis: a bar chart of victims by age group, a density curve of victim age distribution, a box plot of victim age by sex, a bar chart of crimes by hour of day, a horizontal bar chart of the top 10 most common crime types, and a lollipop chart of the top 10 areas by crime count.

[View all visualizations on DataCamp →](https://www.datacamp.com/datalab/w/f319beac-aaaa-4104-8c91-9c1f774176a4/edit)
