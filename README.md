# power-bi

## 📌 Project Overview
This repository contains a Power BI analytics project built on the **Superstore** dataset. The primary deliverable is `project 1.pbix`, an interactive report that visualizes sales, profit, and customer performance across regions and product categories.

> **Goal**: Transform raw transactional data into a clean, analysis-ready model for business insights.

 **Source** | Load raw data from CSV/Excel |
 **Promoted Headers** | Convert the first row into column headers |
 **Changed Type** | Set initial data types (text, number, date) |
 **Changed Type with Locale** | Parse dates/currency using correct locale settings |
**Capitalized Each Word** | Standardize text casing (e.g., "new york" → "New York") 
| **Added Custom** | First custom column (e.g., derived fields) |

 **Added Custom1** | Second custom column (e.g., calculations) |
 **Added Custom2** | Third custom column (e.g., flags or categories) |

> 💡 **Tip**: Rename these custom steps to descriptive names (e.g., `Added Profit Margin`, `Added Region Code`) for easier maintenance.

## 📊 Data Sources & Schema
| Source | Type | Update Frequency | Notes |
|--------|------|------------------|-------|
| Superstore Raw | CSV/Excel | Manual/Ad-hoc | `superstore_raw` query |

### Key Columns
- `Order Date`, `Ship Date` (Date)
- `Segment`, `Category`, `Region` (Text, capitalized)
- `Sales`, `Profit` (Decimal Number)

## 🎯 Key Features
- **Cleaned Data Model**: Text normalization, type-safe dates, and locale-aware parsing.
- **Derived Metrics**: Custom columns for business logic (e.g., profit margins, region codes).
- **Interactive Dashboards**: Drill-down by segment, category, and region.

