# Phase 1 Project
## Project Overview
### Identifying Low-Risk Aircraft for New Aviation Division Launch
For this project we will use data cleaning, imputation, analysis, and visualization to generate insights for a business stakeholder.

## Business Understanding
### 1. Project Purpose
This project is a strategic initiative to support the company's expansion into the aviation industry. The primary purpose is to conduct a comprehensive analysis of aircraft risk profiles to identify and recommend the most suitable low-risk aircraft for the new aviation division's initial fleet. This analysis will provide the necessary data and insights to mitigate the significant risks associated with aircraft acquisition and operation, thereby ensuring a stable and successful launch of the new business venture.

### 2. Problem Statement
The company is entering the aviation sector with a limited understanding of the inherent risks, which include, but are not limited to, accident rates, operational complexity, aircraft damage potential, and the human cost of incidents. A lack of data-driven insights in this area could lead to sub-optimal purchasing decisions, resulting in financial losses, operational inefficiencies, and significant safety liabilities. The problem is to transform raw aviation incident data into actionable intelligence that quantifies these risks and guides the selection of a low-risk, high-reliability aircraft portfolio.

### 3. Project Scope
This project will focus on the following key areas:
 * Data Analysis: Utilizing the provided "Aviation_Data.csv" dataset, the project will analyze historical aviation incidents to assess risk factors.

* Risk Factor Quantification: Key risk factors such as accident frequency, aircraft damage severity, and human injury rates will be quantified and benchmarked across different aircraft makes and models.

 * Aircraft Filtering: The analysis will be filtered to focus on aircraft types relevant to commercial and private enterprises, excluding categories like amateur-built or military aircraft.

 * Risk Profile Generation: A comprehensive risk profile will be developed for each significant aircraft make and model, considering accident severity, operational context (e.g., phase of flight, weather conditions), and human impact.

 * Recommendation & Actionable Insights: The project will culminate in a set of clear, actionable recommendations for the head of the new aviation division, identifying specific aircraft makes and models that represent the lowest overall risk for initial acquisition. The report will explain the rationale behind these recommendations, highlighting key risk mitigation strategies.

## Data Understanding
The data sources for this analysis will be pulled from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters. The data is contained in a csv file "Aviation_Data.csv"

## 1. Loading the Data with Pandas
In the cell below, we:

      * Import and alias pandas as pd
      * Import and alias numpy as np
      * Import and alias seaborn as sns
      * Import and alias matplotlib.pyplot as plt
      * Set Matplotlib visualizations to display inline in the notebook