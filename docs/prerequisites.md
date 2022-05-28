---
layout: default
title: Prerequisites
nav_order: 6
---

# [](#header-1) Pre-requisites for Firesec Deployment

## System Requirements

|Component    |Recommended    | Notes  |
|---|---|---|
| OS  |Windows Server 2016 or above  | with Local Admin privileges on this machine  |
| Core   |12   |   |
| RAM   | 16 GB  |   |
| Storage   | 500 GB   |   |
| Web Server  | Internet Information Services (IIS) 10  |with URL Rewrite Module   |
| DB Server  |SQL SERVER 2016 or above| with SSMS  |

## Additional Requirements
 
-	Local Administrator privileges[^1] are required in order to deploy Firesec on the Server.
-	Hosting Firesec Web App on HTTPS[^2] requires port 443 or a custom port to be opened on that server and firewall. For hosting on HTTP, port 80 or a custom port needs to be opened.
-	.Net Framework 4.8, SQL Server and Management Studio, latest version of browsers[^3], Postman, Putty to be pre-installed on the server.[^4]
- Network Access from deployment Server to respective Network Devices (Firewalls) must be enabled/allowed.
- An Admin user[^5] to be created in respective Network Devices (Firewalls).
- HTTP/2 disabled on Server and browsers (Chrome / Edge / Firefox).
- Remote access to the server for deployment.
- REST API access is required for getting necessary configuration details from the Firewalls.[^6]

[^1]: One Windows user with administrator privileges to install/configure and access IIS, Database and Windows Services.
[^2]:	For https, a self-signed certificate from the customer is required. This can be generated from PowerShell / IIS.
[^3]: Latest version of browsers (Chrome / Edge / Firefox). Postman for testing REST API Request & Responses and putty access for testing via CLI.
[^4]: Customer to complete the installation of these tools prior to Firesec Deployment.
[^5]: A REST API* & CLI Admin user with appropriate user permissions to execute show … type of commands
[^6]: Fortinet, CheckPoint, PaloAlto, Juniper, Cisco Firepower, SonicWall, Sophos etc.

### Note
```
Users accessing the database with type of rights defined for each users
- IIS APPPPOOL\DefaultAppPool  (dbo)
- NT AUTHORITY\SYSTEM (default/system defined)
- NT AUTHORITY\LOCAL SERVICE (default/system defined)
```
* * *
