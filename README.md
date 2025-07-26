# Regional Tuberculosis Patterns and Patient Distribution Analysis

Table of Contents

- [Project Overview](#project-overview)
- [Key Insights](#key-insights)
- [Dataset Description](#dataset-description)
- [Installation and Setup](#installation-and-setup)
- [Features](#features)
- [Results & Visualizations](#results--visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Authors & Acknowledgments](#authors--acknowledgments)

## Project Overview

This project presents a comprehensive analysis of **Tuberculosis (TB) case patterns** and patient distributions in the Kishtwar district of Jammu & Kashmir, India. Leveraging real clinical data from the District Tuberculosis Unit (DTU), the analysis aims to uncover epidemiological trends, identify high-risk groups, recognize gaps in data recording, and recommend improvements to the diagnosis and treatment process of TB in the district.

## Key Insights

- **Public healthcare** was responsible for the diagnosis of 82.2% of TB patients, highlighting its pivotal role.
- The **18–45 age group** accounted for 54.9% of all cases, with a significant male predominance.
- Serious issues with **missing or inconsistent records** (such as treatment dates and diagnosis details) were evident.
- While patient origins spanned multiple regions, the concentration was highest in Kishtwar.
- The dataset contained 366 entries and 16 features, with notable biases due to size and missing variables (e.g., lifestyle factors like smoking or alcohol use).

## Dataset Description

| Column Name                 | Description                                                        |
|-----------------------------|--------------------------------------------------------------------|
| State                       | Patient's registration state (all entries are J&K)                 |
| TU                          | Treatment Unit managing the case                                   |
| Diagnosed from which Facility| Name/location of diagnosing facility                              |
| Public/Private              | Public or private diagnosing facility                              |
| Address                     | Patient’s residential address                                      |
| Diagnosis Date              | Date of TB diagnosis                                               |
| Age                         | Patient’s age                                                      |
| Gender                      | Gender of the patient                                              |
| Type                        | TB case type (e.g., New, Trunat (MTB), etc.)                       |
| Site                        | TB infection site (Pulmonary, Extrapulmonary, etc.)                |
| HIV Status                  | Patient’s HIV test result                                          |
| TB Drug Regimen             | Prescribed treatment regimen                                       |
| Tretment Start Date         | Start date for treatment                                           |
| Weight                      | Patient weight                                                     |
| Diabetic Status             | Diabetic status                                                    |
| EP Site                     | If extrapulmonary, location of infection                           |
| nan                         | Unnamed column                                                     |

## Installation and Setup

### Prerequisites

- Python 3.8 or above
- pip
- Jupyter Notebook

### Dependencies

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`

Install required Python packages:

```bash
pip install numpy pandas seaborn matplotlib
```

### Project Files

- `TB-Analysis-2.ipynb`: Main analysis notebook.
- `tb.xlsx`: Source dataset.


## Features

- **Comprehensive Data Cleaning:** Handles missing/duplicate values and harmonizes column categories.
- **Exploratory Data Analysis:** Age/gender groupings, distribution by healthcare facility, and diagnostic trends.
- **Outcomes & Treatment Status:** Summarizes cure rates, loss to follow-up, mortality, and misdiagnosis frequencies across clinical subgroups.
- **Visual Analytics:** Generates plots to reveal age, gender, region, and facility trends.
- **Gaps Identification:** Highlights data collection deficiencies and suggests quality improvements for records.

## Results & Visualizations

- **Key findings** are summarized at the top of the notebook for quick reference.
- **Charts** include:  
    - Age and gender distribution of TB patients  
    - Public vs. private facility diagnostic rates  
    - Treatment outcomes by age group  
    - Geographical trends within the district

> For detailed visual results, see the rendered outputs within `TB-Analysis-2.ipynb`.

## License

This project is licensed under the MIT License. You are free to use, share, and modify with attribution.

## Authors & Acknowledgments

- **Lead Analyst:** [Jozy Fatima]
- **Clinical Data Source:** District Tuberculosis Unit, Kishtwar
- **Collaborators:** All healthcare professionals and frontline staff involved in data collection

Special thanks to the healthcare workers of Jammu & Kashmir for their relentless service and data provision.

*This README was last updated on July 26, 2025. For continuous improvements or feedback, please contribute via pull request.*