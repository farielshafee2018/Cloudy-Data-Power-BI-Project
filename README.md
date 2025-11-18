# Cloudy-Data-Power-BI-Project
This repository contains a dash board created in the Cloudy Data bootcamp.
The project contains multiple steps.


1. Data was collected from a UN country indicator file (CSV format) and also from an API JSON file (https://api.worldbank.org/v2/country/all?format=JSON&per_page=500)
2. The JSON file was converted to a table.  Both the tables were cleaned (headers, data type, null values, unpivoting similar columns).
3. The indicator file was further manipulated to extract population, land area and GDP separately from a single column.
4. The two files were joined using relationship.
5. Multiple measures were created using DAX commands.  The variable, GDP growth was extracted using DAX and a line chart showing yearly GDP.
6. Cards, tables and maps were added.  Drill through, sparklines and page navigators were added.
