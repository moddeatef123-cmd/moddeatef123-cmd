# COVID-19 Market Impact Analysis | Power BI

An interactive Power BI project exploring how 20 major companies across different sectors performed before, during, and after the COVID-19 market shock (2018–2022). The dashboard focuses on company performance, financial risk, recovery patterns, and Technology vs. Non-Technology comparisons.

> **Project type:** Team graduation project  
> **Tools:** Microsoft Power BI, DAX, Power Query, CSV datasets  
> **Period analyzed:** 2018–2022  
> **Companies:** 20 companies across multiple sectors

## Project Overview

The COVID-19 era affected companies differently. This project uses an interactive dashboard to compare stock-market performance and risk measures, examine recovery patterns, and help users explore results by time period, sector, and company.

### Business Questions

- Which companies delivered the strongest and weakest total returns during 2018–2022?
- How did company risk and volatility differ?
- Which companies experienced the largest drawdowns?
- How did Technology companies compare with Non-Technology companies?
- Which companies showed stronger recovery patterns after the COVID-19 shock?

## Dashboard Preview

### 1. Portfolio Overview
![Portfolio Overview](images/01-dashboard-overview.png)

### 2. Company Ranking & Risk Analysis
![Company Ranking and Risk Analysis](images/02-ranking-risk-analysis.png)

### 3. COVID-19 Recovery Analysis
![COVID-19 Recovery Analysis](images/03-covid-recovery-analysis.png)

### 4. Technology vs. Non-Technology
![Technology vs. Non-Technology](images/04-tech-vs-non-tech.png)

### 5. Company Performance Analysis
![Company Performance Analysis](images/05-company-performance-analysis.png)

### 6. Insights and Recommendations
![Insights and Recommendations](images/06-insights-and-recommendations.png)

## Key Areas of Analysis

- **Performance:** total return, average returns, and company rankings.
- **Risk:** volatility, beta, risk-adjusted return, and maximum drawdown.
- **Recovery:** company-level recovery patterns during the COVID-19 period.
- **Sector comparison:** Technology vs. Non-Technology performance and trends.
- **Interactive exploration:** slicers, filters, drill-down, and company-level views.

The project presentation reports Tesla as the strongest total-return performer in the selected period and American Airlines as the weakest. Results should be interpreted within the project's selected companies, metrics, and 2018–2022 period; they are not investment advice.

## Data Model & Workflow

The project presentation describes a star-schema model with company and calendar dimensions connected to stock-return and related analytical tables.

**Workflow:**

1. Import source CSV files.
2. Clean and transform data in Power Query.
3. Build the data model and relationships.
4. Create DAX measures and KPIs.
5. Develop interactive visuals and validate calculations, filters, and dashboard interactions.

## Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query (M)
- CSV data sources
- Data modeling and relationships
- Interactive visualizations, slicers, drill-down, and drill-through

## My Contribution

My documented role in this team project was **Data Cleaning & Transformation**. The project was completed collaboratively, with other team members responsible for areas including data collection, data modeling, visualization, dashboard design, DAX/KPI development, and documentation.

## Project Files

- `Final-Project-DEPI.pbix` — Power BI report file.
- `Project-Presentation.pptx` — project presentation.
- `images/` — six dashboard and project-page screenshots.

To explore the report, download the `.pbix` file and open it in Microsoft Power BI Desktop. Availability of the underlying source data may affect whether every element refreshes correctly.

## Disclaimer

This project is for educational and portfolio purposes only. It is a historical analysis of selected companies and is not financial or investment advice.
