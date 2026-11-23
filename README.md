# Retail Sales Analytics | Power BI & Excel

A retail analytics project using Excel for data preparation and Power BI for an interactive report. The dataset is labeled `BlinkIT Grocery Data` and includes product attributes, sales, ratings and outlet information.

## Report coverage

The Power BI file contains a **Financial Analysis** page with:

- Summary metrics for total sales, average sales, average rating and number of items.
- Sales breakdowns by item type and fat content.
- Outlet comparisons by location type, size, type and establishment year.
- Slicers for outlet location, outlet size and item type.
- A metric selector and bookmark-based controls.

## Workflow

1. Prepare the source data in Excel, including duplicate, missing-value and error checks.
2. Use the cleaned workbook as the reporting input.
3. Build measures and interactive visuals in Power BI using DAX, slicers and bookmarks.

## Repository guide

| File | Purpose |
| --- | --- |
| [Shop Online (uncleaned data).xlsx](Shop%20Online%20%28uncleaned%20data%29.xlsx) | Original source workbook supplied with the project |
| [Shop Online (cleaned data).xlsx](Shop%20Online%20%28cleaned%20data%29.xlsx) | Prepared workbook |
| [Power PI Project/shop online.pbix](Power%20PI%20Project/shop%20online.pbix) | Power BI report and model |

The existing folder name `Power PI Project` is preserved so existing file paths remain valid.

## Explore the project

1. Download the repository.
2. Compare the source and cleaned Excel workbooks to inspect the preparation output.
3. Open `shop online.pbix` in Power BI Desktop and explore the filters and report controls.
4. Before refreshing, review the Power Query source settings and update local workbook paths where needed.

GitHub stores the report file but does not provide an interactive Power BI viewer. Refresh can depend on local file paths and the installed Power BI version.

## Interpretation

The report explores relationships in the supplied retail data. Sales are not profit, and comparisons across outlet establishment years are not a sales time series. No verified business improvement or causal result is claimed.

The original workbooks and Power BI file are retained unchanged.
