# Hotel Revenue Management Case Study

## End-to-End Analysis of Segmentation, Cancellations, Demand Forecasting and Pricing Strategy

This repository presents an end-to-end hotel Revenue Management case study based on hotel booking data.

The project is designed to simulate how a Revenue Management analyst would approach a hotel performance analysis: transforming booking data into business metrics, identifying revenue opportunities and translating findings into practical commercial recommendations.

---

## Project Snapshot

| Area | Description |
|---|---|
| Industry | Hospitality / Hotel Revenue Management |
| Main Focus | Segmentation, cancellations, demand forecasting and pricing strategy |
| Business Goal | Improve revenue performance through better analytical decision-making |
| Tools | Python, Pandas, Jupyter Notebook, Excel |
| Output | Business insights, analytical modules and RM recommendations |

---

## Core Business Question

**How can hotel booking data be used to support better Revenue Management decisions around segmentation, cancellations, demand forecasting and pricing strategy?**

---

## Main Value of the Project

This project demonstrates the ability to connect technical data analysis with practical Revenue Management thinking.

The main value is not only in calculating metrics, but in using those metrics to support decisions related to:

- Segment prioritization
- Channel and cancellation risk
- Demand forecasting
- Price sensitivity
- Inventory protection
- Revenue strategy

---

## Business Context

Hotels need to make revenue decisions under uncertainty. Demand changes by season, customer segment, booking channel and lead time. At the same time, cancellations, price sensitivity and channel mix can strongly affect final revenue performance.

This case study simulates how a Revenue Management analyst would evaluate hotel booking data to answer questions such as:

- Which customer segments generate the strongest revenue value?
- Which channels or segments create more cancellation risk?
- How does demand behave by month and segment?
- How does demand react to ADR changes?
- What pricing and inventory actions could improve revenue performance?

---

## Main Objective

The main objective of this project is to analyze hotel booking data from a Revenue Management perspective and identify opportunities to improve revenue performance through better segmentation, cancellation management, demand forecasting and pricing strategy.

---
## How to Read This Project

This project is designed to be read at different levels depending on the reader's role and available time.

### For HR Recruiters

Start with the Executive Summary to understand the business objective, tools used and main Revenue Management recommendations.

Recommended file:

- [Executive Summary](executive_summary/executive_summary.md)

### For Revenue Managers or Hiring Managers

Start with the main README and then review the final strategy recommendations.

Recommended files:

- [Main Project README](README.md)
- [Revenue Management Strategy Recommendations](05_revenue_strategy_recommendations/revenue_strategy_recommendations.md)

### For Technical Reviewers

Review the notebooks inside each analytical module.

Recommended modules:

- [Segment Performance Analysis Notebook](01_segment_performance/segment_performance_analysis.ipynb)
- [Cancellation Risk Analysis Notebook](02_cancellation_analysis/cancellation_risk_analysis.ipynb)
- [Demand Forecasting Notebook](03_demand_forecasting/demand_forecasting_by_segment.ipynb)
- [Price Elasticity Analysis Notebook](04_price_elasticity/price_elasticity_analysis.ipynb)

### Suggested Reading Order

1. [Executive Summary](executive_summary/executive_summary.md)  
2. [Segment Performance Analysis](01_segment_performance/README.md)  
3. [Cancellation Risk Analysis](02_cancellation_analysis/README.md)  
4. [Demand Forecasting](03_demand_forecasting/README.md)  
5. [Price Elasticity Analysis](04_price_elasticity/README.md)  
6. [Revenue Management Strategy Recommendations](05_revenue_strategy_recommendations/revenue_strategy_recommendations.md)  

---
## Project Modules

### 01. Segment Performance Analysis

This module analyzes customer segments to understand their contribution to room nights, revenue and ADR.

The analysis focuses on identifying which segments generate strong revenue value and which segments may contribute volume without proportional revenue performance.

**Main Revenue Management focus:**

- Segment mix
- Room nights contribution
- Revenue contribution
- ADR by segment
- Segment value comparison

**Folder:** [01_segment_performance](01_segment_performance/)

---

### 02. Cancellation Risk Analysis

This module analyzes cancellation behavior and its impact on revenue performance.

The objective is to understand how cancellations affect net revenue, forecast accuracy, channel reliability and potential overbooking decisions.

**Main Revenue Management focus:**

- Cancellation rate
- Revenue lost due to cancellations
- Lead time behavior
- Channel risk
- Net revenue impact

**Folder:** [02_cancellation_analysis](02_cancellation_analysis/)

