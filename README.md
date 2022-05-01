# Module_6_Repo

# The purpose of this project is to calculate and plot the housing units per year and average sale price per square foot. In the project I also made an interative map. This is all in order to find viable property investments in the San Francisco area. 
---

## Technologies

# This project is written with the programming language python. It also uses the libraries Pandas, hvplot, and pathlib. The project was written on the Windows operating system.
---

## Installation Guide

```
sfo_data_df = pd.read_csv(
    Path("./Resources/sfo_neighborhoods_census_data.csv"))
display(sfo_data_df.head())
display(sfo_data_df.tail())
```

## Usage

```
all_neighborhoods_df.hvplot.points(
    'Longitude',
    'Latitude',
    geo = True,
    size = 'sale_price_sqr_foot',
    color = 'gross_rent',
    title = 'Neighborhoods Visualization',
    frame_width = 700,
    frame_height = 500
)
---

## Contributors


# Creator of this project is Thomas Burns
# Email is burns235577@gmail.com
---







