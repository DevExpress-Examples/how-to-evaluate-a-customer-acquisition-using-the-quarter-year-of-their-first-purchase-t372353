<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Dashboard_AggrCohortAnalysis/Form1.cs) (VB: [Form1.vb](./VB/Dashboard_AggrCohortAnalysis/Form1.vb))
<!-- default file list end -->

# Dashboard for WinForms - How to evaluate a customer acquisition using the quarter/year of their first purchase

This example shows how to evaluate a customer acquisition by grouping customers by the quarter/year of their first purchase to compare sales contributions.

## Example Structure

The [Chart](https://docs.devexpress.com/Dashboard/14719/winforms-dashboard/winforms-designer/create-dashboards-in-the-winforms-designer/dashboard-item-settings/chart) dashboard item below displays quarterly sales.

![screenshot](/images/aggr_example3_cohortanalysis122827.png)

The following expression determines the quarter when customers made their first purchase.

```
aggr(Min(GetDateQuarterYear([OrderDate])), [CustomerID])
```

![screenshot](/images/aggr_example3_cohortanalysis_result122828.png)

## Documentation

- [Intermediate Level Aggregations](https://docs.devexpress.com/Dashboard/115870/)
- [Aggregations](https://docs.devexpress.com/Dashboard/115894/)
- [Expression Constants, Operators, and Functions](https://docs.devexpress.com/Dashboard/400122/)

## More Examples

- [Dashboard for WinForms - How to display best and worst monthly sales for each year](https://github.com/DevExpress-Examples/how-to-display-best-and-worst-monthly-sales-for-each-year-t369371)
- [Dashboard for WinForms - How to Calculate the Contribution of Quarterly Sales to Total Yearly Sales](https://github.com/DevExpress-Examples/how-to-calculate-the-contribution-of-quarterly-sales-to-total-yearly-sales)
- [Dashboard for WinForms - How to divide customers' count by the number of orders they made](https://github.com/DevExpress-Examples/how-to-divide-customers-count-by-the-number-of-orders-they-made-t372356)
- [Dashboard for WinForms - How to calculate Highest Product Sales by Year](https://github.com/DevExpress-Examples/how-to-show-products-with-the-best-sales-in-a-year-along-with-sales-values-t372408)
- [Dashboard for WinForms - How to display sales by years in comparison with the previous year's sales](https://github.com/DevExpress-Examples/win-dashboard-display-previous-year-sales)
- [Dashboard for WinForms - How to Display Product Sales that are Greater than $20k](https://github.com/DevExpress-Examples/How-to-Display-Product-Sales-that-are-Greater-than-20k)
- [Dashboard for WinForms - How to Display Products with Sales Greater than Average Sales per Category](https://github.com/DevExpress-Examples/How-to-Display-Product-with-Sales-Greater-than-Average-Sales-per-Category)
