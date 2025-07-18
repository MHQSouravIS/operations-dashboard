# Operations Dashboard: Vendor and Item Analysis

This dashboard provides insights into vendor performance and item pricing based on various filters. Use the interactive controls to explore data for specific hospitals, item categories, items, and vendors.

## How to Use the Dashboard

1.  **Select Filters:** Use the dropdown menus at the top to select criteria for your analysis:
    *   **Select Hospital:** Choose a specific hospital or 'All Hospitals' to analyze data across all locations.
    *   **Select Parent Category:** Narrow down the analysis to items within a specific parent category or select 'All Categories'.
    *   **Select Vendor:** Focus on a particular vendor or select 'All Vendors' to compare vendors.
    *   **Select Item:** Choose a specific item. Note that the available items in this dropdown will update based on your Hospital, Parent Category, and Vendor selections. Select 'All Items' to see aggregated results for the applied filters.

2.  **Analyze Data:** After making your selections, click the **Analyze Data** button. The dashboard will update to display the relevant analysis based on your chosen filters.

## Understanding the Outputs

The dashboard provides different views depending on whether you have selected a specific vendor or are analyzing across all vendors ('All Vendors').

### When 'All Vendors' is Selected:

*   **Vendor with the Lowest Item Rate:** This table shows the vendor(s) offering the lowest price ('Item Rate') for the selected item(s) and filters. The 'Item Rate' is highlighted in light green to make it easy to spot the lowest price. This helps identify the most cost-effective source for the item(s) under consideration.
*   **Top 10 Vendors by Item Rate (Lowest to Highest):** This table lists the top 10 vendors based on their 'Item Rate' for the selected item(s) and filters, sorted from the lowest rate upwards. The 'Item Rate' column uses a green color gradient to visually represent the relative prices among these top vendors – darker green indicates a lower rate. Below the table, a bar chart visually compares the 'Item Rate' of these top 10 vendors, providing a quick overview of price variations.

### When a Specific Vendor is Selected:

*   **Items provided by [Selected Vendor]:** When you select a specific vendor, the dashboard lists the unique items that vendor has provided based on the other applied filters (Hospital and Parent Category), along with the 'Total Value' for each item. This helps understand the range of items a specific vendor supplies and their total contribution.

## Styling and Formatting

Numerical values in the results tables, especially the 'Item Rate', are styled (e.g., highlighted in green) to draw attention to key data points and make comparisons easier. The top 10 vendors table uses a color gradient on the 'Item Rate' to visually represent the price range.
