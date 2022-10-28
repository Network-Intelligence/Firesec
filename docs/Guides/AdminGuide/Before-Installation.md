---
layout: default
title: Admin Guide
nav_order: 2
parent: Guides
has_children: false
has_toc: false
---

## Internet Information Services

Step 1: [Steps for Installing IIS and ASP.NET Modules](https://learn.microsoft.com/en-us/iis/application-frameworks/scenario-build-an-aspnet-website-on-iis/configuring-step-1-install-iis-and-asp-net-modules)

Step 2:

### To add an ASP.NET application by using the UI
Open IIS Manager.

For Windows Server 2012, on the Start page click the Server Manager tile, and then click OK. In Server Manager, click the Tools menu, and then click Internet Information Services (IIS) Manager.
For Windows 8, on the Start page type Control Panel, and then click the Control Panel icon in the search results. On the Control Panel screen, click System and Security, click Administrative Tools, and then click Internet Information Services (IIS) Manager.
In the Connections pane, expand the Sites node.

Right-click the site for which you want to create an application, and click Add Application.

In the Alias text box, type a value for the application URL, such as *firesec*. This value is used to access the application in a URL.

Click Select if you want to select a different application pool than the one listed in the Application pool box. In the Select Application Pool dialog box, select an application pool from the Application pool list and then click OK.

In the Physical path text box, type the physical path of the application's folder, or click the browse button (...) to navigate the file system to find the folder.

Optionally, click Connect as to specify credentials that have permission to access the physical path. If you do not use specific credentials, select the Application user (pass-through authentication) option on the Connect As dialog box.

Optionally, click Test Settings to verify the settings that you specified for the application.

Click OK.

### To add an ASP.NET application by using the command line
To add an application to a site, use the following syntax:

> appcmd add app /site.name:string /path:string /physicalPath:string

The variable site.name:string is the name of the website to which you want to add the application. The variable path:string is the virtual path of the application, such as /application, and physicalPath:string is the physical path of the application content in the file system.

For example, to add an application to a site named firesec, with content at c:\inetpub\wwwroot\firesec, type the following at the command prompt, and then press ENTER:

> appcmd add app /site.name:firesec /path:/firesec /physicalPath:c:\inetpub\wwwroot\firesec.


## IIS Rewrite Module 2 

### Installing the module
Download the URL Rewrite 2.0 by using the links at the module's home page at [https://www.iis.net/extensions/urlrewrite](https://www.iis.net/extensions/urlrewrite)

> Note

>> If a previous version of URL Rewrite, such as v1.0 and v1.1, is already installed then it will be upgraded to the v2.0
>> If an RC version of the URL Rewrite 2.0 is already installed, then it will be upgraded to RTW version.