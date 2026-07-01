# Used Cars Market Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the `cars24data..csv` dataset to identify automotive market dynamics, pricing structures, and vehicle profile traits that heavily dictate resale valuations.

The analysis focuses on technical specifications, mileage, historical ownership, variant distribution, and pricing segments to help multi-brand auto platforms optimize standard buying configurations, inventory turns, and dynamic appraisal accuracy.


## Business Problem

Navigating the used car sector is complex due to a highly fragmented matrix of depreciating models, varied wear histories, and uneven regional demand. Estimating correct trade-in pricing margins remains a major challenge.

This project aims to answer questions such as:

* How skewed is the structural breakdown of categorical vehicle profiles?
* Do explicit car brands or structural variants command premium price ranges?
* Which attributes correlate most strongly with listing price adjustments?
* Does higher usage odometer mileage uniformly drag down pricing profiles across segments?
* Which core variables flag premium valuation categories for fast inventory turns?
* What baseline structural patterns segment wholesale commuter cars from executive packages?


## Dataset Information

The dataset contains comprehensive parameters extracted directly from used car platform inventories, detailed in `cars24data..csv`:

* Technical Specs (Engine volume, transmission type, variant naming matrices)
* Historical Wear Metrics (Odometer reading/mileage, previous title registrations)
* Nominal Identifiers (Year of manufacture, regional hub placement, model badges)
* Target Metric (Listing price / current transaction evaluation margin)


## Project Workflow

1. Data Architecture Review
2. Handling Nulls & Text Token Refinements
3. Univariate Feature Distributions
4. Bivariate Price Interactions
5. Categorical Correlation Matrice Evaluations
6. Practical Business Problem Decomposition
7. Dynamic Market Action Plan Suggestions


## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


## Key Analysis Performed

### Data Cleaning

* Outlier Capping and Isolation
* Extraneous Column Exclusions
* Null Verification & Structural Uniformity Checks
* Categorical Label Normalization

### Univariate Analysis

* Total Odometer Usage Spreads
* Categorical Transmission Breakdown Profiles
* Age and Year Profiles across Inventory Records
* Valuation Distribution Skewness Maps

### Bivariate Analysis

* Mileage Accumulation Velocity vs Pricing
* Brand Portfolio Segment Valuations
* Year of Origin Depreciation Impact Curves
* Major Technical Configurations vs Listing Price Segments

### Business Analysis

* Core Price Drivers Matrix
* Premium Inventory Identification Frameworks
* Depreciation Scaling Curves
* Regional Inventory Positioning Configurations


## Project Outcome

The analysis establishes exact pricing anchors across auto segments, showing the weight of historical mileage versus manufacturer tiers. These structural outputs enable operations management teams to optimize strategic car acquisition flows, mitigate procurement errors, and secure better retail margins.


## How to Run This Project

### The Quick Way (No Git Required)

1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and extract the project files.
3. Ensure the used vehicle dataset (`cars24data..csv`) is placed directly inside the project root directory.
4. Open your terminal or command prompt and run:

```bash
pip install pandas numpy matplotlib seaborn notebook
jupyter notebook
```

### Project Structure

Used-Cars-Market-EDA/
│
├── README.md
├── Used_Cars_Market_EDA.ipynb
├── cars24data..csv
└── Business_Recommendations.md

### Author

Priya Patel
Aspiring Data Analyst

📧 Email: patelpriya18217@gmail.com
💻 GitHub: https://github.com/priyapatel96140

If you found this project useful, feel free to give it a Star!
