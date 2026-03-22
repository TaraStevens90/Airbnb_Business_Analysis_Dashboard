# 🏙️ NYC Airbnb Stakeholder Dashboard

This project analyzes mock Airbnb listing data across New York City boroughs using Microsoft Excel. It was developed as part of the CIS&210 Business Analysis final project and includes cleaned data, pivot tables, interactive charts, and dashboard instructions tailored for stakeholder use.

---

## 📊 Analysis & Visualizations

The dashboard explores pricing, availability, and guest engagement across boroughs and neighborhoods using pivot tables and dynamic charts.

### Key Visualizations:

- **Room Availability by Borough**  
  Pie chart showing listing counts by room type (Entire Home/Apt, Private Room, Shared Room) across boroughs.

- **Average Listing Price by Borough**  
  Interactive chart with slicers for room type and minimum nights. Reveals pricing trends by listing category and stay duration.

- **Sum of Reviews by Borough**  
  Dynamic graph tracking monthly and cumulative review counts. Filters include listing price and room type.

- **Total Reviews by Borough (Map View)**  
  Map visualizing borough-level review volume. Hovering reveals borough-specific totals.

- **Review Count by Length of Stay**  
  Bar chart showing review volume by stay duration (e.g., 1, 30, 60, 90, 180, 365 nights), filtered by review year and month.

- **Average Length of Stay by Borough**  
  Comparative chart showing borough-level averages for minimum night requirements.

- **Distribution of Listing Types Across Boroughs**  
  Stacked bar chart visualizing listing type proportions within each borough.

- **Neighborhood-Level Insights**  
  Ranked table highlighting top neighborhoods by average price, total reviews, and listing count.

---

## 🎨 Color Choices

The dashboard uses the official Airbnb brand colors for a cohesive and professional visual design:

The hex codes were applied consistently across charts and slicers to maintain brand familiarity.

---

## 📸 Screenshots

### Clean Data View  
![Cleaned Airbnb dataset showing structured columns and mock data](screenshots/Clean_Data_View.png)

### Pivot Tables  
![Pivot tables sheet summarizing listing counts, prices, and review metrics by borough and room type](screenshots/Pivot_Tables.png)

### Charts 1  
![Dashboard charts including Room Availability, Average Price, and Sum of Reviews](screenshots/Charts_1.png)

### Charts 2  
![Additional dashboard charts showing Review Count by Stay Length and Listing Type Distribution](screenshots/Charts_2.png)

### Dashboard  
![Full dashboard layout with interactive slicers and borough-level visualizations](screenshots/Dashboard.png)

### Dashboard Instructions  
![Dashboard instructions sheet detailing slicer logic, chart interactivity, and report connections](screenshots/Dashboard_Instructions.png)

---

## 🧭 Dashboard Interactivity & Instructions

Each chart is designed to be intuitive and responsive, with slicers and report connections that allow users to explore NYC Airbnb data dynamically.

### Chart Instructions:

| Chart | Interactive | Slicers | Report Connections |
|------|-------------|---------|---------------------|
| **Average Listing Price by Borough** | ✅ | Minimum Night, Room Type | Updates monthly and total reviews in "Sum of Reviews" |
| **Total Reviews by Borough (Map View)** | ✅ and hover | None directly | Updates based on "Sum of Reviews" filters |
| **Sum of Reviews by Borough** | ✅ | Listing Price, Room Type | Drives updates to map and review-based visuals |
| **Review Count by Length of Stay** | ✅ | Review Year, Review Month | Tailored to key intervals (30, 60, 90 days); selective report connections |

---

## 📁 Project Files

- `Airbnb_Business_Analysis_Dashboard.xlsx`  
  Contains all sheets: Cleaned Data, Pivot Tables, Charts, Interactive Dashboard, and Dashboard Instructions.

- `/screenshots` folder  
  Includes six labeled images for README documentation:
  - Clean_Data_View.png
  - Pivot_Tables.png
  - Charts_1.png
  - Charts_2.png
  - Dashboard.png
  - Dashboard_Instructions.png

- `Airbnb_Dashboard_Overview.pdf`  
  Optional downloadable version of the dashboard for offline viewing and stakeholder sharing.

---

## 🚫 Note

This README focuses on technical documentation and dashboard usage. Personal analysis and insights were submitted separately as part of an essay assignment.

---

## ✅ Summary Metrics

- **Total Reviews:** 996,628  
- **Average Listing Price:** $150.12  
- **Top Neighborhood:** Bedford-Stuyvesant

---

For stakeholders, this dashboard offers a clear, interactive view of NYC Airbnb trends, enabling data-driven decisions around pricing, availability, and guest engagement.
