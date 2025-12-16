# Women-Percentage-in-Parliament

## Overall Structure
This project analyzed the percentage of the women in the national parliaments. The data was taken from https://data.ipu.org/women-ranking/?date_year=2025&date_month=11 (as it stands for November). The countries that do not have any national parliament are not included in the list for the robustness. Several visualizations were used for this project, including Top10 highest percentage countries and Top10 worst percentge countries.

## Technologies
Pandas (Python Library): Pandas was used for data manipulation, data cleaning of the raw file. The cell <br>
import pandas as pd
import numpy as np
df=pd.read_csv('Women Percentage in National Parliament.csv', skiprows=15)
df.head() <br>
