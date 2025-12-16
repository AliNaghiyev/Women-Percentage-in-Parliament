# Women-Percentage-in-Parliament

## Overall Structure
This project analyzed the percentage of the women in the national parliaments. The data was taken from [Link](https://data.ipu.org/women-ranking/?date_year=2025&date_month=11) (as it stands for November). The countries that do not have any national parliament are not included in the list for the robustness. Several visualizations were used for this project, including Top10 highest percentage countries and Top10 worst percentge countries.

## Technologies
1.Pandas (Python Library): Pandas was used for data manipulation, data cleaning of the raw file.

2.Numpy (Python Library): Numpy was used for handling empty rows and <br> np.nan <br> played an important role

3.Excel: Excel was used for controlling the data after cleaning. Colab does not allow to view all the rows/columns, therefore Excel allowed to view the data fully. If needed, <br> find&replace <br> function of excel was used

4.Power BI: Power BI was used for transforming data using power query. DAX formulations and visualizations made the report understandable. Also the slicer visualization allows the user to seelct custom columns

# Results
**The results can be viewed in [Results](https://github.com/AliNaghiyev/Women-Percentage-in-Parliament/blob/main/Reports/Women%20Percentage%20in%20Parliament.pdf), short desciptions are below**

*1: **The countries that are unicameral (has only 1 parliament) has less women in their parliament compared to bicameral** (countries that have 2 parliaments, e.g, Great Britain) with a slight difference.

*2: In bicameral countries, higher parliament (chamber 2) contains more woman than chamber 1. However, the percentage is less than 30 for both of the chambers.

*3: Interestingly, the countries that have serious econmic problems such as **Rwanda, Cuba and Nicaragua prefer women in their parliaments**. **Bolivia, Australia, Mexico, Andorra, UAE are the other countries that at least half of the parliament members are women**.

*4: In total, **4 countries do not have any women member in parliament**. 2 of them of South American countries (Argentina and Venesuela). Argentina is the only bicameral country that has this property.

### Important codes
[Colab codes that are used for cleaning the data](https://github.com/AliNaghiyev/Women-Percentage-in-Parliament/blob/main/Jupyter%20codes/Women_in_Parliament.ipynb)
