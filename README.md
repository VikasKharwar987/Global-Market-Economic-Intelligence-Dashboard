# Global Market & Economic Intelligence Dashboard

## Overview

The Global Market & Economic Intelligence Dashboard is an interactive Tableau dashboard designed to analyze stock market activity and global inflation trends. The project combines financial market data with macroeconomic indicators to provide business-focused insights through KPI cards, ranking visualizations, and trend analysis.

The dashboard helps answer questions such as:

* Which stocks have the highest trading activity?
* How has market activity changed over time?
* Which countries currently face the highest inflation?
* How has inflation evolved across major economies over the last four decades?

---

## Dashboard Preview

### KPIs

* **Companies Analyzed:** 505
* **Top Traded Stock:** BAC (Bank of America)
* **Highest Inflation Country:** Zimbabwe
* **Countries Analyzed:** 181

### Visualizations

#### 1. Top Traded Stocks

Displays the top 10 stocks based on total trading volume over the available time period.

**Business Insight:**
Identifies the companies that dominate market activity and attract the highest investor participation.

---

#### 2. Inflation Comparison

Shows the top countries with the highest inflation rates in 2024.

**Business Insight:**
Highlights economies experiencing significant inflationary pressure and potential macroeconomic instability.

---

#### 3. Market Activity Trend

Compares monthly trading volume trends of major technology companies (AAPL, AMD, MSFT).

**Business Insight:**
Tracks changes in investor participation and market sentiment over time.

---

#### 4. Inflation Trend Analysis

Compares historical inflation rates for India, the United States, and the United Kingdom from 1981–2024.

**Business Insight:**
Provides a long-term view of inflation cycles and economic stability across major economies.

---

## Key Performance Indicators (KPIs)

### Companies Analyzed

Represents the total number of unique companies available in the stock market dataset.

**Value:** 505

---

### Top Traded Stock

Represents the stock with the highest cumulative trading volume.

**Value:** BAC (Bank of America)

---

### Highest Inflation Country

Represents the country with the highest inflation rate in the latest available year (2024).

**Value:** Zimbabwe

---

### Countries Analyzed

Represents the total number of countries included in the inflation dataset.

**Value:** 181

---

## Datasets Used

### 1. S&P 500 Historical Stock Data

Dataset:
https://www.kaggle.com/datasets/camnugent/sandp500

Key Fields:

* Date
* Open
* High
* Low
* Close
* Volume
* Company Name

Records:
600,000+ stock market records

---

### 2. Global Inflation Dataset

Dataset:
https://www.kaggle.com/datasets/sazidthe1/global-inflation-data

Key Fields:

* Country Name
* Year
* Inflation Rate

Countries:
181+

Years:
1980–2024

---

## Data Preparation

### Stock Dataset

* Imported CSV into Tableau
* Filtered major stocks for trend analysis
* Aggregated trading volume
* Created ranking visualizations

### Inflation Dataset

* Imported wide-format data
* Performed Tableau Pivot transformation
* Converted yearly columns into:

  * Year
  * Inflation Rate
* Built comparative trend analysis

---

## Tools & Technologies

* Tableau Public / Tableau Desktop
* Microsoft Excel
* CSV Datasets
* Data Visualization
* Business Intelligence (BI)
* Data Analytics

---

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Tableau Pivot Operations
* KPI Design
* Dashboard Development
* Trend Analysis
* Comparative Analytics
* Business Intelligence Reporting
* Data Storytelling

---

## Key Insights

* Bank of America (BAC) recorded the highest trading activity among analyzed stocks.
* Zimbabwe and Venezuela experienced exceptionally high inflation rates in 2024.
* Technology stocks showed fluctuating market activity between 2013 and 2018.
* India experienced higher historical inflation volatility compared to the United States and the United Kingdom.
* Inflation trends reveal significant economic differences across major economies.

---

## Future Enhancements

* Add interactive company filters.
* Integrate GDP and unemployment datasets.
* Include real-time market data APIs.
* Add geographic map visualizations.
* Deploy dashboard to Tableau Public.

---

## Author

Vikas Kharwar
