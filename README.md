# GIGA / School Connectivity Analysis

Exploratory and comparative analysis of ICT access, usage, and affordability indicators relevant to school connectivity (GIGA framework)

## Project Overview

This project analyzes school connectivity across a set of selected countries using ITU data. It focuses on access, use, and affordability indicators that capture the availability and adoption of digital technologies in households and the broader population.

The analysis demonstrates:

-Data cleaning and preparation from raw ITU CSV files

-Country-level deep-dive for selected countries

-Comparative visualization of connectivity metrics

-Ability to assess digital readiness for schools

## Indicators Used

The analysis uses the following selected ITU indicators:

Pillar: Connectivity

Domain: Access

Households with Internet access at home (% of households)

Fixed-broadband subscriptions (per 100 people)

Active mobile-broadband subscriptions (count)

Population coverage by mobile network technology (% of population)

Domain: Use

Individuals using the Internet (% of individuals)

Pillar: Affordability

Domain: ICT Prices

Fixed-broadband Internet 5GB (% of GNI per capita)

Data-only mobile broadband basket 5GB (% of GNI per capita)

These indicators allow the project to evaluate infrastructure availability, household readiness, effective use, and affordability constraints relevant to school connectivity.

Selected Countries for Deep-Dive

-Ukraine

-South Africa

-Aruba

-Chile

-India

-Brazil

These countries were selected to provide a diverse mix of geographies, development levels, and digital adoption rates.

## Project Structure

The project is structured as a multi-notebook workflow in Python (Jupyter notebooks in PyCharm):

Notebook	Purpose
01_data_overview.ipynb	Explore raw ITU datasets and understand structure
02_load_data.ipynb	Load and inspect all selected indicators
03_data_preparation.ipynb	Clean, standardize, and filter indicators for selected countries
04_comparative_analysis.ipynb	Perform comparative analysis and generate visualizations
05_policy_insights.ipynb	Optional, for future extension to provide insights for decision-making
File Structure
giga-school-connectivity-analysis/
│
├─ data/
│  ├─ raw/                   # Raw CSV files from ITU DataHub
│  └─ processed/             # Cleaned CSV files after preprocessing
│
├─ notebooks/
│  ├─ 01_data_overview.ipynb
│  ├─ 02_load_data.ipynb
│  ├─ 03_data_preparation.ipynb
│  ├─ 04_comparative_analysis.ipynb
│  └─ 05_policy_insights.ipynb (optional)
│
└─ README.md

## Analysis Highlights

Access indicators: Track household connectivity and broadband availability trends

Use indicators: Measure individual adoption of Internet and mobile technologies

Affordability indicators: Compare cost of broadband against GNI per capita to highlight digital inclusion barriers

Visualizations: Line plots, bar charts, and comparative country charts to present trends over time

## How to Run

Clone the repository:

git clone https://github.com/yourusername/giga-school-connectivity-analysis.git


Open notebooks in PyCharm or Jupyter

Ensure all raw CSV files are in the data/raw folder

Run notebooks sequentially from 01 to 04

All preprocessing and cleaning scripts are in 03_data_preparation.ipynb.
