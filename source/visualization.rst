Visualization
=====================

Data Visualizer App
-------------------
The DHIS2 Data Visualizer App is designed to help users create visualizations and reports based on the health data stored in the DHIS2 database.

Key features and functions of the Data Visualizer App:
------------------------------------------------------

* Data Selection: Users can select specific data elements, indicators, and dimensions from the DHIS2 database to create visualizations.
* Visualization Types: The app supports various types of visualizations, including charts (e.g., bar charts, line charts, pie charts), maps, and tables.
* Customization: Users can customize the appearance and layout of their visualizations, such as choosing colors, labels, and legends.
* Data Filters: The app allows users to apply filters to the data, enabling them to focus on specific time periods, geographical regions, or other criteria.
* Interactivity: Some visualizations created with the Data Visualizer App can be interactive, allowing users to hover over data points for more information or drill down into the data.
* Export and Sharing: Users can export their visualizations as images or PDFs, making it easy to share the results with colleagues or stakeholders.
Dashboard Integration: Visualizations created with the Data Visualizer App can be integrated into DHIS2 dashboards, providing a centralized view of key health indicators and data trends.


Creating and editing visualizations
----------------------------------

#. Select Visualization Type: Depending on your data and analysis goals, choose the appropriate visualization type. Common types include bar charts, line charts, pie charts, maps, and tables. Different types may have specific requirements and options.
 
#. Select Data Elements and Indicators: Start by selecting the data elements or indicators you want to visualize. These are the data points you want to analyze. You can usually browse and search for them within the Data Visualizer App.
#. Choose Dimensions: Dimensions are additional variables that you can use to slice and dice your data. They Include
   * Data: Includes data elements, indicators and datasets (reporting rates), describing the phenomena or event of the data.
   * Periods: Describes when the event took place.
   * Organisation units: Describes where the event took place.

 

#. Configure Visualization: Customize your visualization by specifying options such as labels, legends, and other settings. These options may vary depending on the selected visualization type.
 
#. Apply Filters (Optional): Apply filters to narrow down your data. Filters allow you to focus on specific time periods, geographical areas, or other criteria. This step is optional but can be useful for more targeted analysis.
#. Preview and Save: Preview your visualization to ensure it accurately represents your data. If everything looks good, save your visualization. You may be prompted to give it a title and description.
#. Share and Publish: Depending on your permissions, you may be able to share your visualization with other users or publish it to a dashboard for wider visibility.

  Levels of access when sharing visualizations
    * View and Edit: Can view and edit the visualization.
    * View only: Can only view the visualization.
 
#. Export or Download: If you need to share your visualization as an image or PDF, many DHIS2 instances offer export options.
 

Dashboards
-----------------

#. Create a New Dashboard
Click on the "Create New" or "Add Dashboard" button to create a new dashboard.
Provide a name and description for your dashboard. This information helps users understand the purpose of the dashboard. (Description is optional)

 
#. Add Layout and Structure
Dashboards typically consist of one or more layout elements, such as rows and columns, where you can arrange visualizations and reports. Start by adding these layout elements to your dashboard.

   Layout Options
 
 In a Freeflow layout, you have the flexibility to rearrange added items by clicking and dragging them with your mouse to your preferred positions. Additionally, you can adjust the size of items by clicking on the drag handle located in the lower right corner of the item and then dragging it to your desired dimensions.

 If you opt for a Fixed Columns layout, you can specify the number of columns you wish to include in your dashboard. The dashboard will automatically organize the items for you within these columns. However, in this layout, manual repositioning and resizing of items aren't possible since their placements are determined by the fixed column structure you've chosen.

 

#. Add Visualizations and Reports
Within each layout element, you can add visualizations and reports. Click on the "Add Item" select the type of content you want to add (e.g., charts, maps, tables).
Choose the specific visualizations or reports you want to include in that section. You can select from existing visualizations you've created or create new ones.

#. Configure Visualization Settings
Customize each visualization's settings, including colors, labels, legends, and any other specific options relevant to the type of visualization you're using.

#. Apply Filters (Optional)
By default, users can filter dashboard items using any dimension that has been defined within the DHIS2 instance. However, you can customize these dashboard filter settings by clicking on the "Filter Settings" option for a specific dashboard.

 
To specify which filters should be available, you can choose the "Only allow filtering by selected dimensions" option. From there, you can handpick the filters(grant) you want to make accessible on the dashboard. Period and Organization Unit are automatically included by default, but you have the flexibility to remove them if you prefer. 

#. Save the Dashboard
Once you've added and configured all the visualizations and reports, save your dashboard to store it for future use.

#. Share and Assign Permissions
Determine who can access the dashboard and at what level of access (view, edit, or share). Assign permissions to users or user groups accordingly.

