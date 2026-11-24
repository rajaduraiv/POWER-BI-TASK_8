# POWER-BI-TASK_8

# Student Performance Dashboard – Power BI

## 1. Project Overview

This Power BI task presents a Student Performance Dashboard. It summarizes students' academic scores and overall results, and provides interactive filters to explore performance by student characteristics and study-related categories.

## 2. Tools Used

- Microsoft Power BI Desktop
- Power BI Report View
- Power BI visualizations, cards, and slicers

## 3. Tables and Fields Used

The report visuals use the following model tables and fields:

- `FactScores`
  - `Subject`
  - `Score`
  - Measures: `Avg Math Score`, `Avg Reading Score`, `Avg Writing Score`
- `DimStudent`
  - `StudentID`
  - `Overall Result`
  - `gender`
  - `race/ethnicity`
  - `lunch`
  - `test preparation course`
  - Measure: `Overall Pass %`

## 4. Operations Performed in Power BI

### 4.1 Created a Student Performance Dashboard
Added a report page titled **STUDENT PERFORMANCE DASHBOARD** to present student score and result information in one place.

### 4.2 Created KPI Cards
Added four card visuals to show:
- Average Math Score
- Average Reading Score
- Average Writing Score
- Overall Pass Percentage

These cards provide a quick summary of important performance measures.

### 4.3 Created a Subject-wise Score Column Chart
Added a clustered column chart using `Subject` as the category and the average of `Score` as the value. The chart compares average scores across subjects.

### 4.4 Created an Overall Result Donut Chart
Added a donut chart using `Overall Result` and the count of `StudentID`. This visual shows the distribution of students across overall result categories.

### 4.5 Added Interactive Slicers
Added slicers for:
- Gender
- Race/Ethnicity
- Lunch
- Test Preparation Course
- Subject

These slicers allow the report viewer to filter the dashboard and examine selected groups or subjects.

### 4.6 Configured Report Layout and Theme
Configured the report page as **Fit to Page** and used the Fluent 2 base theme with a dark custom theme resource.

### 4.7 Enabled Report Interactions and Export Settings
The report settings support filter/drill interactions with other visuals, enhanced tooltips, and export of summarized data.

## 5. Visuals Included

| Visual | Purpose |
|---|---|
| Card – Average Math Score | Displays the average mathematics score |
| Card – Average Reading Score | Displays the average reading score |
| Card – Average Writing Score | Displays the average writing score |
| Card – Overall Pass % | Displays the overall pass percentage |
| Clustered column chart | Compares average score by subject |
| Donut chart | Displays student count by overall result |
| Gender slicer | Filters by gender |
| Race/Ethnicity slicer | Filters by race/ethnicity |
| Lunch slicer | Filters by lunch category |
| Test Preparation Course slicer | Filters by preparation-course category |
| Subject slicer | Filters by subject |

## 6. Power BI Concepts Practiced

- Using separate fact and dimension tables in a report model
- Using measures in card visuals
- Displaying averages in a clustered column chart
- Displaying category counts in a donut chart
- Adding slicers for interactive filtering
- Configuring report page layout and theme
- Using visual interactions and summarized-data export settings

## 7.Screenshoot

"C:\Users\rajad\OneDrive\Pictures\Screenshots\Screenshot 2026-11-24 111053.png"

## 8. Conclusion

The Student Performance Dashboard provides a compact view of academic performance through KPI cards, a subject-wise average-score chart, and an overall-result donut chart. The slicers make it possible to explore the results by gender, race/ethnicity, lunch category, test preparation course, and subject.

## Note on Data Preparation

This README describes the tables, fields, measures, visuals, and report settings visible in the supplied PBIX report definition. Individual Power Query cleaning steps and model relationship details are not exposed by that report definition. To document those operations accurately, check **Transform data > Applied Steps** and **Model view** in Power BI Desktop before adding them here.
