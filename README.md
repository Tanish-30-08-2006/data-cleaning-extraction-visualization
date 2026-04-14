# 📊 PowerBI Sales Report & Data Transformation Journey

Hey there! 👋 Welcome to my PowerBI Data Analytics project. I took raw sales data, cleaned it up, engineered new features, and built an interactive dashboard to visually track key sales targets and trends.

Before diving into the technical details, check out the final interactive dashboard in action below!

### 🎬 See the Report in Action



<details>
  <summary><b>▶️ Click here to view the Interactive Dashboard Action</b></summary>
  <br>
  <p align="center">
    <video src="assets/screen_recordings/PowerBI_Sales_Report_Recording_1.mp4" controls width="800"></video>
    <br><br>
    <video src="assets/screen_recordings/PowerBI_Sales_Report_Recording_2.mp4" controls width="800"></video>
  </p>
</details>
<br>

<details>
  <summary><b>🖼️ Click here to view static screenshots of the dashboard</b></summary>
  <br>
  <img src="assets/screenshots/report_image_1.png" alt="Report 1" width="800">
  <br><br>
  <img src="assets/screenshots/report_image_2.png" alt="Report 2" width="800">
  <br><br>
  <img src="assets/screenshots/report_image_3.png" alt="Report 3" width="800">
</details>

---

## 📈 The PowerBI Report (Dashboard Features)

I designed this dashboard to make exploring the sales data as intuitive as possible. Here is a breakdown of the key features I implemented to bring the data to life:

* **🎯 Target KPIs (Key Performance Indicators):**
  I built custom KPI tracking to measure performance against specific goals. For example, I set a dynamic target of $40K—the visual automatically shifts to Green (target hit) or Red (target missed) based on current real-time sales.

* **🖱️ Interactive Toggles (Bookmarks & Action Buttons):**
  To save space and keep the dashboard looking clean, I used overlapping visuals. By linking Action Buttons to Bookmarks, you can click a button to seamlessly switch the view from a visual Bar Chart directly to a detailed Matrix table in the exact same spot!

* **🔍 Drill-Through for Detailed Insights:**
  Curious about a specific product segment? I set up Drill-Through pages. If you spot "Laptops" on the main page, you can simply right-click it and drill through directly to a separate, dedicated page breaking down that specific product's underlying stats and description.

* **🌳 Decomposition Trees:**
  I used Decomposition Trees to investigate the structural flow of our sales. It acts like a dynamic flowchart (e.g., breaking down *Product Category* ⮕ *Product Name* ⮕ *Unit Price*) to let the user easily investigate exactly where the biggest numbers are coming from.

* **📊 Smart Charting & Custom Grouping:**
  * **Line & Bar Charts:** I used a dedicated `Date` table to track time-based trends exactly (like viewing last quarter's total sales day-by-day).
  * **Data Groupings & Bins:** I categorized scattered data into logical groups. For instance, I grouped multiple scattered cities into "Tier 1" and "Tier 2" markets, and utilized grouping bins to create neat histogram slices.
  * **Tooltips:** I configured custom tooltips so when you hover your mouse over any bar or pie slice, a floating box appears with instant extra info.

* **🎛️ Dynamic Filtering:**
  I implemented a robust filter structure depending on the need: allowing users to filter inside a single visual box, filtering everything across a single page, or persisting filters globally across the whole report.

<br>

*(Next up: Feature Extraction section!)*
