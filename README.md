# Youtube-Analytics-Insight
📊 Interactive Power BI YouTube Analytics Dashboard analyzing views, watch time, likes, videos, sources, and audience geography. Built with Power Query, DAX, and data visualization to identify content performance, audience engagement, top sources, and key insights for data-driven YouTube growth.
# 📺 YouTube Analytics & Insights Dashboard – Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![YouTube](https://img.shields.io/badge/YouTube-Analytics-red?style=for-the-badge&logo=youtube)
![DAX](https://img.shields.io/badge/DAX-Measures-orange?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-green?style=for-the-badge)

---

## 📊 Project Overview

The **YouTube Analytics & Insights Dashboard** is an interactive Power BI project designed to analyze YouTube channel and video performance using data visualization and business intelligence techniques.

The dashboard transforms raw YouTube analytics data into meaningful insights related to views, watch time, likes, dislikes, sources, videos, audience geography, and overall content performance.

The main purpose of this project is to understand audience engagement, identify high-performing content, analyze traffic sources, and support data-driven content decisions.

---

## 🎯 Project Objective

The main objective of this project is to develop an interactive and visually appealing Power BI dashboard that provides a complete overview of YouTube performance.

The dashboard helps analyze:

- 👁️ Total Views
- ⏱️ Watch Time
- 👍 Total Likes
- 👎 Total Dislikes
- 🔗 Source Performance
- 🎥 Video Performance
- 🌍 Audience Geography
- 📊 Content Performance
- 💡 Key Insights

The project demonstrates how raw analytics data can be converted into an easy-to-understand business intelligence dashboard.

---

## 🗂️ Dataset

The project uses a YouTube analytics dataset containing information related to video performance, views, likes, dislikes, sources, video titles, and geographical information.

The dataset was imported into Microsoft Power BI and prepared for analysis.

Before creating the dashboard, the dataset was cleaned, transformed, structured, and prepared for visualization.

---

## 🧹 Data Cleaning & Transformation

The dataset was prepared using **Power Query** before building the dashboard.

The data preparation process includes:

- Removing unnecessary columns
- Handling missing values
- Correcting data types
- Cleaning text fields
- Standardizing column names
- Removing duplicate records where required
- Formatting numeric fields
- Preparing data for visualization

Clean and consistent data is important for producing accurate dashboard results.

---

## 🔄 Power Query Transformation

After the initial cleaning process, additional transformations were performed using Power Query.

### Transformation Activities

- Changed appropriate data types
- Renamed columns for better understanding
- Removed unnecessary fields
- Standardized text values
- Applied filters where required
- Organized categorical and numerical fields
- Prepared the dataset for Power BI modeling

Power Query helped convert the raw dataset into a structured and analysis-ready format.

---

## 🧩 Data Modeling

After cleaning and transformation, the prepared data was structured inside the Power BI data model.

Data modeling allows Power BI to correctly work with different fields and calculations.

### Data Modeling Activities

- Organized tables and fields
- Identified relevant columns
- Created relationships where required
- Checked relationship direction
- Verified data types
- Prepared the model for calculations
- Created a logical reporting structure

A proper data model improves the accuracy and reliability of dashboard calculations.

---

## 🧮 DAX Measures

**DAX (Data Analysis Expressions)** was used to create calculated measures and important performance metrics.

The measures were used throughout the dashboard for dynamic calculations.

### Important Metrics

- Total Views
- Total Watch Time
- Total Likes
- Total Dislikes
- Source Count
- Channel Count
- Video Count
- Performance-related calculations

Example calculations include:

    Total Views = SUM('YouTube'[Views])

    Total Likes = SUM('YouTube'[Likes])

    Total Dislikes = SUM('YouTube'[Dislikes])

    Total Watch Time = SUM('YouTube'[Watch Time])

> Note: Column and table names may vary depending on the actual dataset structure.

---

## 📊 Data Visualization

After completing data cleaning, transformation, data modeling, and DAX calculations, different Power BI visualizations were created.

Each visual was selected according to the type of analysis required.

| Visualization | Purpose |
|---|---|
| KPI Cards | Display important performance metrics |
| Bar Chart | Compare sources and videos |
| Donut Chart | Analyze category distribution |
| Map | Analyze geographical distribution |
| Table | Display top-performing videos |
| Insights Panel | Highlight important findings |

The combination of these visuals provides a complete overview of YouTube performance.

---

## 🎯 KPI Cards

The dashboard contains five major KPI cards.

### 👁️ Total Views

**240.514K**

This KPI represents the total number of views generated by the analyzed YouTube content.

Views are an important indicator of content reach and audience exposure.

### ⏱️ Watch Time

**169.616K**

This KPI represents the total watch time recorded in the dataset.

Watch time provides a deeper understanding of audience engagement because it indicates how much time viewers spent consuming the content.

### 👥 Channel Count

**419.211K**

This KPI represents the calculated channel-related activity available in the dataset.

### 🔗 Source Count

**422.371K**

This KPI represents the calculated source-level activity available in the dataset.

### 👍 Total Likes

**73.787K**

This KPI represents the total number of likes received by the analyzed content.

Likes provide an important indication of viewer interaction and audience response.

---

## 📈 Top 10 Source Name

The **Top 10 Source Name** visual identifies the leading sources available in the dataset.

### Purpose

This visual helps understand:

- Which sources contribute the most activity
- Which sources are important for performance
- How source activity is distributed
- Which sources require further analysis

Source-level analysis can help identify valuable traffic or activity sources.

---

## 🍩 Count of Likes by Source Name

A **Donut Chart** is used to visualize the distribution of likes across different sources.

### Purpose

It helps understand:

- Which sources generate more likes
- How engagement is distributed
- Which sources contribute significantly to total likes
- Differences in audience interaction

The donut chart provides a quick visual comparison between different source categories.

---

## 📉 Top 10 Dislikes by Video

The **Top 10 Dislikes by Video** visual identifies videos with comparatively higher dislike counts.

### Purpose

This analysis helps identify:

- Videos receiving higher negative feedback
- Content that may require improvement
- Differences in viewer reactions
- Videos requiring further investigation

Negative feedback can provide useful information when evaluating content performance.

---

## 🎥 Top Videos

The **Top Videos** section displays the leading videos based on the selected performance metric.

### Purpose

It helps identify:

- Best-performing videos
- High-view videos
- Popular content
- Content that attracts audience attention

Analyzing top-performing videos helps understand which types of content perform well.

---

## 🌍 Top Geographies

The **Top Geographies** section provides a geographical view of the audience.

A map is used to visualize where viewers are located.

### Purpose

Geographical analysis helps understand:

- Major audience locations
- Regional audience distribution
- Potential target markets
- Opportunities for localized content

Understanding audience geography can help improve content targeting and future strategy.

---

## 🍩 Video by Title

The **Video by Title** visualization compares performance across different video titles.

### Purpose

This visual helps determine:

- Which video titles perform better
- Which videos contribute more to overall activity
- Differences between individual videos
- Potential high-performing content patterns

This analysis can be useful for future content planning.

---

## 💡 Key Insights

The dashboard contains a dedicated **INSIGHTS** section that summarizes the most important findings from the analysis.

### 🟢 Strong audience reach with 240.51K views

The dashboard generated approximately **240.51K views**, showing strong overall audience reach across the analyzed content.

This indicates that the analyzed videos were able to attract a substantial number of viewers.

### 🟢 169.62K watch time shows good engagement

The dashboard recorded approximately **169.62K watch time**, indicating meaningful viewer activity and engagement with the content.

Watch time provides additional information beyond simple view counts because it reflects the amount of time viewers spend consuming the content.

### 🟢 73.79K likes indicate positive interaction

Approximately **73.79K likes** were recorded in the dataset.

This indicates strong viewer interaction with the analyzed content and provides an additional measure of audience response.

### 🟢 Top content drives overall performance

The **Top Videos** and **Video by Title** analysis shows that content performance varies between videos.

Some videos contribute more significantly to overall activity.

Identifying these high-performing videos can help understand successful content patterns and improve future content planning.

---

## 🔍 Business Questions Answered

The dashboard helps answer several important business and analytical questions.

### 👥 Audience Performance

- How many views were generated?
- How much watch time was recorded?
- How strong is audience interaction?
- Which geographical areas contribute to the audience?

### 🎥 Content Performance

- Which videos perform the best?
- Which videos receive higher engagement?
- Which videos receive comparatively higher dislikes?
- Which content contributes significantly to overall performance?

### 🔗 Source Performance

- Which sources contribute the most activity?
- Which sources generate more likes?
- Which sources should receive additional attention?

### 🌍 Geographic Performance

- Where are viewers located?
- Which regions contribute significantly to the audience?
- Which geographical markets could be targeted?

---

## 💼 Business Value

The dashboard converts raw YouTube analytics data into meaningful business intelligence.

It can help content creators and analysts:

- 📊 Monitor channel performance
- 🎥 Identify successful content
- 👥 Understand audience behavior
- 🌍 Analyze audience locations
- 🔗 Evaluate source performance
- ❤️ Measure audience interaction
- 💡 Make data-driven decisions

Instead of manually analyzing large amounts of raw data, users can quickly identify important trends and patterns through the dashboard.

---

## 🚀 Recommendations

Based on the dashboard analysis, the following recommendations can be considered.

### 1. 🎥 Focus on Top-Performing Content

Analyze the topics, formats, and styles of successful videos and use those findings when planning future content.

### 2. 👥 Improve Audience Engagement

Create engaging content with strong introductions and clear calls-to-action to encourage viewer interaction.

### 3. ⏱️ Monitor Watch Time

Views should not be analyzed alone. Watch time should also be monitored to understand the quality of audience engagement.

### 4. 🌍 Understand Audience Geography

Geographical insights can help identify important regions and support better content targeting.

### 5. 📉 Monitor Negative Feedback

Videos with comparatively higher dislikes should be reviewed to identify possible areas for content improvement.

### 6. 🔗 Analyze Source Performance

Regularly monitor source performance to identify the most valuable sources of audience activity.

---

## 🎨 Dashboard Design

The dashboard uses a modern **YouTube-inspired Dark + Red theme**.

### Design Features

- ⚫ Dark background
- 🔴 YouTube red highlights
- 🔵 Blue analytical elements
- 🟢 Green insight indicators
- 🟣 Purple engagement elements
- 🟡 Yellow source elements
- ✨ Neon-style visual accents
- 🖥️ Modern KPI cards
- 📊 Clean analytical layout

---

## 🎨 Dashboard Color Palette

| Element | Hex Code |
|---|---|
| Dashboard Background | `#020609` |
| KPI Card Background | `#07121C` |
| Card Border | `#263A4F` |
| YouTube Red | `#FF0000` |
| Insight Green | `#00C853` |

The dark background provides strong contrast and makes KPI cards and visuals visually prominent.

---

## 🖥️ Dashboard Layout

The dashboard is divided into multiple analytical sections.

### Header Section

The header contains:

**YouTube Analytics & Insights**

with the subtitle:

**TRACK. ANALYZE. IMPROVE. GROW.**

The header communicates the overall purpose of the dashboard.

### KPI Section

The top section contains five KPI cards:

- 👁️ Views
- ⏱️ Watch Time
- 👥 Channel Count
- 🔗 Source Count
- 👍 Total Likes

These KPIs provide a quick overview of overall performance.

### Source Analysis Section

This section contains:

- 📈 Top 10 Source Name
- 🍩 Count of Likes by Source Name
- 📉 Top 10 Dislikes by Video

This section focuses on source-level activity and audience interaction.

### Content & Audience Section

This section contains:

- 🎥 Top Videos
- 🌍 Top Geographies
- 🍩 Video by Title
- 💡 Key Insights

This section focuses on content performance, audience geography, and important findings.

---

## 🔄 Project Workflow

The complete project workflow follows these steps:

**Raw Data**

↓

**Data Import**

↓

**Data Cleaning**

↓

**Power Query Transformation**

↓

**Data Modeling**

↓

**DAX Measures**

↓

**Data Visualization**

↓

**Dashboard Development**

↓

**Key Insights**

↓

**Business Recommendations**

---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- KPI Development
- Dashboard Design
- Business Intelligence
- Data Storytelling
- Content Performance Analysis
- Audience Analysis
- Geographic Analysis
- Source Analysis

---

## 🛠️ Tools & Technologies

| Tool / Technology | Usage |
|---|---|
| 📊 Microsoft Power BI | Dashboard & Visualization |
| 🔄 Power Query | Data Cleaning & Transformation |
| 🧮 DAX | Measures & Calculations |
| 📁 CSV Dataset | Source Data |
| 📈 Power BI Visuals | Data Analysis |
| 🐙 GitHub | Project Documentation & Version Control |

---

## 📁 Project Structure

The recommended GitHub repository structure is:

YouTube-Analytics-Power-BI/

├── 📊 YouTube Analytics.pbix  
├── 📸 Dashboard Screenshot.png  
├── 📄 README.md  
└── 📁 Dataset/  
    └── YouTube Analytics Dataset.csv

---

## 🎯 Project Outcome

The final Power BI dashboard successfully converts raw YouTube analytics data into an interactive analytical report.

The dashboard provides a centralized view of:

**Views + Watch Time + Likes + Sources + Videos + Geography + Insights**

This allows users to quickly understand overall performance and identify important areas for improvement.

---

## 🔮 Future Improvements

The dashboard can be further enhanced by adding:

- 📅 Date-based slicers
- 📱 Device Type Analysis
- 👥 Subscriber Growth Analysis
- 📈 Views Forecasting
- 🔮 Predictive Analytics
- 🎯 Engagement Rate
- ⏰ Best Publishing Time Analysis
- 🎥 Video Category Analysis
- 📊 Advanced Drill-Through Pages
- 💡 Dynamic DAX-Based Insights
- 📌 Interactive Filters
- 📑 Additional Dashboard Pages

---

## 🏆 Conclusion

The **YouTube Analytics & Insights Dashboard** demonstrates how Power BI can transform raw YouTube analytics data into meaningful and actionable business intelligence.

Using **Power Query, Data Modeling, DAX, and Power BI Visualizations**, the project provides insights into:

- Audience reach
- Watch time
- Viewer engagement
- Video performance
- Source performance
- Geographic distribution
- Likes and dislikes
- Overall channel activity

The dashboard makes it easier to identify high-performing content, understand audience behavior, and support data-driven content decisions.

---

## 👨‍💻 Author

### Hardik Kumar

**Data Analytics Skills:**

`Power BI` • `Excel` • `SQL` • `Python` • `DAX` • `Power Query` • `Data Analytics`

---

## ⭐ If You Like This Project

If you found this project useful or interesting:

⭐ Star this repository  
🍴 Fork the repository  
📢 Share the project  
💬 Provide feedback

---

## 🔖 Tags

`Power BI` `YouTube Analytics` `YouTube Dashboard` `Data Analytics` `Business Intelligence` `Power Query` `DAX` `Data Visualization` `Dashboard` `Data Analysis` `YouTube Data` `Analytics Dashboard` `Power BI Project`

---

## 🚀 Final Message

> **DATA DRIVES DECISIONS.**  
> **INSIGHTS DRIVE GROWTH.**  
> **CREATE BETTER. GROW FASTER. SUCCEED TOGETHER.**
