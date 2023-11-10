Author: Amreek Singh- Senior Solution Architect- FastTRack for Dynamics

//Import the querypack (Kusto Queries)
1. Log in to your Azure Portal
2. Search for "Deploy a custom template"
3. Select "Build your own template in the editor"
4. Copy the contents of QueryPackTemplate\template.json and paste in the editor
5. press Save
6. Choose the subscription id,resourcegroup,region and the querypack name (or you can use the default name)
7. Click on "Review and Create"

or  [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSinghAmreek%2FPowerAutomateTelemetry%2Fmain%2FQueryPackTemplate%2Ftemplate.json)
Follow steps #6 and #7 above.

//Import the Dashboard
1. Log in to your Azure Portal
2. Search for "Deploy a custom template"
3. Select "Build your own template in the editor"
4. Copy the contents of Dashboardtemplate\dashboard.json and paste in the editor
5. press Save
6. Choose the subscription id,resourcegroup,region, resourcegroup(textbox) and the appinsightInstance name(textbox)
7. Click on "Review and Create"
or  [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSinghAmreek%2FPowerAutomateTelemetry%2Fmain%2FDashboardTemplate%2Fdashboard.json)
Follow steps #6 and #7 above.
