# Create AzureFirewall sandbox setup

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsfiguemsft%2Fnetworkinglab%2Fmaster%2Fvnet1%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsfiguemsft%2Fnetworkinglab%2Fmaster%2Fvnet1%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template creates a virtual network with 2 subnets (server subnet, and AzureFirewall subnet).
Azure Firewall is a managed cloud-based network security service that protects your Azure Virtual Network resources.
It is a fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability.
You can centrally create, enforce, and log application and network connectivity policies across subscriptions and virtual network.
Azure Firewall uses a static public IP address for your virtual network resources allowing outside firewalls to identify traffic originating from your virtual network.
The service is fully integrated with Azure Monitor for logging and analytics. Learn more at https://docs.microsoft.com/en-us/azure/firewall.
