# Business Funding Analysis & Dashboard - Nigeria

**Dataset from Data Science Nigeria**

---

##  Project Overview
This project analyzes Nigerian startup funding data to uncover **trends in sectors, funding sizes, and investor activity**. Using Python and Power BI, raw datasets were transformed into **clean, actionable insights** and an interactive dashboard for decision-making.  

**Key questions addressed:**  
- Which sectors attract the most funding?  
- How are investors distributed across funding sizes?  
- Which startups are top-funded and why?  

---

## Problem Statement
Startups in Nigeria face challenges securing funding due to **limited transparency** on sector performance and investor activity.  
Investors also need **insights into funding trends** to optimize decisions.  

This project solves these problems by providing:  
- **Cleaned and structured datasets**  
- **Feature-engineered metrics** like funding size and investor density  
- **Interactive dashboards** for actionable insights  

---

## Dataset
- **Source:** Data Science Nigeria  
- **Records:** 26 startups  
- **Columns after preprocessing:**  
  - Website Domain  
  - Categories  
  - Investors  
  - Investors Count  
  - Amount Normalized  
  - Funding Size (Small/Medium/Large)  
  - Primary Category  

**Notes:**  
- Missing values handled (Investors and Investors Count filled)  
- Categories parsed for meaningful analysis  
- Amounts normalized for comparison  

---

## Methodology

### 1. Data Cleaning
- Removed irrelevant columns (`Effective date`, `Source URLs`)  
- Handled missing values (`Unknown` for missing investors)  
- Normalized funding amounts  

### 2. Feature Engineering
- **Funding Size:** Small (<10M), Medium (<100M), Large (>100M)  
- **Investor Density:** Funding amount ÷ (number of investors + 1)  
- **Primary Category:** Main startup category  
- **Calculated Investor Count:** Derived from investor list  

### 3. Exploratory Data Analysis
- Funding by sector  
- Investor distribution by funding size  
- Top funded startups  

### 4. Dashboard Development
- **Tools:** Power BI  
- Interactive visuals included:  
  - Funding by sector  
  - Investor distribution  
  - Funding trends  
  - Top-funded startups  

**Example Visuals:**  

**Funding by Sector:**  
![Funding by Sector](https://github.com/thelawalmicheal/nigeria-startup-funding-analysis/blob/main/images/sector_funding.png))

**Investor Distribution by Funding Size:**  
![Investor Distribution](https://github.com/thelawalmicheal/nigeria-startup-funding-analysis/blob/main/images/investor_distribution.png)

**Top Funded Startups:**  
![Top Funded Startups](https://github.com/thelawalmicheal/nigeria-startup-funding-analysis/blob/main/images/top_funded_startups.png)


---

## 💡 Key Insights

### Total Funding
- **\$6 Billion** total funding captured  

### Top Sectors
| Sector / Category | Funding Amount |
|------------------ |----------------|
| Other             |  \$497,172,000 |
| Series I          |  \$685,000,000 |
| Private Equity    |  \$103,310,000 |

**Observation:** "Other," "Series I," and "Private Equity" dominate the funding landscape.

### Investor Distribution & Funding Size
| Funding Size | Investors| % of Total |
|--------------|----------|------------|
| Large        | 11       | 45.83%     |
| Medium       | 10       | 41.67%     |
| Small        | 3        | 12.5%      |

**Observation:** Most investors prefer **large and medium funding rounds**, showing risk concentration.

### Top Funded Startups
| Website Domain       | Primary Category  | Funding Amount |
|---------------------|-----------------|----------------|
| anthropic.com       | Other           | \$4,971,720,000 |
| databricks.com      | Series I        | \$685,000,000   |
| claritisoftware.com | Private Equity  | \$103,310,000   |
| carnnow.com         | Debt Financing  | \$40,000,000    |
| swtchenergy.com     | Series B        | \$27,200,000    |
| e-zinc.ca           | Series A2       | \$31,000,000    |
| gaiia.com           | Series A        | \$13,200,000    |
| biointelligence.com | Seed            | \$16,757,000    |

**Observation:** Funding is concentrated in a **few top startups**, highlighting key opportunities.

---

## Tools & Skills Used
Python (pandas, numpy), Data Cleaning, Feature Engineering, Exploratory Data Analysis, Power BI, Dashboard Design, Data Visualization, Business Insights, Reporting  

---

## Next Steps
- Predict which startups are likely to secure future funding  
- Expand dataset to include **historical trends** and geographic info  
- Investor profiling by sector preference and performance  
- Advanced Power BI visuals: KPIs, drill-through, and interactive slicers  
- Share insights with investors or startup incubators for actionable strategies  

---

## Audience
- Investors looking to target Nigerian startups  
- Startup founders seeking funding trends  
- Policy makers monitoring startup ecosystem growth  

---

## How to Explore
1. Clone this repository  
2. Open `Business_Funding_Analysis.ipynb` to explore preprocessing and analysis  
3. Open `PowerBI_Dashboard.pbix` for interactive visual insights  
4. PNG images in `/images/` folder can be used for quick visuals  
