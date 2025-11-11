Glassmorphism Sales Dashboard — README
🌟 Overview
The Glassmorphism Sales Dashboard is a modern, interactive, browser-based analytics tool designed to visualize sales performance with a sleek, frosted-glass UI. This project combines clean design, smooth interactions, and data-driven insights to help users instantly understand patterns in sales, product performance, and regional distribution.
The dashboard reads JSON sales data and automatically generates real-time visualizations using Plotly.js.

✨ Features
✅ Interactive Glassmorphism UI
A modern frosted-glass look created using:


Transparent layers


Blur effects


Smooth shadows


Rounded cards


✅ Upload & Visualize JSON instantly
Just upload your sales.json file. The dashboard:


Reads the file


Processes all records


Updates every chart dynamically


✅ 5 Auto-Generated Insights


Monthly Sales Trend
Visualizes growth, seasonality, and performance changes.


Sales by Product
Identifies top-selling and low-performing products.


Sales by Region
Helps understand market strength across areas.


Category Contribution
A donut chart showing category-wise breakdown.


Top Cities by Sales
A horizontal bar chart ranking top performing cities.



📂 File Structure
project-folder/
│── sales_dashboard_glassmorphism.html
│── sample_sales.json  (optional)


🧪 JSON File Format
Your uploaded file must follow this structure:
[
  {
    "Date": "2024-01-15",
    "Product": "Laptop",
    "Category": "Electronics",
    "Region": "North",
    "City": "Delhi",
    "TotalSales": 65000
  }
]

The dashboard automatically:


Parses the data


Groups fields


Summarizes values


Builds charts



⚙️ Tech Stack


HTML5


CSS3 (Glassmorphism design)


JavaScript


Plotly.js (for interactive charts)



🚀 How to Use


Download the file:
sales_dashboard_glassmorphism.html


Open it in any browser
Chrome, Firefox, Edge etc.


Click Upload Sales JSON File


Select your JSON data


View 5 dashboards instantly


No backend. No installation. Pure client-side magic.

🎯 Why This Project Matters
This dashboard showcases:


Frontend UI design skills


Data visualization ability


Interactive dashboard building


Clean and modern web styling


Real-world analytics workflow


Perfect to add in:


Resume


Portfolio


GitHub


Data analytics projects section



📝 Author
Azi
Data Analytics & Modern UI Enthusiast
