---
title: Adding panels
description: Dynamic report allows you to add panel to better filter your data depending on the chosen time period.
page-status-flag: never-activated
uuid: 8e76e837-5efc-4250-8192-dee1a0bd62fe
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: reporting
content-type: reference
topic-tags: customizing-reports
discoiquuid: f4e1e676-5ca2-4a58-96d7-d378ff803710

internal: n
snippet: y
---

# Adding panels{#adding-panels}

## Adding a blank panel {#adding-a-blank-panel}

To start your report, you can add a set of panels to an out of the box or custom report. Each panel contains different data sets and is composed of freeform tables and visualizations.

This panel allows you to build your reports as needed. You can add as many panels as you want in your reports in order to filter your data with different time periods.

1. Click the **Panels** icon. You can also add a panel by clicking the **Insert tab** and selecting **New Blank Panel**. 

   ![](assets/dynamic_report_panel_1.png)

1. Drag and drop the **Blank Panel** into your dashboard. 

   ![](assets/dynamic_report_panel.png)

You can now add a freeform table to your panel to start targeting data.

## Adding a freeform table {#adding-a-freeform-table}

Freeform tables allow you to create a table to analyze your data using the different metrics and dimensions available in the **Component** table.

Each table and visualization is resizable and can be moved to better customize your report.

1. Click the **Panels** icon.

   ![](assets/dynamic_report_panel_1.png)

1. Drag and drop the **Freeform** item into your dashboard.

   You can also add a table by clicking the **Insert** tab and selecting **New Freeform** or by clicking **Add a freeform table** in an empty panel. 

   ![](assets/dynamic_report_panel_2.png)

1. Starting Campaign 19.4 release, the **[!UICONTROL Exclude proof]** will already be selected by default. If needed, you can change it by drag and dropping one of the **[!UICONTROL Segments]** from the **[!UICONTROL Components]** tab into the top bar.

   ![](assets/dynamic_report_panel_3.png)

1. Drag and drop items from the **Components** tab into the columns and rows to build your table.

   ![](assets/dynamic_report_freeform_3.png)

1. Click the **Settings** icon to change how the data is displayed in your columns.

   ![](assets/dynamic_report_freeform_4.png)

   The **[!UICONTROL Column settings]** is composed of:

    * **[!UICONTROL Number]**: lets you show or hide summary numbers in the column.
    * **[!UICONTROL Percent]**: lets you show or hide percent in the column.
    * **[!UICONTROL Interpret zero as no value]**: lets you show or hide when value equals zero.
    * **[!UICONTROL Background]**: lets you show or hide the horizontal progress bar in cells.
    * **[!UICONTROL Include retries]**: lets you include retries in the result. This is only available for **[!UICONTROL Sent]** and **[!UICONTROL Bounces + Errors]**.

1. Select one or multiple rows and click the **Visualize** icon. A visualization is added to reflect the rows you have selected.

   ![](assets/dynamic_report_freeform_5.png)

You can now add as many components as you need and also add visualizations to give graphical representations of your data.
