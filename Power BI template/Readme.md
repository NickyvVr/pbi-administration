This folder contains the Power BI template file to start the extract of your tenant settings.
* It currently uses a Bearer token to authenticate, which can be obtained for example from the Power BI Rest API website:
[Admin - WidelySharedArtifacts LinksSharedToWholeOrganization](https://learn.microsoft.com/en-us/rest/api/power-bi/admin/widely-shared-artifacts-links-shared-to-whole-organization#code-try-0)

Current ideas to further enhance this template:
* Use authentication to login to the API automatically with the user logged in to PBID
* Load MS default values for tenant settings
* Load best practice values for tenant settings
* Show difference with default MS/best practice values
* Add links to more info on MS Learn
