# F-1 data analysis 1950 - 2024

## Table of Contents

- [Introduction](#Introduction)
- [Project Overview](#Project-Overview)
- [Visualizations](#Visualizations)
- [How to Use](#How-to-Use)

## Introduction

This project focuses on building an interactive and comprehensive Formula 1 data visualization dashboard using Microsoft Power BI. The dashboard analyzes key metrics related to races, drivers, and teams and visualize key race statistics from 1950 to 2024.

## Project Overview

### Purpose

The purpose of this project is to analyzes and visualizes Formula 1 race data to uncover trends in race wins, team performance, and key factors affecting results. The interactive dashboard lets users explore.

### Data Sources

The dataset used is publicly available on **Kaggle**:  
[Formula 1 World Championship (1950-2024)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

### Tools Used
- **Power BI**: Data visualization & dashboard creation
- **DAX & Power Query**: Data transformation and calculated measures

## Visualizations

![Drivers](https://github.com/gabrielesaus/portfolio/blob/main/Drivers.png)
![Teams](https://github.com/gabrielesaus/portfolio/blob/main/Teams.png)

### Key Insights
- **Race Winners & Team Performance:** Analyzing the most successful drivers and teams.
- **Track Insights:** You can explore the data by selecting the circuit that interests you the most.
- **Season Trends:** Understanding how drivers' and teams' results have changed over the years.
- **Reasons for not finishing:** Finding out the top reasons for not finishing races. 
- **Drivers Standings:** Interactive data preview for a choosen driver.

### Data Used:
- Results
- Circuits
- Constructors
- Drivers
- Qualifying
- Races
- Status

## How to Use

1. **Download Power BI Desktop**: [Download Link](https://powerbi.microsoft.com/en-us/desktop/)
2. **Download the Project File**: [Formula 1_Projec](https://github.com/gabrielesaus/portfolio/blob/main/Formula%201_Project.pbix)
3. **Open the Power BI File**:
    - Locate and open `Formula 1_Project.pbix` in Power BI Desktop.
4. **Resolve Dataset Errors (if any)**:
    - Go to `Transform Data` -> `Data Source Settings`.
    - Change the data source path to the correct dataset files in your local system.
    - Apply changes and refresh the dataset.

## Next Steps & Improvements

- There may be errors in the "duration" columns. Errors occur due to different locale settings. This location would be relevant in the future only when sharing reports not via PowerBI cloud, but when sending .pbix files AND only if different computers have different settings (this does not happen often in companies).
- Add Circuit-Specific Insights (Weather, Lap Records, Track Characteristics)
- Optimize for Mobile View in Power BI Service
- Enhancing dashboard with **predictive analytics** (e.g., Machine Learning)  

## Connect with Me

📧 Email: gabriele.saus@gmail.com  
💼 LinkedIn: [Gabriele Sauspreskyte](https://www.linkedin.com/in/gabriele-saus/)  

## References

1. [Microsoft Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi)
2. [Formula 1 World Championship (1950-2024) on Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
