## TFS-Companion-Reports
Team Foundation Server (TFS) Companion Reports, a sister integrated project for the TFS Companion Database, provides sample custom reports to augments -- and perhaps improve on -- the reporting package that comes with hosted TFS solutions.  These SQL Server Reporting Services (SSRS) reports are easily customizable and do not interact directly with your TFS server -- so no performance hits to worry about.

## Pre-requisites
These reports use data from the [TFS Companion Database](https://github.com/madcalfus/TFS-Companion-Database), so you'll need to install it first; then, update the "TfsCompanionDB.rds" data source to point to it.

## Development Tools
I'm developing with these tools.  All have community (free) editions.  These can also be used to do the deployment.
- Visual Studio 2015 with Update 3 - <a href="https://www.visualstudio.com/downloads/">Download</a>
- SQL Server 2016 Developer Edition - <a href="https://www.microsoft.com/en-us/cloud-platform/sql-server-editions-developers">Download</a>
- SQL Server Data Tools (SSDT) for Visual Studio 2015 - <a href="https://msdn.microsoft.com/en-us/library/mt204009.aspx">Download</a>

See [Wiki](https://github.com/madcalfus/TFS-Companion-Reports/wiki) for samples