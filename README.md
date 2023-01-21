# Excel-PivotTables

A deep dive into Excel Pivot Tables, specializing on Data Analytics, using an IMDb dataset from a Udemy led course.

## Section 1: Excel Pivot Tables 101

* 1) First show the Budget of each movie Title in rows with filters for Country and Language that are set to Japan and English respectively. Out of all of the movies produced in English, how many of the movies were Japanese movies? !

* 2) Clear the Language filter, set the Country filter to Denmark, and pull in Gross Revenue as a second metric. How much gross revenue did "The Celebration" generate?

* 3) Use the "Clear All" command in the PivotTable Analyze options to remove all fields from the table, and create a new view showing Gross Revenue by Country (as rows) and Genre (as columns). How much revenue was generated by Comedy films in Finland?

* 4) Remove the Country field, move Genre to the row labels, and drag in Rating as secondary row labels. How much revenue was generated by PG-rated Family films? Double click on the cell to see the exact source data populating the value. Which title drove most of the revenue?

* 5) Add a fake row of data in the "IMDb Movie Database" tab, beneath the existing rows, and use the Change Data Source option to update the pivot. Create a title-level view and confirm that the new data is included, then delete the entire row in the raw data sheet and refresh the Pivot Table to remove it.

|Budget by Title|Budget/GR by Country, Genre and Title|
|:-:|:-:|
|![Budget by Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/TitleBudgetPivotTable.png?h=350&w=630)|![Budget/GR by Country, Genre and Title](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/BudgetGROnCountryGenreTitle.png?h=350&w=630)|
|Horror Films GR by Country|USA B&W Films GR by Genre and Rating|
|![Horror Films GR by Country](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnCountryByGenre.png?h=350&w=630)|![USA B&W Films GR by Genre and Rating](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/GROnGenreRatingByCountryB&W.png?h=350&w=630)|

### Add a row and a column to the raw dataset

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section1HomeworkPics/Section1.5HomeworkPic.png?w=1260">
</p>

## Section 2: Formatting Excel Pivot Tables

* 1) Show Budget and Gross Revenue by Title, and change the number format to currency, with a dollar sign and no decimal places. What was the budget for "A Passage to India"?

* 2) Remove Budget and Title, and show Gross Revenue by Genre (rows) and Rating (columns). Update the PivotTable options to show "$0" instead of blank values

* 3) Move Rating to the row labels (beneath Genre), change your table layout to Outline View, and Update your column headers from "Rating" to "Film Rating", and from "Sum of Gross Revenue" to "Gross Revenue" (hint: you may need a trailing space)

* 4) Remove Film Rating from the view, so that you're just viewing Gross Revenue by Genre. Turn Grand Totals off, select the Gross Revenue values, format as currency (if they aren't already) and add a Color Scale from Green (high) to Red (low). Which Genre produced the most Gross Revenue?

* 5) Add a second instance of Gross Revenue, and format the new column with Data Bars. Update the number format to make the text invisible, so that only the bars appear. Which Genre produced the second-highest Gross Revenue total in the sample?

|A Passage To India GR|Replace Blank Values w/ $0|
|:-:|:-:|
|![A Passage To India GR](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.1HomeworkPic.png?h=350&w=630)|![Replace Blank Values w/ $0](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.2HomeworkPic.png?h=350&w=630)|
|Horror Films GR by Country|USA B&W Films GR by Genre and Rating|
|![Horror Films GR by Country](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.3HomeworkPic.png?h=350&w=630)|![USA B&W Films GR by Genre and Rating](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.4HomeworkPic.png?h=350&w=630)|

### Visualizing Gross Revenue with Color Values and Data Bars

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section2HomeworkPics/2.5HomeworkPic.png?w=1260">
</p>

## Section 3: Use Pivot Tables to Sort, Filter and Group Data

* 1) Create a view showing Gross Revenue by Title, with a filter for Year to only include films released in 2005, 2006, 2007 or 2008, then sort the titles descending by Gross Revenue. What's the top-grossing film released during that 4-year sample? (Note: if the Release Dates don't auto-group, you will need to use the "Group" tools in the Analyze tab or create a new column in your raw data to extract the year from the Release Date column)

* 2) Add a Label Filter to only include titles that end in "2". How many sequels were released during these years? Which earned the most Gross Revenue?

* 3) Clear your label filter, and add a Value Filter to only show titles that earned between $1,000,000 and $3,000,000 in Gross Revenue. How many titles fell into this range?

* 4) Adjust your PivotTable Options to allow multiple filters, then add a label filter to only show movies that start with the letter "M". How many titles are now listed?

* 5) Add a wildcard to your label filter to only show titles that start with the letter "M" and also contain the letter "s", separated by any number of characters. Which titles are returned?

|Top Grossing Title from 2005-2008|Top Grossing Title ending in "2"|
|:-:|:-:|
|![Top Grossing Title from 2005-2008](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section3HomeworkPics/3.1HomeworkPics.png?h=350&w=630)|![Top Grossing Title ending in "2"](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section3HomeworkPics/3.2HomeworkPics.png?h=350&w=630)|
|Which Titles earned from 1-3mm|Which Titles start with the letter "M"|
|![Which Titles earned from 1-3mm](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section3HomeworkPics/3.3HomeworkPics.png?h=350&w=630)|![Which Titles start with the letter "M"](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section3HomeworkPics/3.4HomeworkPics.png?h=350&w=630)|

