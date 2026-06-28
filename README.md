![preview](https://raw.githubusercontent.com/govinda25072003-ai/pbi-amazon-sales-dash/main/preview.svg)

# GeoSales Intelligence Engine

In the intricate ecosystem of e-commerce, raw transaction records often conceal the most valuable strategic narratives. The **GeoSales Intelligence Engine** reimagines how enterprises can decode regional performance, seasonal demand fluctuations, and product category resonance through a modern analytics interface. Built upon the foundation of structured sales data and geographic mapping, this repository provides a dynamic framework for transforming dispersed order logs into a unified, visual command center.

This project was inspired by the need to evolve beyond simple data aggregation. Instead of merely viewing sales figures, the GeoSales Intelligence Engine enables stakeholders to interact with data geographically, temporally, and categorically, revealing hidden correlation patterns that typical dashboards miss. Whether you are a supply chain analyst forecasting inventory or a marketing strategist evaluating campaign lift across different states, this engine offers a scalable, customizable platform for deep sales exploration.

## 📈 Overview: From Data Streams to Strategic Vision

Modern commerce generates data at an unprecedented velocity, yet many organizations struggle to synthesize this information into actionable insights. The GeoSales Intelligence Engine addresses this challenge by providing a modular, Power BI-centric architecture that ingests Amazon-style sales reports and outputs an interactive, multi-dimensional dashboard.

The system is designed around three core principles:

*   **Geospatial Context:** Every sales record is enriched with location intelligence, allowing for heat maps, regional trend lines, and territory-based performance breakdowns.
*   **Time-Aware Analytics:** The engine automatically segments data into fiscal periods, holiday windows, and rolling averages, enabling precise seasonal strategy adjustments.
*   **Category Fluidity:** Products are analyzed not just as SKUs, but as members of hierarchical categories, revealing cross-category affinities and substitution effects.

## [![Download](https://raw.githubusercontent.com/govinda25072003-ai/pbi-amazon-sales-dash/main/button.svg)](https://govinda25072003-ai.github.io/pbi-amazon-sales-dash/)

## 🗺️ Key Features & Architecture

### 1. 📊 Interactive Geographic Sales Map
Visualize revenue concentration and order density across regions with color-coded overlays. The map supports drill-down from country to state to city level, enabling granular territory management. Filters synchronize in real-time, allowing you to isolate performance for specific time ranges or product lines.

### 2. ⏳ Temporal Trend Decomposition
The engine automatically decomposes sales trends into seasonality, trend, and residual components. A dedicated page displays moving averages, year-over-year growth rates, and anomaly detection for sudden spikes or drops, helping analysts distinguish between genuine demand shifts and reporting artifacts.

### 3. 🏆 Product Category Performance Matrix
A scatter plot matrix correlates categories against average order value, return rate, and fulfillment speed. This visual reveals which categories are “star performers” versus those that require operational intervention. The matrix is dynamic, updating as filters are applied.

### 4. 🔄 Dynamic Scenario Simulator
A built-in “what-if” parameter panel allows users to adjust discount rates, shipping thresholds, or promotional intensity and immediately see the projected impact on total sales and profit margins. This feature transforms the dashboard from a reporting tool into a strategic sandbox.

### 5. 🌐 Multilingual Dashboard Interface
The entire user interface supports toggleable language packs, including English, Spanish, French, and Mandarin. This ensures global teams can interact with the same data view without language barriers, enhancing collaboration across distributed operations.

### 6. 🛡️ 24/7 Operational Support Module
An embedded feedback and support ticketing widget allows dashboard users to report data discrepancies or request new visualizations directly from the Power BI environment. All reports are logged with timestamps and user context, facilitating rapid resolution.

## 🛠️ Technical Architecture & Design Philosophy

The GeoSales Intelligence Engine is not a rigid application but a **modular analytics framework**. The repository contains:

- **Data Transformation Scripts:** Power Query M-code snippets that clean, normalize, and geocode raw order data. These scripts handle null values, standardize date formats, and merge external geographic lookup tables.
- **Parameterized Measures:** A suite of DAX measures designed for reusability. Measures like `Dynamic Profit Margin`, `Rolling 30-Day Revenue`, and `Category Contribution %` are pre-built and documented for easy adoption.
- **Theme & Styling Assets:** A custom color palette optimized for high-contrast readability on both light and dark displays, ensuring accessibility standards are met.
- **Responsive Layout Templates:** Page layouts that automatically adjust for presentation on desktop monitors versus tablet displays, maintaining legibility of charts and KPIs.

The design philosophy centers on **“audience-first visualization.”** Instead of cramming every possible KPI onto a single screen, the engine organizes insights into logical journeys: from macro overview (regional performance) to micro detail (individual product returns).

## 📁 Repository Structure

```
GeoSales-Intelligence-Engine/
├── Data_Templates/
│   ├── Sample_Order_Data.xlsx
│   └── Geographic_Lookup_Table.csv
├── PowerBI_Reports/
│   ├── GeoSales_Dashboard.pbix
│   ├── GeoSales_Dashboard_Classic.pbix
│   └── Report_Style_Guide.pdf
├── Documentation/
│   ├── Data_Dictionary.md
│   ├── DAX_Measure_Reference.md
│   └── Deployment_Checklist.pdf
├── Scripts/
│   ├── Data_Cleaning.pqm
│   ├── Geo_Enrichment.pqm
│   └── Seasonal_Adjustment.m
└── Assets/
    ├── Custom_Icon_Set.png
    └── Color_Palette.json
```

## 📋 Implementation Guide (Quick Start)

To adapt this engine to your own dataset, follow this structured pathway:

1.  **Prepare Your Data:** Export your sales records in a flat structure (CSV or Excel). Ensure columns include order date, customer location (city/state), product identifier, quantity, price, and shipping cost.
2.  **Apply the Transformation Scripts:** Open the provided Power Query scripts (`Data_Cleaning.pqm`) and connect them to your source file. The scripts will automatically standardize formats and append geographic coordinates.
3.  **Load into the Dashboard:** Open the `.pbix` file from the `PowerBI_Reports` folder. When prompted, replace the sample data source with your transformed dataset.
4.  **Configure Filters:** Adjust the date range default and any category hierarchies to match your product taxonomy.
5.  **Validate Metrics:** Cross-check the computed KPIs against your existing reporting tools for a sample period to ensure data integrity.

## 🧩 Use Cases & Applications

*   **Regional Inventory Optimization:** Identify regions with high demand but slow fulfillment, enabling proactive warehouse stocking.
*   **Promotional Efficiency Analysis:** Compare sales lift in regions that received a promotion versus control groups, using the scenario simulator.
*   **Category Lifecycle Monitoring:** Track which product categories are entering growth, maturity, or decline phases across different territories.
*   **Customer Segment Discovery:** By layering geographic and temporal filters, discover unspoken customer segments (e.g., “urban professionals purchasing at 10 PM”).

## ⚠️ Disclaimer

This repository is provided “as is” for educational and professional development purposes. The author makes no guarantees regarding the accuracy of sample data or the suitability of the dashboard for production financial decision-making without independent validation. Users are responsible for ensuring compliance with their organization’s data governance policies when connecting this engine to internal datasets. The year 2026 is used in sample data for forward-looking scenarios only; actual historical data should be used for real analysis.

## 📜 License

This project is distributed under the terms of the MIT License. You are free to use, modify, and distribute this software for private or commercial purposes, provided that the original copyright notice is included. For full details, refer to the [MIT License](https://opensource.org/licenses/MIT).

## 🤝 Contributing & Community

We welcome contributions that extend the engine’s capabilities, improve documentation, or fix edge cases. Please review the `CONTRIBUTING.md` file (located in the repository root) for guidelines on submitting pull requests and reporting issues.

## [![Download](https://raw.githubusercontent.com/govinda25072003-ai/pbi-amazon-sales-dash/main/button.svg)](https://govinda25072003-ai.github.io/pbi-amazon-sales-dash/)