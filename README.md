# Business-Insight-360

### Project Overview

This project analyzes revenue concentration, margin performance, customer discount structures, and inventory imbalances across multiple markets using transactional-level data.

The objective was to evaluate whether current growth is profit-accretive or margin-dilutive, and to identify structural drivers behind profitability volatility.

The analysis integrates Finance, Sales, Marketing, and Supply-Chain data to assess both commercial and operational performance.

### Business Problem

Despite revenue growth across key markets, margin performance showed signs of compression. High-revenue accounts were operating below target GM%, while inventory data indicated simultaneous stockouts and excess inventory across regions.

This raised three core questions:

- Is revenue growth aligned with profitability targets?
- Are discount structures driving structural margin dilution?
- Is forecast inaccuracy contributing to working capital inefficiencies?

### Data Overview

-Millions of transactional records
-Multi-market dataset
-Customer-level and product-level granularity
-Integrated SQL databases with supplementary Excel inputs
-Relational data model (fact and dimension structure)
**Core data domains analyzed:**
-Key Metrics : Net Sales, Gross Margin, Gross Margin %, Forecast Accuracy %, Net Error, & Absolute Error
-P&L Statement
-Revenue Trend
-Product, Customer & Market Perfomance 
-Unit Economics
-Customer and market hierarchies

### Methodology

The analytical model was structured using a relational star-schema approach linking fact tables (Sales, Inventory, Forecast) to dimension tables (Customer, Product, Market, Date, Pricing).

Key analytical techniques included:

-GM% vs Target variance analysis
-Revenue concentration and margin sensitivity evaluation
-Discount impact assessment (pre- and post-invoice)
-Forecast accuracy and absolute error measurement
-Stockout vs excess inventory imbalance identification

### Key Insights

- Revenue concentration in major markets correlates with margin compression, particularly among high-volume accounts.
- Large customers operate below GM% targets due to elevated discount structures.
- Stockouts and excess inventory coexist across markets, indicating systemic forecast misalignment rather than isolated regional issues.
- Growth appears volume-driven but margin-sensitive, increasing exposure to profitability volatility.
- Margin dispersion within markets suggests uneven customer portfolio performance.

### Strategic Implications

The interaction between pricing concessions and inventory misallocation creates a reinforcing profitability pressure loop. Without structural intervention, continued scale expansion risks becoming margin-dilutive rather than margin-accretive.

The issue is not growth itself — but the quality and allocation of growth.

### Dashboard

An interactive Power BI dashboard was developed to support:

Multi-dimensional performance analysis (Finance x Market × Customer × Product × Time)
- Finance View
- Sales View
- Marketing View
- Supply-Chain View
- Executive View

### Dashboard preview images are included in this repository.
Home Page:
<img width="1761" height="993" alt="Screenshot 2026-02-28 173241" src="https://github.com/user-attachments/assets/26ff24e8-5763-420b-a07f-e55aa4ae70c7" />
Finance View:
<img width="1763" height="997" alt="Screenshot 2026-02-28 173255" src="https://github.com/user-attachments/assets/4052423a-82b1-4182-9f4b-4d2e9b47862c" />
Sales View:
<img width="1764" height="992" alt="Screenshot 2026-02-28 173308" src="https://github.com/user-attachments/assets/df8c9062-6e15-44b5-9e8b-7746e111585b" />
Marketing View:
<img width="1760" height="993" alt="Screenshot 2026-02-28 173319" src="https://github.com/user-attachments/assets/887f16ca-4b4f-4089-bb8d-2a660dfb1798" />
Supply-Chain View:
<img width="1763" height="996" alt="Screenshot 2026-02-28 173332" src="https://github.com/user-attachments/assets/2ff4c198-e4d5-4b88-9e40-1efdf5ed8f1d" />
Executive View:
<img width="1759" height="991" alt="Screenshot 2026-02-28 173341" src="https://github.com/user-attachments/assets/b2f0957d-6cf1-4322-ab75-bf13b59f26c0" />

### Tools & Technologies

- SQL (data extraction and transformation)
- Power BI (data modeling and visualization)
- Excel (supplementary operational inputs)