### Titles that start with "M" and contain "s" 

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section3HomeworkPics/3.5HomeworkPics.png?w=1260">
</p>

## Section 4: How to Enrich Data with Calculated Values and Fields

* 1) Create a view to show IMDb Score by Title. What happens when you replace Title with Genre? How can you fix this issue? (hint: look at the summarization type...)

* 2) Update your view to show Average IMDb Score by Genre (primary row labels) and Year (secondary row labels), for 2011-2014. Drag in a second instance of IMDb Score, change the summarization to Average, and show the values as a Rank (large to small) based on the year. Which year in the 4-year sample saw the highest-rated Biography films on average? The lowest?

* 3) Add in a column for Gross Revenue, and show the values as the % Difference From the previous year. By what percentage did Action movie revenue grow in 2014?

* 4) Create two new calculated fields named "Profit" (Gross Revenue - Budget), and "Profit Margin" (Profit / Gross Revenue). Update the view to show both new fields by Title. Which Title generated the strongest Profit Margin in the entire sample (across all years)?

* 5) Create a new calculated field for "Cast + Director Likes" (Cast FB Likes + Director FB Likes), and update the view to show Cast + Director Likes by Genre. If you wanted to show this field as an average across titles, rather than a sum, how could you accomplish this? 

|Show IMDb Scores as "Avgerage"|View Genre Average by Rank between 2011-2014|
|:-:|:-:|
|![Show IMDb Scores as "Avgerage"](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section4HomeworkPics/4.1HomeworkPics.png?h=350&w=630)|![View Genre Average by Rank between 2011-2014](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section4HomeworkPics/4.2HomeworkPics.png?h=350&w=630)|
|Show % Difference from Previous Year|Create "Profit" and "Profit Margin" Calculated Field|
|![Show % Difference from Previous Year](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section4HomeworkPics/4.3HomeworkPics.png?h=350&w=630)|![Create "Profit" and "Profit Margin" Calculated Field](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section4HomeworkPics/4.4HomeworkPics.png?h=350&w=630)|

### Create calculated field for "Cast + Director Likes" for combined Cast and Director FB Likes. 

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section4HomeworkPics/4.5HomeworkPics.png?w=1260">
</p>

## Section 5: Visualizing Data with Excel Pivot Charts

* 1) Create a view to show # of Titles by Country, excluding the USA, for the entire sample. Name the PivotTable "Titles by Country", then use a PivotChart to visualize this view as a Clustered Column Chart.

* 2) Hide the Field Buttons from the PivotChart, then apply a value filter to only show the top 10 countries by # of Titles (hint: you may need to enable multiple filters). Which country is #2?

* 3) Change the chart type to a Clustered Bar, and change the PivotTable sorting to ascending by # of Titles.

* 4) Pull in IMDb Score as a second series, and summarize values by Average. Change your PivotChart type to Combo, with # of Titles as a Clustered Column and IMDb Score as a Line with Markers, on the Secondary Axis. Which of the 10 countries generated the lowest average IMDb scores? (Bonus: Format the IMDb series in the chart to only show the markers, with no line)

* 5) Copy the existing pivot and create a second view below the combo chart to show Budget by Genre, with a Top 5 filter applied. Name the table "Budget by Genre", then visualize this view with a Pie chart, with hidden field buttons.

* 6) Insert a Slicer for Genre, enable multi-select, then connect it to both PivotTables. Create a simple dashboard by hiding the columns of your raw PivotTable views, disabling gridlines, and aligning/formatting the PivotCharts and Slicer as you see fit. Practice adjusting slicer selections to see how the dashboard updates!

|"Titles by Country" Clustered Column Chart|Top 10 Countries by Number of Titles|
|:-:|:-:|
|!["Titles by Country" Clustered Column Chart](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.1HomeworkPic.png?h=350&w=630)|![Top 10 Countries by Number of Titles](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.2HomeworkPic.png?h=350&w=630)|
|Clustered Bar Chart Ascending by # of Titles|# of Titles and IMDb Score Combo Chart|
|![Clustered Bar Chart Ascending by # of Titles](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.3HomeworkPic.png?h=350&w=630)|![# of Titles and IMDb Score Combo Chart](https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.4HomeworkPic.png?h=350&w=630)|

### Top 5 "Budget by Genre" Pie Chart. 

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.5HomeworkPic.png?w=1260">
</p>

### Enable Slicers multi-select and connect it to both Combo and Pie Charts. 

<p align="center">
    <img src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/Section5HomeworkPics/5.6HomeworkPic.png?w=1260">
</p>

## Section 6: Case Studies

<p align="left">
    <img width="150" alt="level1" src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/CaseStudies/VoterDemographics.jpg?raw=true"><a href="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/READMEVoterDemographics.md">Analysis of U.S. Voter Demographics<a>
</p>
    
---

<p align="left">
    <img width="150" alt="level1" src="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/Images/CaseStudies/SalaryData.jpg?raw=true"><a href="https://github.com/mathewqpmiller/Excel-PivotTables/blob/main/READMESalaryData.md">Analyzing San Francisco Salary Data<a>
</p>
