Wayfarer Global --- Customer Retention, Churn & Revenue Intelligence
> An interactive Business Intelligence dashboard for understanding
> customer retention, churn behavior, customer value, revenue exposure,
> and acquisition performance.
Overview
Wayfarer Global --- Customer Retention, Churn & Revenue Intelligence
is a portfolio-grade BI project built around a practical business
question:
Who is churning, what behaviors are associated with churn, how much
revenue is exposed, and where should the business focus its retention
efforts?
The dashboard analyzes a synthetic population of 50,000 customers,
271,778 bookings, and 26 months of history. It combines
executive KPIs, interactive filtering, retention analysis,
customer-value analysis, churn-driver analysis, marketing analytics, and
an action-oriented retention view.
Analytical flow: Customer Behavior → Churn → Customer Value →
Revenue Exposure → Business Action
Business Objectives
Monitor customer retention and churn at an executive level.
Identify differences in churn across segments, membership tiers,
channels, and regions.
Understand customer value using RFM-style segmentation and lifetime
revenue.
Identify high-value customers exposed to churn.
Examine behavioral signals associated with churn.
Evaluate acquisition channels using customer volume, revenue, churn,
ROI, and CAC.
Translate analytical findings into actionable retention priorities.
Dashboard Sections
1. Executive Overview
Tracks:
Total Customers
Active / Non-Churned Customers
Churn Rate
Retention Rate
Revenue
Profit
Average Order Value
Revenue at Risk
Also includes monthly revenue and churn trends, lifecycle distribution,
regional revenue, and revenue vs. profit.
2. Customer Retention
Analyzes:
Churn over time
Customer lifecycle
Churn by customer segment
Churn by membership tier
Churn by acquisition channel
Churn by region
Business question: Where is customer churn concentrated?
3. Customer Value
Includes:
RFM segment distribution
Lifetime revenue distribution
Customer Value × Churn Risk Matrix
High-value customers at risk
Revenue associated with at-risk high-value customers
The value-risk matrix combines revenue value with current churn-risk
status.
4. Churn Drivers
Includes:
Logistic regression feature importance
Held-out test-set confusion matrix
Churn by support-ticket count
Churn by booking lead time
Churn by return/cancellation rate
Churn by cart-abandonment count
The dashboard explicitly treats these relationships as associative
rather than causal.
5. Marketing & Acquisition
Compares acquisition channels across:
Customer volume
Revenue
Churn rate
Campaign ROI
Estimated CAC
Campaign ROI: (Revenue Generated − Spend) ÷ Spend
Estimated CAC: Spend ÷ Conversions
6. Action Center
Connects analytical findings to business action using:
Segment size
Revenue contribution
Churn rate
Revenue at risk
Recommended action
Interactive Filtering
Filters are available for:
`Region` · `Country` · `Segment` · `Tier` · `Channel` · `Device` ·
`Risk`
The customer count and analytical views update with active filters where
applicable. Customer-value terciles are calculated from the full
population so High / Medium / Low value retains a stable definition
across filters.
Key Portfolio Metrics
Metric                      Value
---
Customers                  50,000
Active / Non-Churned       26,730
Churn Rate                  34.2%
Retention Rate              65.8%
Revenue                  $480.8M
Profit                   $141.9M
Average Order Value       $1,965
Revenue at Risk          $170.0M
These are synthetic portfolio-demo figures, not real Wayfarer Global
business results.
Technical Stack
HTML5
CSS3
Vanilla JavaScript
Plotly.js
Responsive web layout
The dashboard performs filtering and aggregation client-side using a
columnar customer-data structure and does not require a backend.
Analytical Methodology
The synthetic dataset supports analysis across geography, customer
segment, membership tier, acquisition channel, device, risk, revenue,
profit, booking behavior, support activity, booking lead time,
return/cancellation behavior, cart abandonment, and RFM-related customer
value.
Churn
Churn is calculated from the project's `churn_flag`, with purchasing
history considered when calculating churn and retention rates.
Customer Value
Customer value is segmented using revenue-based terciles calculated from
the full customer population.
Churn Drivers
Behavioral variables are grouped into interpretable buckets and compared
with churn rates. Logistic regression feature importance and a held-out
test-set confusion matrix are also provided.
Important: These analyses identify associations and predictive
signals; they do not establish causation.
Project Architecture
``` text
Wayfarer Global
├── Executive Overview
│   ├── KPI cards
│   ├── Revenue trend
│   ├── Churn trend
│   ├── Customer segments
│   ├── Regional revenue
│   └── Revenue vs Profit
├── Customer Retention
│   ├── Churn over time
│   ├── Lifecycle
│   ├── Segment churn
│   ├── Tier churn
│   ├── Channel churn
│   └── Regional churn
├── Customer Value
│   ├── RFM segments
│   ├── Revenue distribution
│   └── Value × Risk Matrix
├── Churn Drivers
│   ├── Feature importance
│   ├── Confusion matrix
│   ├── Support tickets
│   ├── Lead time
│   ├── Return/cancellation rate
│   └── Cart abandonment
├── Marketing & Acquisition
│   ├── Customers by channel
│   ├── Revenue by channel
│   ├── Churn by channel
│   ├── Campaign ROI
│   └── Estimated CAC
└── Action Center
    └── Segment-level retention priorities
```
Why This Project Matters
This project demonstrates the BI workflow:
Business Problem → Data → Metrics → Segmentation → Diagnostic Analysis
→ Predictive Signals → Business Action
It showcases customer analytics, KPI design, interactive filtering,
churn analysis, customer-value analysis, revenue-risk analysis,
marketing analytics, and business-oriented data storytelling.
Limitations
This is a synthetic portfolio project.
Customer and transaction data are not real company data.
Findings should not be interpreted as real Wayfarer Global findings.
Churn-driver relationships are associative.
ROI and CAC use the supplied synthetic campaign data.
The project demonstrates BI methodology and analytical storytelling
rather than production forecasting.
Getting Started
The dashboard is a standalone HTML application.
Download or clone the project.
Open `wayfarer_dashboard.html` in a modern browser.
Explore the tabs and interactive filters.
No database or application server is required.
Portfolio Details
Project Type: Business Intelligence / Customer Analytics
Domain: Customer Retention & Revenue
Core Areas: Customer Analytics · Churn Analysis · Retention · RFM ·
Customer Value · Revenue Analytics · Marketing Analytics · Predictive
Analytics
Technologies: HTML · CSS · JavaScript · Plotly.js
Author
Remon Basu
MSc Biotechnology | Business Intelligence | Data Analytics
Created as a portfolio demonstration of interactive BI, customer
analytics, and business-focused data storytelling.
