# Step 1 : Create a workspace

1. In the Microsoft Fabric portal, click on the Power BI experience at the bottom left of the window.

![Microsoft Fabric Portal Home](images/fabric_portal_home.png)

2. Navigate to Workspaces using the left navigation menu and click on New workspace.

![Navigating to Workspaces in Fabric](images/create_workspace.png)

3. Insert a name for the workspace, you can choose any name you like. You can leave the other cells empty. Then click on Advanced.

![Create a workspace](images/create_workspace_tab.png)

4. Then choose your Fabric license. You can, for example, use your trial capacity or a Fabric capacity you've created on Azure. Leave the other settings as default, then click Apply.

![Workspace advanced settings](images/create_workspace_advanced_tab.png)

5. The workspace will then be created and automatically displayed on your screen. Check that you have an empty workspace as shown in the image below.

![Created workspace](images/empty_workspace.png)

# Step 2 : Create a KQL database

A KQL database refers to a database system suited for ingesting streaming data, making it particularly useful for scenarios that require real-time data analysis. Its columnar storage and efficient compression facilitate fast querying over large datasets.

In this demonstration, we will set up a KQL database tailored to ingest streaming data, showcasing its capabilities in real-time data processing

1. In the workspace you've just created, click on the New button and then on More options.

![Workspace more options](images/workspace_more_options.png)

2. Scroll down to the Real-Time Analytics section, and click on the KQL Database button to create a KQL database.

![Real Time Analytics Options](images/real_time_analytics_options.png)

3. Insert the name NycTaxiDB for the database name, leave the type set to New Database (default) and click Create.

![Choose KQL database name](images/new_kql_database.png)

4. You'll then land on this page. By default, KQL database tables are unavailable in OneLake. We can change this by clicking on the pencil in the OneLake availability line.

![Change OneLake availability](images/onelake_availability.png)

5. Toggle the button to Active and select Done.

![Change OneLake availability](images/data_availability_onelake.png)