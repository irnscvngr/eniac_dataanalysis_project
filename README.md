# Eniac Data Analysis Project

## Project overview

This project was part of a Data Science Bootcamp at WBS Coding School.<br>
Base of the project was a collection of data (e.g. orderlines, products, brands) from a real but anonymized company. To make things simpler, it shall be called *Eniac* from now on.<br>
The project was structured in the following way:
1. **Data preparation and cleaning**<br>
   The provided data had a lot of inconsistencies, sometimes missing information etc. So the first part of the project was to provide a consistent and reliable dataset.<br>
   <br>
2. **Data analysis**<br>
   The now reliable dataset was analysed regarding customerbehaviour. Goal was to find out if and how strongly discounts on product prices boost revenue and/or sales.<br>
   <br>
   - **Cluster products**<br>
     Products were clustered using a product-type attribute already present in the data.<br>
     Further clustering was done using Google Gemini AI controlled via Python code.<br>
     <br>
   - **Discounts, revenues and sales over time**<br>
     Product-clusters were analyzed over time to get an overview and find out general patterns.<br>
   - **Find correlations between discounts and revenue/sales**<br>
     Linear-regression models between discounts and revenue/sales were setup per product-type.<br>
     <br>
4. **Present results**<br>
   Results of the data analysis were ordered by importance and impact on the company. Finally results were presented using Google Slides.<br>
   <br>
   <br>

## Project presentation

The following shows some images from the final presentation.<br>
See the full presentation over on <a href="https://docs.google.com/presentation/d/1MgT4-HUO19ZwohObSgC9Dpi1rOVWpC7COi-TduYRChg/edit?usp=sharing">[Google Slides]</a>.

<img src="images/Slide_02.png" width=400> <img src="images/Slide_03.png" width=400>
<br>
<br>
<img src="images/Slide_05.png" width=400> <img src="images/Slide_06.png" width=400>
<br>
<br>
<img src="images/Slide_09.png" width=400> <img src="images/Slide_10.png" width=400>
<br>
<br>

## Data analysis

<img src="images/discounts_heatmap.png" width=1000>
<br>
<br>
<img src="images/discounts_barchart.png" width=1000>
<br>
<br>
<img src="images/orders_prices_over_time.png" width=1000>
<br>
<br>
