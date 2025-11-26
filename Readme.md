Supply Chain Correlation Analysis

Email: 24f2000871@ds.study.iitm.ac.in

Overview

This repository contains the correlation analysis and heatmap visualization for a supply chain dataset consisting of 77 procurement transactions from an automotive manufacturer. The objective is to understand relationships between key supply chain metrics for supplier evaluation, inventory planning, and cost optimization.

Files Included

correlation.csv
Contains the 5×5 numerical correlation matrix generated using Excel’s Data Analysis ToolPak. Only correlation values are included.

heatmap.png
Screenshot of the Excel heatmap created using Conditional Formatting with the Red–White–Green color scale. Image size is between 400×400 and 512×512 pixels.

README.md
Documentation required for repository validation (this file).

Steps Followed

Imported the supply chain dataset into Excel.

Enabled the Analysis ToolPak
(File → Options → Add-ins → Analysis ToolPak).

Generated the correlation matrix using:
Data → Data Analysis → Correlation.
Selected all five metrics and enabled “Labels in first row.”

Copied the correlation matrix to a new sheet.

Applied Conditional Formatting (Color Scales → Red-White-Green) to create the heatmap.

Exported the correlation matrix as correlation.csv.

Took a square screenshot (400–512 px) of the heatmap and saved it as heatmap.png.