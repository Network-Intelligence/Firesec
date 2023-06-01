---
layout: default
title: CheckPoint
nav_order: 1
parent: Integrations
has_children: false
has_toc: false
---


## CheckPoint 
Technology Alliance Partner
{: .label .label-yellow }

## Support Firmware Versions

<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions|Automatic (API)|Automatic (SSH)|Manual (Config File)|
|---|---|---|---|---|---|---|
|Firewall|CheckPoint|GAIA|R81|✅|❌|❌|
|Firewall|CheckPoint|GAIA|R80.40|✅|❌|❌|
|Firewall|CheckPoint|GAIA|R80.30|✅|❌|❌|
|Firewall|CheckPoint|GAIA|R80.20|✅|❌|❌|

</div>


## Check Point Pre-requisites

### CREATE AN ADMINISTRATOR IN SMARTCONSOLE

1. Log in to the SmartConsole
2. Go to Manage & Settings > Permissions & Administrators
3. Add New
4. Enter the desired username and password
5. Select the authentication method as "Check Point Password"
6. Click OK
7. Publish the SmartConsole Session.

### ENABLE THE MANAGEMENT API (REST API)

1. Login to the SmartConsole.
2. From SmartDashboard, Select Manage & Settings> Blades > Management API
3. Set "Accept API calls from" to "All IP addresses"
4. Next Publish
5. Run the api restart command on the security management server.
6. Restart the API using the command
> api restart
  * Please note restarting the API is an essential step after making the above changes to the accessibility setting of the REST API.

![CheckPoint Management API](../../../../assets/images/CheckPoint%20Management%20API.png)

7. Verify the status of the API using the command 
> api status

> Note the Accessibility Setting (it will display Require all granted)

8. Validate the connectivity with Postman 

> https://mgmt-server:port/web_api/login 

> * Replace mgmt-server:port with actual values as per your environment and pass the user credentials as parameters in the POST Request.


<!-- 


## Enable CheckPoint Management API

1.	Login to the SmartConsole.
2.	From SmartDashboard, Select Manage & Settings> Blades > Management API
3.	Set "Accept API calls from" to "All IP addresses" 
4.	Next Publish 
5.	Run the api restart command on the security management server. 

![CheckPoint Management API](../../../../assets/images/CheckPoint%20Management%20API.png)

> Please note restarting the API is an essential step after making changes to the accessibility setting of the API.

To verify if the API is enabled and ready to serve requests 
Execute
> api status 

The Accessibility now displays "Require all granted"

1.	Download and Install [Postman](https://www.postman.com/downloads/) on Firesec server
2.	Execute POST request on URL (https://[mgmt-server]:[port]/web_api/login)with username and password as parameters. Replace the [mgmt-server]:[port] with actual IP & port values, as per your environment.
3.	If you get a valid response (200) from the executed call, then API access is available from the server. -->


### References 

[How to](https://scribehow.com/page/Check_Point_Pre-requisites__ZQfYMSJbRIOZQ09ArxtqIg)

Please refer to this link [Check Point - Management API reference](https://sc1.checkpoint.com/documents/latest/APIs/#introduction~v1.9) for more details 
