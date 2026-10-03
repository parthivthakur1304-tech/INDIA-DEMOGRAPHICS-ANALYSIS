# India Demographics Analysis

An interactive **Power BI** dashboard and presentation analysing a 10,000-record demographic dataset across 10 Indian states, covering age, gender, education, employment, income, household size and access to internet, banking and health insurance.

> **Note:** The dataset is a **synthetic sample** created for practising data analysis and dashboard design. It is not official Census data, so the findings describe this sample only and should not be read as real-world statistics for India.

## Dashboard Preview

**Overview page**

![Dashboard Overview](01_overview.png)

**Charts page**

![Charts Page](02_charts.png)

## Project Files

| File | Description |
|------|-------------|
| `India_Demographics_Dashboard.pbix` | Power BI report (open with Power BI Desktop) |
| `india_demographics_data.csv` | Dataset: 10,000 rows, 14 columns |
| `India_Demographics_Professional_Presentation.pptx` | 9-slide presentation of the analysis and key insights |

## Dataset

- **Rows:** 10,000 (one row per person) | **Columns:** 14
- **States covered (10):** Punjab, Uttar Pradesh, Maharashtra, Delhi, Tamil Nadu, Haryana, Karnataka, Gujarat, West Bengal, Rajasthan
- **Data quality:** no missing values and no duplicate `Person_ID`

| Column | Description |
|--------|-------------|
| `Person_ID` | Unique ID for each person |
| `State` | State of residence |
| `Age` | Age in years (18 to 80) |
| `Gender` | Male / Female |
| `Education` | Primary, Secondary, Higher Secondary, Graduate, Postgraduate |
| `Occupation` | 10 categories (Private, Teacher, Government, Student, Farmer, etc.) |
| `Employment_Status` | Employed, Self-employed, Unemployed, Student |
| `Annual_Income_INR` / `Monthly_Income_INR` | Income in rupees |
| `Household_Size` | Number of household members (1 to 8) |
| `Urban_Rural` | Location type |
| `Internet_Access`, `Bank_Account`, `Health_Insurance` | Yes / No indicators |

## Tools Used

- **Power BI Desktop** for the data model, report pages and visuals
- **Microsoft PowerPoint** for the summary presentation
- **CSV** as the data source

## What the Dashboard Shows

The report has two pages:

- **Overview:** project introduction
- **Charts:** KPI cards (record count, income, household size, age) with interactive visuals:
  - Respondents by state (bar chart) with a state slicer
  - Gender split (donut chart)
  - Age group distribution (column chart)
  - Education level distribution (bar chart)

## Key Findings

- **Sample size:** 10,000 records, average age **49.1** years, median annual income **₹4.94 lakh**, average household size **4.49**.
- **Geography:** Punjab has the most records (**1,044**) and Rajasthan the fewest (**943**).
- **Income by state:** Gujarat has the highest average annual income (about **₹5.10 lakh**) and Punjab the lowest (about **₹4.91 lakh**), a gap of roughly 4%.
- **Gender:** 50.6% male (5,058) and 49.4% female (4,942).
- **Location:** 49.5% urban and 50.5% rural.
- **Education:** Higher Secondary is the largest group (2,042 records), followed closely by Secondary and Graduate.
- **Inclusion:** about half the sample has internet access (50.6%), a bank account (50.7%) and health insurance (50.3%).

## Limitations

- The data is synthetic and spread almost evenly across categories, so differences between states, genders and education levels are small.
- Results are not representative of India's actual population.
- A natural next step is to repeat the analysis with real data (for example Census of India or NSSO surveys), where meaningful gaps are expected.

## How to Open

1. Download `India_Demographics_Dashboard.pbix`.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. If prompted, point the data source to `india_demographics_data.csv`.

## Author

**Parthiv Thakur**
GitHub: [parthivthakur1304-tech](https://github.com/parthivthakur1304-tech)
