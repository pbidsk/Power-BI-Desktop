# Microsoft Power BI Desktop

* [Installation](#installation)
* [Connecting to Data Sources](#connecting-to-data-sources)
* [Data Modelling and Relationships](#data-modelling-and-relationships)
* [Creating Visualizations](#creating-visualizations)
* [Time Intelligence and Measures](#time-intelligence-and-measures)
* [Sharing Reports and Finalizing Projects](#sharing-reports-and-finalizing-projects)

## **Installation**

Once the installation finishes, go ahead and launch the application. The welcome screen will present you with a choice: begin a fresh new report or connect to a data source you've used before.

Power BI is Microsoft’s premier self-service platform for business intelligence (BI). With Power BI you can:

* Effortlessly connect to a wide array of data sources
* Shape, transform, and prepare the data for analysis
* Build interactive dashboards and detailed, paginated reports
* Safely share your findings through the cloud

The complete Power BI ecosystem is made up of several components:

* Power BI Desktop
* Power BI Service (the online version you access through a browser)
* Power BI Mobile apps for iOS and Android
* Power BI Gateway (which enables connections to on-premises data)

## Connecting to Data Sources

You begin a project by pulling in data from sources like Excel spreadsheets, CSV files, SQL databases, or even web-based APIs.

Here’s how to do it:

* Click on **Get Data** within Power BI Desktop
* Pick your source type (for instance, Excel or CSV)
* You can choose to load the data immediately or select **Transform Data** to launch the Power Query Editor

Inside the Power Query Editor, you have the power to:

* Clean and optimize your data tables
* Modify and assign the correct data types
* Rename, rearrange, or remove entire columns
* Bring queries together using merge or append operations

Having data that is properly structured and refined is a critical step before you proceed to the modelling phase.

## Data Modelling and Relationships

Once your data is prepared, the next step is to define how your different tables connect to each other.

Key points to remember:

* Relationships are typically one-to-many or many-to-one
* These links can be automatically detected or manually established by you
* You have full control over the cross-filter direction and the relationship's cardinality

To set up relationships in the **Model view**:

* Navigate to **Manage Relationships**
* Designate the source and target tables along with their corresponding matching columns
* Confirm that the relationship is set to active

A well-built model ensures that your filters and visualizations will work exactly as intended.

## Creating Visualizations

Visualizations are what turn your prepared datasets into clear, understandable insights.

Some of the most commonly used chart types are:

* Bar and column charts
* Pie or donut charts
* Tables and matrix visualizations
* Line graphs and geographical maps
* Slicers and other interactive filtering tools

To create a visual:

* Pick a visualization type from the templates
* Drag the relevant fields to the axes, values, or filters areas
* Organize and arrange all the elements on your report canvas

By default, visuals in Power BI are interconnected—selecting an element in one chart will automatically filter and influence the others through **visual interactions**.

## Time Intelligence and Measures

Incorporate sophisticated, time-based analysis into your dashboards.

The process involves:

* Making sure your date field is assigned the `Date` data type
* Officially designating your date table using **Modeling > Mark as Date Table**

You can generate time intelligence metrics easily with **Quick Measures**:

* Examples include: Year-to-date totals, Month-over-month growth, and comparisons to previous periods
* Find this option under **Home > Quick Measure**
* Select the base measure (e.g., SalesAmount) and associate it with your date column

Power BI will automatically write the necessary DAX (Data Analysis Expressions) formulas in the background for these standard time calculations.

## Sharing Reports and Finalizing Projects

When your report is ready, use the Power BI Service to publish and distribute it.

Here is the typical process:

* Save your project as a `.pbix` file
* Click the **Publish** button to send it to your Power BI online workspace
* Organize your reports into dedicated workspaces and dashboards
* Grant access to colleagues or other stakeholders

Additional capabilities you can use include:

* Setting up scheduled automatic data refreshes
* Designing live, updating dashboards
* Viewing and interacting with reports on mobile devices from anywhere