---

### 03. Demand Forecasting by Segment and Month

This module focuses on forecasting demand by month and customer segment.

The objective is to support pricing and inventory decisions by understanding expected demand patterns across time and segments.

**Main Revenue Management focus:**

- Monthly demand
- Segment demand behavior
- Seasonality
- Future demand estimation
- Forecast-based pricing support

**Folder:** [03_demand_forecasting](03_demand_forecasting/)

---

### 04. Price Elasticity and Demand Behavior

This module analyzes the relationship between ADR and demand.

The goal is to evaluate whether demand reacts strongly or weakly to price changes across different periods and segments.

**Main Revenue Management focus:**

- ADR behavior
- Demand response
- Price sensitivity
- Seasonality effects
- Pricing power by segment

**Folder:** [04_price_elasticity](04_price_elasticity/)

---

### 05. Revenue Management Strategy Recommendations

This final module connects the analytical findings with practical Revenue Management decisions.

The objective is to translate the analysis into recommendations related to pricing, segmentation, inventory control, cancellation management and channel mix.

**Main Revenue Management focus:**

- Pricing strategy
- Channel mix optimization
- Segment prioritization
- Cancellation risk management
- Inventory protection

**Folder:** [05_revenue_strategy_recommendations](05_revenue_strategy_recommendations/)

---
## Key Findings

The analysis highlights several Revenue Management insights that can support better hotel decision-making.

### 1. Segment performance should not be evaluated only by volume

Some segments may generate strong room night volume, but this does not always mean they generate proportional revenue value.

Revenue Management decisions should compare room nights, revenue and ADR together to understand the real value of each segment.

---

### 2. Direct demand can represent stronger revenue value

Direct bookings may provide stronger value when compared with volume-heavy channels, especially if they show better ADR contribution or lower dependency costs.

This supports the importance of monitoring direct demand and not relying only on high-volume intermediary channels.

---

### 3. Cancellations affect both revenue and forecast accuracy

Cancellation behavior can create a false sense of demand if only gross bookings are analyzed.

For Revenue Management, cancellation patterns should be considered when evaluating net demand, overbooking assumptions and inventory availability.

---

### 4. Demand forecasting should be segmented

A total hotel forecast can hide important differences between customer segments.

Forecasting demand by segment and month allows the hotel to better understand expected demand composition and adapt pricing or inventory decisions accordingly.

---

### 5. Price elasticity must be interpreted carefully

The relationship between ADR and demand is influenced by seasonality, segment mix and demand pressure.

A weak or positive elasticity result may indicate that price is reacting to market demand, rather than demand being directly caused by price changes.

---

### 6. Inventory protection is key during high-demand periods

When demand is strong, accepting too much low-yield or high-risk business too early can limit the ability to capture higher-value demand later.

Revenue Management should consider segment value, cancellation risk and expected demand before allocating inventory.

---
## Key Revenue Management Metrics Used

This project uses several core hotel Revenue Management metrics and analytical variables:

- Room nights
- Revenue
- ADR
- Cancellation rate
- Net revenue
- Lead time
- Customer segment
- Market segment
- Booking channel
- Monthly demand
- Seasonality
- Price elasticity

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Excel
- Forecasting models
- Revenue Management metrics
- Business analysis

---

## What This Project Demonstrates

This project demonstrates my ability to:

- Transform raw hotel booking data into business-ready metrics.
- Analyze customer segments from a Revenue Management perspective.
- Identify cancellation patterns and revenue risk.
- Forecast demand by month and segment.
- Evaluate the relationship between ADR and demand.
- Translate data analysis into practical Revenue Management recommendations.
- Communicate technical findings in a business-oriented way.

---

## Repository Structure

```text
Hotel-Revenue-Management-Case-Study/
│
├── 01_segment_performance/
│   ├── README.md
│   ├── segment_performance_analysis.ipynb
│   └── segment_performance_dataset.xlsx
│
├── 02_cancellation_analysis/
│   ├── README.md
│   ├── cancellation_risk_analysis.ipynb
│   └── cancellation_analysis_dataset.xlsx
│
├── 03_demand_forecasting/
│   ├── README.md
│   └── demand_forecasting_by_segment.ipynb
│
├── 04_price_elasticity/
│   ├── README.md
│   └── price_elasticity_analysis.ipynb
│
├── 05_revenue_strategy_recommendations/
│   └── README.md
│
├── executive_summary/
│   └── README.md
│
├── assets/
│   └── README.md
│
└── README.md

