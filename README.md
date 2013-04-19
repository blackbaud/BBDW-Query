BBDW-Query
=====================

BBDW-Query contains a number of query views that enable users to build ad-hoc queries in Blackbaud CRM using the Blackbaud Data Warehouse as the data source.

## Requirements: ##

- Blackbaud CRM 3.0 or higher is installed
- The Blackbaud Data Warehouse has been deployed and refreshed


## Resources ##

[Blackbaud Developer Network](http://www.bbdevnetwork.com/)

[Blackbaud Data Warehouse Documentation](https://www.blackbaud.com/files/support/guides/infinitydevguide/infsdk-developer-help.htm#../Subsystems/bbdw-developer-help/content/welcomebbdwsdk.htm)

[Blackbaud Infinity Query Documentation](https://www.blackbaud.com/files/support/guides/infinitydevguide/infsdk-developer-help.htm#../Subsystems/infquery-developer-help/Content/InfinityQuery/WelcomeInfinityQuery.htm%3FTocPath%3DQuery%7C_____0)

## Deployment Instructions ##
1. Compile Blackbaud.OpenFx.BBDW.Query.Catalog.dll using Visual Studio 2010 or higher
1. Copy Blackbaud.OpenFx.BBDW.Query.Catalog.dll to the ...\vroot\bin\Custom folder on all web servers
1. Load the BBDW Query Package through Catalog Browser
1. The Constituent Reporting source view should now be available when creating a new query


## License ##

Published under Apache Software License 2.0, see LICENSE