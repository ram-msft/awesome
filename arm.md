# AZURE RESOURCE MANAGER ( ARM )

All the goodness I've found on Azure Resource Manager and templates.  

## KEY VAULT ( AKV )

* ARM template reference for keyvault <https://docs.microsoft.com/en-us/azure/templates/microsoft.keyvault/vaults>
* Keyvault - Add access policy <https://github.com/Azure/azure-quickstart-templates/tree/master/101-keyvault-add-access-policy>
* Keyvault - Create a keyvault - <https://github.com/Azure/azure-quickstart-templates/tree/master/101-key-vault-create>
* Keyvault QuickStart Templates - Create with logging, create,with per, create vault with secrets passed, create api managememt with hostname as proxy, keyvault access policy <https://azure.microsoft.com/en-us/resources/templates/?resourceType=Microsoft.Keyvault>

## LEARN

* Azure Citadel <https://azurecitadel.com/automation/>
* What's new with ARM Templates (Nov 2019) - https://www.youtube.com/watch?v=3D-JIKShrws

## TEMPLATE COLLECTIONS

* Master template reference on Az Docs <https://docs.microsoft.com/en-us/azure/templates/>
* Non-profits center for Azure - arm templates and contoso store  plus ppts <https://github.com/Microsoft/Nonprofits>
* Quickstart templates for ARM <https://azure.microsoft.com/en-us/resources/templates/>
* Quickstart templates for ARM github <https://github.com/singhkays/azure-quickstart-templates>

## TOOLS 

* ARMClient Command Tool <http://blog.davidebbo.com/2015/01/azure-resource-manager-client.html>
* Deployment Manager - deploy arm templates across regions - https://docs.microsoft.com/en-us/azure/azure-resource-manager/deployment-manager-overview
* Template tester - https://github.com/Azure/azure-quickstart-templates/tree/master/test/arm-ttk
* Template validator <https://github.com/singhkays/azure-arm-validator>
* Visualizer for ARM - https://github.com/shenglol/arm-visualizer 

## TOOLS - ARM CLIENT SAMPLES

<dt>Az Subs - List</dt><dd>armclient GET /subscriptions?api-version=2018-11-01</dd>
<dt>Az Advisory Alerts to WebHook</dt><dd>https://docs.microsoft.com/en-us/azure/advisor/advisor-alerts</dd>
<dt>Logic Apps parameter inspection</dt><dd>armclient get https://management.azure.com/$subid/providers/Microsoft.Logic/workflows?api-version=2017-07-01</dd>
<dt>Microsoft.Web/connectors parameter inspection</dt><dd>armclient get https://management.azure.com/$subid/providers/Microsoft.Web/locations/centralus/managedApis/gmail?api-version=2018-07-01-preview<br/>
armclient get https://management.azure.com/$subid/providers/Microsoft.Web/locations/centralus/managedApis/smtp?api-version=2018-07-01-preview<br/>
armclient get https://management.azure.com/$subid/providers/Microsoft.Web/locations/centralus/managedApis/office365?api-version=2018-07-01-preview
</dd>
<dt>Resource Groups - List</dt><dd>armclient GET /subscriptions/{subid}/resourceGroups?api-version=2018-05-01</dd>
<dt>Websites in an RG - List</dt><dd>armclient GET $subid/resourceGroups/madison/providers/Microsoft.Web/sites?api-version=2018-11-01</dd>
</dl>

## MISC

* ARM errors on deploy - https://github.com/projectkudu/kudu/wiki/Investigating-msdeploy-ARM-failures
* Callback URL for Logic App in ARM <https://stackoverflow.com/questions/47012601/getting-callback-url-for-logic-app-in-arm>
* Visualize ARM Templates in VS Code - https://marketplace.visualstudio.com/items?itemName=bencoleman.armview
