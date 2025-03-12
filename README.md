### Overview

This project aims to analyze the relationship between the availability of healthcare facilities and the type of health insurance coverage in Chicago. Specifically, it investigates whether the number of clinics and hospitals influences the prevalence of private insurance, such as employment-based coverage, compared to public insurance programs like Medicaid, the largest public health insurance provider in the United States.

To conduct this analysis, multiple datasets from the Chicago Health Atlas, the Chicago Data Portal, and the American Community Survey (ACS) were integrated. In addition to healthcare facility data, various socioeconomic factors were incorporated, including public assistance income and perceived neighborhood safety rates, to assess their potential impact on insurance coverage.

The study is geographically focused on Chicago and utilizes community area-level data to identify spatial patterns in health insurance coverage and healthcare facility distribution. To support the analysis, several maps were created, visualizing the distribution of insurance types and healthcare facilities across different community areas. These visualizations provide insights into potential disparities in access to healthcare services and insurance coverage throughout the city.

### Datasets Used:
- `CommAreas_20250304.geojson` (A geojson file for community area boundaries in Chicago)
- `Public_Health_Services-_Chicago_Primary_Care_Community_Health_Centers_20250304.csv` (Clinics in Chicago)
- `hospitals.csv` (Hospitals in Chicago)
- `Chicago Health Atlas Data Download - Community areas.csv` (Socioeconomic factors and some insurance data in Chicago on the level of community areas)
- `ACSST5Y{year}.csv` files (with year being 2015-2023, so there are 9 files containing the percent of different public insurance coverages in Chicago)
- `Employment_Insurance_Chicago_Health_Atlas.csv` (Percent of employment-based health insurance coverage in Chicago from 2015-2023)
- `Public_assistance_income_Chicago_Health_Atlas.csv` (Percent of households reporting public assistance income from 2015-2023)

The source of each dataset and how to acquire them are stated later in the code below
