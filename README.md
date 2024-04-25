# Maven Sales Challenge | MavenTech-Sales Performance Report 📈

<img width="960" alt="MavenTech-Sales_Performance_Report" src="https://github.com/RishikaB-05/Maven-Sales-Challenge-MavenTech--Sales-Performance-Report-/assets/157221360/da07c537-cb1d-4854-b8f2-76ed397bbdf0">


## MavenTech – Sales Performance Report

## Overview

MavenTech, a company that specializes in selling computer hardware to large businesses, requires visibility of its data outside of its new CRM platform to track its sales opportunities.

## Objective:

Develop an interactive dashboard that empowers MavenTech's sales managers to effectively track and analyze their Sales performance across various levels (all regions, team regions, and individual sales agents) on a quarterly basis.

## Data:

The data contains B2B sales opportunities from a CRM database including information on:

- Accounts
- Products
- Sales teams
- Sales opportunities
The Above tables consist of 18 fields and 8800 records in CSV format.

The Deal Pipeline stages consist of Prospecting > Engaging > Won / Lost
## Approach to the Challenge
Step 1: Imported the data into Power BI Desktop and understand the data structure and what information the data contains.

Step 2: based on the pieces of information available in the CRM data, the KPIs the sales managers most likely need to focus on were defined.

Step 3: decided how to visualize the KPIs (e.g., KPIs cards, by team leaders, by sales agent, etc.), and draft a dashboard's user flow that maximizes user experience.

Step 4: data clean-up and transformation using Power Query, to make the data suitable create all the measures for the KPIs and the visualizations.

Step 5: creation of the data model and all the measures.
## Modeling Data

Minimal data cleaning was done, and currency columns were formatted. Columns were added to the 'sales_pipeline' table to track deal engagement to sale close duration, with separate columns for engage/close dates by month. Relationships between tables were established after minor formatting

## Interactive Filters:

The dashboard provides various filters to enable focused analysis:

- Region: allows filtering by a particular region.

- Quarter: allows selecting a specific quarter for performance analysis.

- Manager: facilitates selecting multiple managers to compare their teams' performance.

- Sales Agent: enables filtering by individual sales agents within a selected team.

## Performance Metrics:

The dashboard displays key metrics to assess team and individual sales agent performance:

- Opportunities: Represents the sum of won and lost deals within the selected criteria.

- Won Deals: Calculates the proportion of won deals out of the total deals.

- Lost Deals: Calculates the proportion of lost deals out of the total deals.

- Revenue: Represents the total close value from won deals based on the applied filters.

## Conclusion

This project showcases a unique step forward in visualizing and understanding MavenTech's company sales landscape. By incorporating interactive features such as charts and graphs, has empowered the regional managers to gain deeper insights into their sales teams.
