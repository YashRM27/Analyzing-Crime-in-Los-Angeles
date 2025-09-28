# Analyzing-Crime-in-Los-Angeles

This project explores the **`crimes.csv`** dataset to identify crime
patterns across different dimensions such as time, location, and victim
demographics. The analysis uses **pandas**, **NumPy**, **matplotlib**,
and **seaborn** to clean, process, and visualize the data.

------------------------------------------------------------------------

## 🚀 Project Objectives

1.  **Peak Crime Hour**
    -   Identify the hour of the day with the **highest frequency of
        crimes**.\
    -   Store the result as an integer variable `peak_crime_hour`.
2.  **Night Crime Hotspot**
    -   Define *night crimes* as those occurring between **10:00 PM
        (22:00) and 3:59 AM (03:59)**.\
    -   Find the **area with the largest frequency of night crimes**.\
    -   Store the result as a string variable
        `peak_night_crime_location`.
3.  **Victim Age Group Analysis**
    -   Group crime victims into the following age brackets:
        -   `"0-17"`, `"18-25"`, `"26-34"`, `"35-44"`, `"45-54"`,
            `"55-64"`, `"65+"`\
    -   Count the number of crimes in each group.\
    -   Save as a pandas Series `victim_ages` with group labels as the
        index.

------------------------------------------------------------------------

## 📂 Dataset

The dataset is stored in **`crimes.csv`**.\
Important columns used: - `TIME OCC` → Time of occurrence of crime (HHMM
format). - `AREA NAME` → Name of the police jurisdiction area. -
`Vict Age` → Age of the victim.

------------------------------------------------------------------------

## 🛠️ Installation & Requirements

Install the required dependencies:

``` bash
pip install pandas numpy matplotlib seaborn
```

------------------------------------------------------------------------

## 📈 Results

-   **`peak_crime_hour`** → Hour with the highest crime frequency.\
-   **`peak_night_crime_location`** → Area with most crimes during night
    hours.\
-   **`victim_ages`** → Distribution of crimes across victim age groups.

------------------------------------------------------------------------

## ✅ Deliverables

-   Variables:
    -   `peak_crime_hour`
    -   `peak_night_crime_location`
    -   `victim_ages`
-   Visualizations: Hourly crime distribution.
