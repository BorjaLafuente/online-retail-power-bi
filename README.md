# Online Retail II: sales analysis in Power BI

> 🚧 **Work in progress.** The data model and report are being built. This README will be completed with screenshots and findings.

Sales dashboard for a UK-based online retailer of giftware, built in Power BI on two years of real transactions (December 2009 to December 2011, about one million invoice lines).

## Planned content

- **Sales overview**: revenue, orders and average order value, with year-on-year comparison.
- **Customers**: RFM segmentation (recency, frequency, monetary value).
- **Products**: Pareto analysis, the share of revenue that comes from the top products.
- **Geography**: sales by country.

## Progress

- [x] Load and combine the two sheets of the source file, removing a week duplicated in both
- [ ] Data cleaning: cancellations, non-product codes, missing customers
- [ ] Star schema: sales fact table with product, customer and calendar dimensions
- [ ] DAX measures
- [ ] Report pages
- [ ] Documentation and screenshots

## Data

[Online Retail II](https://doi.org/10.24432/C5CG6D), UCI Machine Learning Repository (Chen, 2012), under a CC BY 4.0 license. The data file is not included in this repository: download it from the link above and save it as `data/online_retail_II.xlsx`.

## Tools

Power BI Desktop · Power Query (M) · DAX · saved in Power BI Project format (`.pbip`), so the model and report are plain-text files that can be versioned with Git.