# Flight-Delay-Analysis
Exploratory and predictive analysis of NYC flight delays using the nycflights13 dataset.


---

## Getting Started

1. **Clone the repository**  
   git clone https://github.com/your-username/flight-club-delay-analysis.git
   cd flight-club-delay-analysis
2. **Install R packages**
Open R or RStudio and install the dependencies:
install.packages(c("nycflights13", "dplyr", "ggplot2", "lubridate", "knitr"))
3. **Render the report**
In RStudio, open analysis/FlightClub_Final_Report.Rmd and click “Knit” to produce HTML or PDF output.


## Analysis Overview
**Background & Purpose**
Investigate factors influencing departure delays at NYC airports to inform operations and reduce passenger inconvenience.

**Research Questions**
- Does time of year affect delays?
- Which airlines and airports experience the longest delays?
- How do weather conditions correlate with delays?
- Are holiday periods associated with higher delays?

**Data Source & Cleaning**
- Primary tables from nycflights13: flights, airlines, airports, planes, weather.
- Filtered out cancelled flights and handled missing values in delay fields.

**Exploratory Data Analysis (EDA)**
- Time Series of daily average departure delay
- Boxplots of delays by carrier and by airport
- Heatmaps and scatter plots relating weather metrics to delays

**Methodology & Results**
- Summary statistics and hypothesis tests on median delays across seasons
- Visual and statistical comparison of top‑delaying airlines/airports
- Quantified weather impacts (e.g., precipitation, wind) on delay magnitude

**Conclusions**
- Seasonal peaks in summer and winter holidays
- Specific carriers and hubs show systematically higher delays


**Dependencies**
 - R ≥ 4.0
 - CRAN packages:
   - nycflights13
   - dplyr
   - ggplot2
   - lubridate
   - knitr
