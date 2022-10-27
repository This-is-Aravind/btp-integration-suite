<!-- loio78bde6f695a44a81bf20080289584d36 -->

# Customizing an Analysis

The analytics dashboard allows you to customize an analysis using specific dimensions and measures.



## Context

You can create custom charts using selected dimensions and measures to analyze the performance of APIs.



## Procedure

1.  Select *Analyze Data* in the bottom-right corner of the screen.

2.  Enter a chart title of your choice in the *Title* field.

3.  Add the required measures and dimensions in the left pane.

4.  The selected measures appear in the *Selected Measures* dropdown list. You can select the required measure from this list and plot the chart.

    > ### Note:  
    > You can add multiple measures with various dimensions for a single chart. If you add more than two measures, a table with measure details is displayed below the chart.

5.  To drill down on a particular dimension, click the corresponding bar on the plotted chart. If you apply a filter to a chart to drill down to the details, you can navigate back to any previous parameter by using the breadcrumb option.

6.  If you want to analyze using a particular value of measure or dimension in the plotted chart, choose the Filter icon at the top of the chart and set the required values in the Filter popup. You can enter values for measures manually using the Equals to, Greater than, or Less than options. For static dimensions \(default\), you can choose multiple values from the dropdown list. For custom dimensions \(created by you\), you can enter multiple values separated by commas.

7.  Choose *OK* and then save the chart.

8.  The chart appears in the *Custom View*.

    > ### Note:  
    > As you analyze your data, you may see an entity's value of \(n.a or not set\) displayed, including the parentheses, for your API Proxies, Product, Developer, and Developer Apps dimensions. This could be due to one of the following reasons:
    > 
    > -   Not all of your API proxies and developer applications are using products.
    > -   Some of your traffic is generated by unregistered developers and applications. This traffic may originate from an internal-use or public API.

9.  To remove a custom chart from custom view, select *Unpin from Custom View* option from the *Chart Settings* dropdown.

10. To add a custom chart, select *Change Analytic View* option from the *Chart Settings* dropdown.

11. To delete a custom chart, select *Delete* option from the *Chart Settings* dropdown.

12. To edit a custom chart, choose *Edit Chart* icon.

    > ### Note:  
    > While editing the charts, there's a possibility that the changes that you make to the order of the measures might not get preserved. In such cases, you can follow the steps given below to modify the measures in your charts:
    > 
    > 1.  Remove all the measures in the chart except for the one you want to view.
    > 2.  Save the chart.
    > 3.  Edit the chart again to add the next measure and save the changes. Repeat this step to add the other measures to the chart.

