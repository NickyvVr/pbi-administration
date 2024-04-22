This folder contains the Power BI template file to start the extract of your tenant settings.
* It currently uses a Bearer token to authenticate, which can be obtained for example from the Power BI Rest API website:
[Admin - WidelySharedArtifacts LinksSharedToWholeOrganization](https://learn.microsoft.com/en-us/rest/api/power-bi/admin/widely-shared-artifacts-links-shared-to-whole-organization#code-try-0)

With this template you can easily extract your Power BI tenant settings.
You need to login with a Power BI Administrator account at one of the Power BI or Fabric Admin REST API's (ex. https://learn.microsoft.com/en-us/rest/api/power-bi/admin/groups-get-groups-as-admin?tryIt=true&source=docs#code-try-0) and obtain the **Bearer token**. You don't need to run the API call itself. Logging in is enough to obtain the token.
https://learn.microsoft.com/en-us/rest/api/fabric/admin/tenants/get-tenant-settings?tabs=HTTP#code-try-0

![image](https://github.com/NickyvVr/pbi-administration/assets/16239272/f7f71edf-db76-481e-a6c3-0125edfea987)

Once you have that token you can copy and paste it in the Bearer parameter and click Load.

Current ideas to further enhance this template:
* Use authentication to login to the API automatically with the user logged in to PBID
* Load MS default values for tenant settings
* Load best practice values for tenant settings
* Show difference with default MS/best practice values
* Add links to more info on MS Learn

Created by Nicky van Vroenhoven
www.nickyvv.com
