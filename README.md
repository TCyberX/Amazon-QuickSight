

# Visualize data with QuickSight

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-analytics-quicksight)

**Author:** Albert  
**Email:** tapcyberx@gmail.com

---

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Introducing Today's Project!

### Tools and concepts

Amazon QuickSight is a cloud-based business intelligence (BI) service that enables users to visualize, analyze, and share data insights quickly. 

### Project reflection

I used QuickSight to analyze Netflix data: connected S3 files, created visualizations (like genre distribution charts), applied filters, and exported dashboards—turning raw data into insights fast.

One unexpected challenge was creating the genre distribution graph—it was my first time visualizing such complex category data, which required careful filtering to make the insights clear.

---

## Upload project files into S3

S3 stores two essential files for this project: manifest.json and netflix_titles.csv, ensuring efficient data management and accessibility for seamless processing and analysis.

I edited the manifest.json file by updating its configurations to ensure proper metadata and resource linking. It’s important to edit this file because it defines essential settings for data processing in S3 URI of our database.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_3c3cd85a)

---

## Create QuickSight account

Creating a QuickSight account cost you money is probably if you don't delete after you done with this project.

Creating an account took me aroud 5 minutes more or less.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_f4ab4214)

---

## Download the Dataset

I connected the S3 bucket to QuickSight by navigating to Datasets, selecting Create a Dataset, choosing S3 as the data source, providing a data source name, and uploading the S3 URI of the manifest file.

The manifest.json file was crucial in this step because it defines the dataset structure for QuickSight, ensuring it correctly interprets and visualizes the data. Without it, QuickSight might misread or misrepresent the dataset.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_6f874996)

---

## My first visualization

I created visualizations in QuickSight by selecting a dataset, opening a new analysis, choosing a visualization type, adding relevant fields, customizing the chart, and then saving the insights for sharing.

The visualization displays a breakdown of Netflix-featured TV shows and movies by release year, highlighting trends in content production over time. It helps identify patterns in Netflix’s content library expansion.


I created this graph by dragging and dropping the release year field to the X-axis and the count of titles to the Y-axis. I then customized the headings and labels for clarity, making it easy to analyze trends over time.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_aff3aad7)

---

## Using filters

Filters are useful for refining data and enhancing graph clarity. When creating a donut chart to count records by listed_in, filters help focus on specific categories, making insights more meaningful.

This donut chart visualizes the count of Netflix titles by category (listed_in), showing the distribution of genres like 'Action & Adventure,' 'Thrillers,' and 'TV Comedies.' I added a filter to focus on specific categories, making it easier.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_c32248c5)

---

## Setting up a dashboard

Before publishing the dashboard, I ensured clarity and consistency by renaming each graph to reflect its insights, adjusting colors for better readability, and adding descriptive titles to make the data instantly understandable for viewers.

I exported the dashboard as a PDF by selecting the 'Export' option, choosing the PDF format, and downloading the file once processing was complete.

![Image](http://learn.nextwork.org/delighted_indigo_timid_orc/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Refreshing source data

---

---
