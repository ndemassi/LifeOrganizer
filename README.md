# Life Organizer Repo

## Title
*The Life Organizer* Repository
![dashboard](dashboard.png)

## Description
This serves as a repository for my Power BI Life Organizer dashboard and associated files.

## Motivation
*The Life Organizer* began as a simple budgeting tool and has evolved into a treasure trove of data and Power BI dashboards covering my finances and fitness habits.

## Features
This project contains interactive dashboards that attempt to answer various questions about my fitness and finances.
I log purchases (with location, categories, and event tags), income (including tax and retirement contribution details), and workouts (using metrics like mileage, weight, duration, etc.).

## Technologies Used
### Power BI Desktop
All of the reports, dashboards, and visualizations were made in **Power BI Desktop** on a **Windows** computer.
### Data Sources
All data is sourced from either **CSV** or **Excel** files, which are stored on SharePoint. I have plans in the future to incorporate weather data via **API**, but have not gotten that far yet.
### Other Languages
**DAX** and **Power Query** (**M Language**) are essential for this project.

## Project Structure
This project consists of a series of reports and dashboards that are published on Power BI server.

## How to Use
Step-by-step instructions on how to open and explore the Power BI report:
1) Clone the repository
2) Open the .pbix file in Power BI Desktop
3) Interact with the dashboard and customize as needed

## Walkthrough
Here is the main page of the dashboard:
![dashboard](dashboard.png)

The integration of this data requires a sophisticated semantic model, which you can see below. It includes various tables for income, expenses, exercise, and budgeting. It is all centered around a central date table.
![data_model](data_model.png)

Occasionally, different data groupings are required; this can be accomplished by using the grouping feature in Power BI:
![data_grouping](data_grouping.png)

These reports ultimately allow me to create a Sankey diagram of all my expenses. This has become a bit of a New Year's Eve tradition for me... every year on December 31st, I produce the following chart that shows where my money went all year!
![sankey](sankey.png)

Yes, this means I have to analyze every single paycheck so that I can extract tax withholding information. What a joy!
But the results are priceless. Increased organization, budget accountability, and tailored workouts. Below is a collage of a few other pages of the report:
![collage](collage.jpg)

## Contributing
*(Insert guidelines for others who want to contribute, report issues, or suggest improvements.)*

## Contact
You may contact me on LinkedIn at http://www.linkedin.com/in/ndemassi.

## Disclaimer
All data used in this project has purposely and randomly been altered to protect my privacy.
