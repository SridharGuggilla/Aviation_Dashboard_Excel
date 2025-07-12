# Aviation_Dashboard_Excel
This repository contains an interactive Excel-based dashboard that visualizes civil aviation accident data from the National Transportation Safety Board (NTSB). The dashboard provides insights into accident trends over time, by location, by phase of flight, by purpose of flight, damage severity, and key performance indicators (KPIs).


# Features

Location-Wise Accident Analysis: Map and table showing the number of accidents by country or airport.

Accidents by Year: Line chart tracking accidents over years to highlight historical trends.

Accidents by Purpose of Flight: Bar chart categorizing accidents (e.g., private, commercial, instructional).

Phase of Flight Breakdown: Pie or column chart illustrating the flight phases with the highest occurrences.

Aircraft Damage Summary: Distribution of damage levels (e.g., substantial, destroyed).

Key Performance Indicators (KPIs): Metrics for total accidents, fatalities, serious injuries, and average yearly change.

Interactive Filter Controls: Slicers/dropdowns to filter the data by date range, country, aircraft category, or injury severity.

Data Source & ETL: Raw data, transformation steps, and dashboard logic included within the workbook.


# Prerequisites

Microsoft Excel 2016 or later (Windows or Mac) with Power Query and Power Pivot enabled.

Windows: For map visualizations, ensure the Bing Maps add-in is installed or use Office 365's built-in map feature.

Mac: Map features may be limited; charts will adjust accordingly.

#  Data Source

The primary data source is the NTSB Aviation Accident Database. Key fields included:

Event Date and Publication Date

Location: Country, latitude, longitude, airport code/name

Injury Severity and counts

Aircraft Make/Model, Damage Category

Flight Phase, Purpose, Weather Conditions

# 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please:

Fork the repository.

Create a new branch (git checkout -b feature/my-feature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/my-feature).

Open a Pull Request.
