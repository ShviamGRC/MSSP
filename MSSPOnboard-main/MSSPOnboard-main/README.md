# Onboard Microsoft Sentinel Onesec MSSP

| Onesec Group         | Role | Delete the registration assignment assigned to their tenant (*) | Create and run Playbooks | Create automation Rules to run Playbooks | Can run Playbook Manually | Create and edit workbooks, analytic rules and other Azure Sentinel Resources | Manage incidents (dismiss, assign etc) | View data, incidents, dashboards and other Azure Sentinel resources |
|----------------------|------|----------------------------------------------------------------|--------------------------|------------------------------------------|--------------------------|--------------------------------------------------------------------|-------------------------------------|------------------------------------------------------------|
| MDR&nbsp;T1&nbsp;-&nbsp;Analyst     | Microsoft&nbsp;Sentinel&nbsp;Reader + Microsoft&nbsp;Sentinel&nbsp;Playbook&nbsp;Operator | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | | | | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; |
| MDR&nbsp;T2&nbsp;-&nbsp;Analyst     | Microsoft&nbsp;Sentinel&nbsp;Responder + Microsoft&nbsp;Sentinel&nbsp;Automation&nbsp;Contributor | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; |
| MDR&nbsp;T3&nbsp;-&nbsp;Threat Hunter | Microsoft&nbsp;Sentinel&nbsp;Contributor + Logic&nbsp;App&nbsp;Contributor | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;X&emsp;&emsp;&emsp; |




|Deployment Type | Button |
|----------------|--------|
| Subscription   | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520Subscription%2FdelegatedResourceManagement.json) |
| Resource Group | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsorcia25%2FMSSPOnboard%2Fmain%2FOnboard%2520a%2520Resource%2520Group%2FrgDelegatedResourceManagement.json) |
