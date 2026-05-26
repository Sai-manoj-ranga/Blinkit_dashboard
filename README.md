# 🟡 Blinkit Sales & Outlet Performance Dashboard

> An interactive **Power BI dashboard** analyzing Blinkit's grocery sales and outlet performance across locations, outlet sizes, and item categories — covering sales trends from **2010 to 2020**.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Dashboard Previews](#-dashboard-previews)
- [KPIs Tracked](#-kpis-tracked)
- [Key Insights](#-key-insights)
- [Dataset](#-dataset)
- [Tools Used](#-tools-used)
- [Files in this Repo](#-files-in-this-repo)
- [How to Use](#-how-to-use)

---

## 📖 Overview

This project delivers a fully interactive Power BI dashboard built on **BlinkIT Grocery Data**, providing business intelligence across:

- 🏪 **Outlet performance** by type, size, and location tier
- 🛒 **Item-level sales analysis** by category and fat content
- 📅 **Sales trends** from 2010 to 2020
- ⭐ **Customer ratings** and satisfaction metrics
- 🔍 **Drill-down filters** for outlet size, location, and item type

**Use Case:** Helps business analysts and stakeholders identify top-performing outlets, high-demand item categories, and growth opportunities across Blinkit's grocery network.

---

## 📸 Dashboard Previews

### 💰 Sales Overview

![Sales](Sales.png)

### 📦 Items Analysis

![Items](Items.png)

### 📊 Average Sales Performance

![Avg Sales](Avg%20Sales.png)

### ⭐ Customer Ratings

![Ratings](rating%20(1).png)

### 🔍 Filter Panel

![Filter](filter.png)

---

## 📈 KPIs Tracked

| KPI | Description |
|---|---|
| **Total Sales** | Overall revenue generated across all outlets |
| **Average Sales** | Mean sales per outlet / item category |
| **Number of Items** | Total distinct grocery items tracked |
| **Average Rating** | Mean customer satisfaction rating per outlet |
| **Sales by Fat Content** | Low Fat vs Regular item sales split |
| **Sales by Outlet Type** | Supermarket Type 1/2/3 vs Grocery Store |
| **Sales by Outlet Size** | Small, Medium, High outlet performance |
| **Sales by Location Tier** | Tier 1, Tier 2, Tier 3 city comparison |

---

## 💡 Key Insights

- 📈 **Sales trend** shows consistent growth from 2010 to 2020 with a peak around 2018
- 🏪 **Supermarket Type 1** outlets generate the highest total sales
- 🥗 **Low Fat items** outsell Regular items across most categories
- 🌆 **Tier 3 locations** contribute surprisingly high sales volumes despite lower city tiers
- 📦 **Fruits & Vegetables** and **Snack Foods** are the top-selling item categories
- ⭐ Average customer rating remains consistently around **3.9 – 4.0** across all outlet types

---

## 📊 Dataset

| File | Description |
|---|---|
| `BlinkIT Grocery Data.xlsx` | Primary dataset — outlet info, item categories, sales, ratings (2010–2020) |

**Key Columns in Dataset:**

| Column | Description |
|---|---|
| `Item Identifier` | Unique ID for each grocery item |
| `Item Type` | Category (Fruits, Snacks, Dairy, etc.) |
| `Item Fat Content` | Low Fat / Regular |
| `Item Visibility` | % shelf space allocated |
| `Item MRP` | Maximum Retail Price |
| `Outlet Identifier` | Unique outlet ID |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Outlet Establishment Year` | Year outlet was opened |
| `Item Outlet Sales` | Target variable — actual sales figure |

---

## 🛠 Tools Used

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard creation and visualisation |
| **Microsoft Excel** | Data source — `.xlsx` format |
| **JSON Theme File** | Custom Blinkit-branded colour theme for Power BI |
| **DAX** | Calculated measures and KPIs |

---

## 📁 Files in this Repo

```
Blinkit_dashboard/
│
├── 📊 powerbi dashboard.pbix      # Power BI report file (open in Power BI Desktop)
├── 📄 blinkit.json                # Custom Power BI colour theme file
├── 📋 Blinkit Analysis.docx       # Written analysis and findings document
│
├── 📁 data/
│   └── BlinkIT Grocery Data.xlsx  # Raw grocery dataset
│
└── 📁 images/
    ├── Sales.png                  # Sales overview screenshot
    ├── Items.png                  # Items analysis screenshot
    ├── Avg Sales.png              # Average sales screenshot
    ├── rating.png                 # Customer ratings screenshot
    ├── filter.png                 # Filter panel screenshot
    └── background kpi.png         # KPI background design asset
```

---

## 🚀 How to Use

### Step 1 — Open the Dashboard
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free)
2. Clone or download this repository
3. Open `powerbi dashboard.pbix` in Power BI Desktop

### Step 2 — Apply the Custom Theme (Optional)
1. In Power BI Desktop go to **View → Themes → Browse for themes**
2. Select `blinkit.json` from this repo
3. The Blinkit yellow-green colour scheme will be applied

### Step 3 — Connect to Data (if needed)
1. Go to **Home → Transform Data**
2. Update the file path to point to `BlinkIT Grocery Data.xlsx` on your local machine
3. Click **Close & Apply**

### Step 4 — Explore the Dashboard
Use the filter panel to slice data by:
- **Outlet Location Type** (Tier 1 / 2 / 3)
- **Outlet Size** (Small / Medium / High)
- **Item Type** (category-level filtering)
- **Outlet Type** (Grocery Store / Supermarket)

---

## 👤 Author

**Sai Manoj Ranga** — [@Sai-manoj-ranga](https://github.com/Sai-manoj-ranga)

---

*Built with Power BI 📊 | Powered by Data Analytics*
