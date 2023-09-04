---
layout: default
title: Integrations
nav_order: 4
has_children: true
has_toc: false
---

# Integrations
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

<!-- # Integrations
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc} -->

---

Firesec provides flexible ways to integrate with various network devices. Analysis can be carried out in two modes 

> **Online (Automatic)** - Firesec connects directly with the network device either using CLI or API.[^1] 
Further, allow customers to setup a scheduled analysis.

> **Offline (Manual)** - Firesec takes the configuration file of the network device to carry out the analysis[^2]

[^1]: Requires Administrator user credentials to access CLI or API to execute show commands
[^2]: Analysis limited to the data available in the configuration

## Supported Devices

#### Firesec integration with **Network Devices** 

- ✅ [CheckPoint]({{ site.url }}{% link docs/Integrations/Network Devices/CheckPoint.md %})
- ✅ [Cisco]({{ site.url }}{% link docs/Integrations/Network Devices/Cisco.md %}) 
- ✅ [Fortinet]({{ site.url }}{% link docs/Integrations/Network Devices/Fortinet.md %})
- ✅ [Juniper]({{ site.url }}{% link docs/Integrations/Network Devices/Juniper.md %})
- ✅ [Palo Alto]({{ site.url }}{% link docs/Integrations/Network Devices/PaloAlto.md %})
- ✅ [SonicWall]({{ site.url }}{% link docs/Integrations/Network Devices/Sonicwall.md %})
- ✅ [Sophos XG | UTM]({{ site.url }}{% link docs/Integrations/Network Devices/Sophos.md %}) (includes erstwhile Cyberoam devices too)

- ✅ [AWS Security Groups]({{ site.url }}{% link docs/Integrations/Network Devices/AWS.md %})
- ✅ [Azure Network Security Groups]({{ site.url }}{% link docs/Integrations/Network Devices/Azure.md %})

#### Firesec integration with **Change Management Solutions** 

- ✅ [ServiceNow]({{ site.url }}{% link docs/Integrations/Change Management/ServiceNow.md %}) 
- ✅ [Fresh Service]({{ site.url }}{% link docs/Integrations/Change Management/FreshService.md %}) 
- ✅ [Service Desk Plus]({{ site.url }}{% link docs/Integrations/Change Management/ServiceDeskPlus.md %}) 

#### Firesec integration with **Vulnerability Management Solutions**

- ✅ [Rapid 7 Nexpose]({{ site.url }}{% link docs/Integrations/Vulnerability Management/Rapid7.md %})
- ✅ [Nessus]({{ site.url }}{% link docs/Integrations/Vulnerability Management/Nessus.md %})

#### Firesec integration with **Identity Management Solutions**

- ✅ [CyberArk]({{ site.url }}{% link docs/Integrations/Identity Management/CyberArk.md %})


| Legend |
| --- | --- |
| Supported | ✅ |
| Not Supported | ❌ |
| Not Applicable | 🚫 | 
| Beta | ꞵ |

<details><summary>Version 1.38</summary>
<div markdown="1">
### Firesec version v 1.38 supported devices 
Stable 
{: .label .label-green }
New Release
{: .label .label-purple }

<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions| Manual (Config File)|Automatic (SSH)|Automatic (API)|
|---|---|---|---|---|---|---|
| Firewall|Cisco|ASA|v9.x|✅|✅|🚫|
| Firewall|Cisco|ASA|v8.x|✅|✅|🚫|
| Router|Cisco|IOS|v15.x|✅|✅|🚫|
| Router|Cisco|IOS|v12.x|✅|✅|🚫|
| Switch|Cisco|IOS|v15.x|✅|✅|🚫|
| Firewall|CheckPoint|GAIA|R81|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R80.20|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R80.10|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R77.30|✅|🚫|🚫|
|Firewall|Cyberoam||10.6.3|✅|❌|🚫|
|Firewall|Fortinet|FortiGate|v7.x|✅|✅|✅|
|Firewall|Fortinet|FortiGate|v6.x|✅|✅|✅|
|Firewall|Fortinet|FortiGate|v5.x|✅|✅|✅|
|Firewall|Juniper|vSRX|v20.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v19.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v18.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v17.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v10.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v9.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v8.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v7.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v6.x|✅|❌|✅|
|Firewall|Sonicwall|SonicOS|6.5.0.2|✅|✅|❌|
|Firewall|Sonicwall|SonicOS|6.5.4.4|✅|✅|❌|
|Firewall|Sophos|Sophos XG|v1701|✅|❌|✅|
|Firewall|Sophos|Sophos UTM|v9.x|❌|❌|✅|
|Cloud|AWS|NSG|3|🚫|🚫|✅|
|Cloud|Azure|NSG|3|🚫|🚫|✅|
|Firewall|Cisco|Firepower|v6.4|🚫|🚫|ꞵ|
|Management Console|Cisco|FMC|v7.2|🚫|🚫|ꞵ|
|Management Console|CheckPoint|SmartConsole|R81.10|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R81|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.40|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.30|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.20|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.10|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80|🚫|🚫|✅|
|Management Console|Palo Alto|Panorama|v10.0|🚫|🚫|✅|
|Vulnerability Manager|Rapid7|InsightVM||🚫|🚫|ꞵ|
|Vulnerability Manager|Tenable|Nessus||🚫|🚫|ꞵ|
|Identity Manager|CyberArk|PVWA|11.7|🚫|🚫|ꞵ|

</div>

</div>
</details>

***

##
# Step-by-Step Guide to integrate a Firewall in Firesec
#### [Made by Rishit Shah with Scribe](https://scribehow.com/shared/Step-by-Step_Guide_to_integrate_a_Firewall_in_Firesec__vm1DzK2oQlaT2VG_SNehNg)
This step-by-step guide provides clear instructions on how to integrate a firewall in Firesec. It includes detailed steps on how to navigate the Firesec platform, add new assets, configure device settings, parse firewall configurations, analyze security and optimization, filter and export data, run compliance audits, and generate reports. Following this guide will help users effectively manage and secure their firewall configurations using Firesec.

1. Navigate to Firesec Web URL  https://analyzer.firesec.io/Account/Login.aspx 

Please note this url could be different in your environment. 


2. Enter the username and Password to Login

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/be45fc63-c3ef-4b55-a9e9-2f3abcebf66a/ascreenshot.jpeg?tl_px=248,48&br_px=1108,529&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


3. A successful login, lands the user on to the Dashboard

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/e5918bb7-101b-4dfc-881c-18336c8e006e/screenshot.png?tl_px=1,0&br_px=1378,750&force_format=png&width=1120.0)


4. From the menu on the right, click "Assets"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/992dff23-5ea4-4517-b450-a37a13e0950d/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1376,750&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=6,179)


5. Select the Business Unit from the dropdown

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/a76a1a21-677b-4175-b64e-0aaf51b9ede3/ascreenshot.jpeg?tl_px=327,53&br_px=1187,534&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


6. Click "Add New"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/8c62534a-a32d-4b4e-913d-1be8a1ce1144/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=314,154)


7. Enter the basic Asset details - Asset Name, Criticality, Tag, Location as desired and click Next

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/b866c2db-6ebb-407b-adfe-365cde331731/ascreenshot.jpeg?tl_px=524,0&br_px=1384,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,186)


8. Click "Next"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d5b57248-185e-4c48-b46f-bea7d764b031/ascreenshot.jpeg?tl_px=525,204&br_px=1385,685&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=749,212)


9. Select the analysis type -  Security, Optimization  and then click on Next

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/f62af21f-d610-457d-9010-2f0161a7cb8c/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=602,177)


10. Enter the details as required on the form - Asset Type, Vendor, Fetch Mechanism

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c0a8f44f-78db-4819-9bbb-6ea1ae85ee45/ascreenshot.jpeg?tl_px=525,0&br_px=1385,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=442,172)


11. Enter the credentials required to connect with the Device

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/a002c5f8-420c-4774-9c84-f94b716d079d/ascreenshot.jpeg?tl_px=525,41&br_px=1385,522&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=770,212)


Tip: Tip! Please note the forms are dynamic and may change based on the Asset Type and Vendor selected. 

Please ensure you are aware of the ports on which this device can be connected using SSH or REST API or Both (depending on the type and vendor)


12. Click the "SSH Port" field.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/61f850c7-3697-4d32-9dbd-bab9a1783864/ascreenshot.jpeg?tl_px=517,106&br_px=1377,587&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


13. Click the "Expert Password" field.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/e5c1513a-8904-4731-8d19-b68043d6aa21/ascreenshot.jpeg?tl_px=497,145&br_px=1357,626&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


14. Click "Next"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/269bcf78-15ac-495b-a68f-1075eb74bbcc/ascreenshot.jpeg?tl_px=525,231&br_px=1385,712&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=760,212)


15. Recurrence determines how frequently Firesec will connect with the device to pull the configuration information. If you are unsure, please select "OnDemand". This will trigger an immediate one time analysis.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d1a52498-8ad2-4175-98e8-b04598879be7/ascreenshot.jpeg?tl_px=525,0&br_px=1385,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=468,162)


16. Click "Next"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/38875a95-4e01-4a11-a2dc-d1e9f30063d8/user_cropped_screenshot.jpeg?tl_px=238,0&br_px=1385,557&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=1001,428)


Tip: Tip! Recurrence can help with Automatic Scheduling on Analysis. The Recommendation is to set this to 90 days. 


17. Wait for the platform to load the list of Devices **


18. Select the desired Devices from the list and click "Finish"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/ff8fa192-8756-44bd-b597-24f799dbe031/ascreenshot.jpeg?tl_px=238,140&br_px=1385,781&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=1003,289)


19. Assets are added Successfully

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d6cde307-5242-4679-b2c8-ce137657322b/ascreenshot.jpeg?tl_px=269,0&br_px=1129,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,12)


20. Click on the Bell Icon to see the notifications

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d8cb7904-2f1f-4961-a188-abb72d3f14d7/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=294,18)


21. Click "Notifications

1. Start Parsing for firewall 'VSX-GW1' configuration
2. Start Parsing for firewall 'Virt_Sys' configuration
3. Start Parsing for..."

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/50b20549-6835-4ab3-861a-cc8e4343624e/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=325,4)


22. Click on the Asset Name "CheckPointR81-Demo_SMS"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/2b7fd584-4ca9-4ccb-bd98-ea9c5e4e411e/ascreenshot.jpeg?tl_px=32,77&br_px=892,558&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


23. Click "PrimarygwR81"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/08cdadda-df0c-47d7-9457-87e7cf2d140b/ascreenshot.jpeg?tl_px=9,130&br_px=869,611&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


24. Click on the Hostname "PrimarygwR81" to drill down into the detailed view of the asset

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/7500341d-8b78-473b-8139-0e8bf4457ee2/ascreenshot.jpeg?tl_px=57,105&br_px=917,586&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


25. Click "RULE BASE"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/a035f67e-c6cf-4123-955a-55a611e5eb35/ascreenshot.jpeg?tl_px=114,0&br_px=973,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,86)


26. Select the desire number of rows to be displayed

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/b0ca6ad5-af9c-47ca-96af-27359532752b/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=304,137)


27. Scroll to the right to see additional information about the rule

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/946b5dee-0ee5-47ca-8f45-c308b16b1f63/ascreenshot.jpeg?tl_px=8,11&br_px=1385,781&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=717,529)


28. Click "FiresecWeb" to see contextual information about the object (IP Address, Where it is used etc)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d689df6e-5a5a-4267-8b8f-4f4d88e646dc/ascreenshot.jpeg?tl_px=525,300&br_px=1385,781&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=404,317)


29. Click "Close"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/dfbd739d-9d69-48f0-926f-9bd064d46ea4/ascreenshot.jpeg?tl_px=8,11&br_px=1385,781&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=717,330)


30. On any column, use the filter option to filter and sort the data

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/6ac52f62-b44c-4795-bf44-10383ee1a2af/ascreenshot.jpeg?tl_px=525,209&br_px=1385,690&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=602,212)


31. Filter options 

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/817eb949-2afc-41bf-aefe-9f974e4c7233/ascreenshot.jpeg?tl_px=14,0&br_px=874,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,148)


32. Click "Apply"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/3a2cc671-5f1f-4a65-9899-94a197fada52/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=565,155)


33. Click "Clear Filter" to remove all filters applied on the data table

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/786b4924-da3d-4d35-a5ff-329430d2525f/ascreenshot.jpeg?tl_px=525,75&br_px=1385,556&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=564,212)


34. Select Rules by clicking on the CheckBox 

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/5dd55757-6202-4527-b84b-aee2cf3ec2cf/ascreenshot.jpeg?tl_px=0,224&br_px=859,705&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=299,212)


35. Click "Export"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/047155b6-6869-4c5e-94a8-8c8f820870be/ascreenshot.jpeg?tl_px=510,68&br_px=1370,549&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


36. Select the columns to export

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/f7341b0d-fcbd-4b37-a219-576d8f3683e1/ascreenshot.jpeg?tl_px=0,8&br_px=1146,649&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=498,277)


37. Click "Export"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/0b1b6e97-2444-4b8d-b043-eda69f5cc7bd/ascreenshot.jpeg?tl_px=8,11&br_px=1385,781&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=734,281)


38. Click "SECURITY ANALYSIS"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d77ef37a-d1ad-49d0-9d87-069e971e7a00/ascreenshot.jpeg?tl_px=227,0&br_px=1087,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,80)


39. Click "Any Source"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c690dc56-c4a5-4353-8a8d-bfbbfb7dadc0/ascreenshot.jpeg?tl_px=36,9&br_px=895,490&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


40. Click "Any Destination"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/f686fbca-371f-4bd6-9c6b-c6b59374d3b4/ascreenshot.jpeg?tl_px=120,11&br_px=979,492&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


41. Click "Any Service"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/84926c92-f106-4728-83de-a5800bb4c63f/ascreenshot.jpeg?tl_px=211,11&br_px=1071,492&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


42. Click "Any Source Destination"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/1f7e15b5-bf81-4452-be0f-f862c7327113/ascreenshot.jpeg?tl_px=362,12&br_px=1222,493&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


43. Click "Any Source Service"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/0c948255-0646-46e4-a82c-d883321c98f9/ascreenshot.jpeg?tl_px=459,12&br_px=1319,493&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


44. Click "Any Destination Service"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/dd8dd5c0-0eb5-4c86-91b9-7af37bbe9542/ascreenshot.jpeg?tl_px=525,4&br_px=1385,485&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=498,212)


45. Click "Logging Disabled"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/b252bd99-c9df-403f-b572-28be2878dc83/ascreenshot.jpeg?tl_px=525,15&br_px=1385,496&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=630,212)


46. Click "Drop Rules Logging Disabled"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/bead307d-14d8-462a-a50d-ada59f18bc9a/ascreenshot.jpeg?tl_px=0,45&br_px=859,526&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=345,212)


47. Click "More Ports Access"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/f96c0635-cc7e-4a67-b5ff-28f838e39051/ascreenshot.jpeg?tl_px=101,46&br_px=961,527&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


48. Click "Inactive"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c94c0f0c-221c-4a4e-bd5c-0cd770a8e153/ascreenshot.jpeg?tl_px=201,49&br_px=1061,530&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


49. Click "Risky Ports"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/2a4e819d-e07e-4dbc-8f25-643f6197fda0/ascreenshot.jpeg?tl_px=260,41&br_px=1120,522&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


50. Click "Risky Ports Clear Text Protocols"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/232d3511-a173-4de8-b13d-c727603785b5/ascreenshot.jpeg?tl_px=406,47&br_px=1266,528&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


51. Click "Symmetric Rule"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/862a9e8a-a9e9-4671-bedb-c4605ec5fc0e/ascreenshot.jpeg?tl_px=525,49&br_px=1385,530&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=433,212)


52. Click "Too Many IPs in Destination"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/77e5f720-1c36-409e-a1ee-e892a141de24/ascreenshot.jpeg?tl_px=525,45&br_px=1385,526&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=543,212)


53. Click "Drop Rules Positioning"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/fe9b935f-927a-4bb9-b3da-d23d18cebb31/ascreenshot.jpeg?tl_px=0,77&br_px=859,558&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=375,212)


54. Click "OPTIMIZATION"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/017a70a2-7975-4280-a6a6-d3615f611c5a/ascreenshot.jpeg?tl_px=313,0&br_px=1173,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,98)


55. Click "Duplicate Objects"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/23f052d4-18c4-4c51-ac79-15130c7057d6/ascreenshot.jpeg?tl_px=125,0&br_px=984,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,167)


56. Click "Host Group"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/9d3c0db3-fae4-4414-ab54-7b22de9fb047/ascreenshot.jpeg?tl_px=0,7&br_px=859,488&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=353,212)


57. Click "Service"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/57d7d4fd-5ad7-4a11-b1d9-79e12c2d35af/ascreenshot.jpeg?tl_px=31,7&br_px=890,488&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


58. Click "Service Group"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/d3fcaaea-e599-4a45-94a3-65ef0a634f63/ascreenshot.jpeg?tl_px=101,7&br_px=961,488&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


59. Click "Interface"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/bfc2a610-8a32-4207-8063-da7a63ba31c5/ascreenshot.jpeg?tl_px=186,7&br_px=1046,488&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


60. Click "Empty Objects"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/6c6f96b3-b231-4edf-a022-103c82ca2e02/ascreenshot.jpeg?tl_px=279,0&br_px=1139,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,151)


61. Click "Empty Host Groups"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/73e58a0e-a5e9-4e27-8237-030358f7b6e5/ascreenshot.jpeg?tl_px=26,3&br_px=885,484&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


62. Click "Empty Services"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/1dc7d2ce-12aa-45b1-b3c0-7ae8ab0d6973/ascreenshot.jpeg?tl_px=163,1&br_px=1022,482&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


63. Click "Empty Service Groups"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/46abf787-12f7-40fe-9e0f-c85046cabfd1/ascreenshot.jpeg?tl_px=259,1&br_px=1119,482&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


64. Click "Empty Interfaces"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/7018e58f-026f-4bce-8c2c-dca9b9fa6e43/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=533,201)


65. Click "Grouping"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/0afa230f-3572-4753-954c-c7597867adbd/ascreenshot.jpeg?tl_px=370,0&br_px=1230,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,157)


66. Click "Source Grouping"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/da978b53-0ebd-4b93-93e0-a4ecfa11e290/ascreenshot.jpeg?tl_px=33,27&br_px=892,508&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


67. Click "Destination Grouping"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/0e794a43-61b9-42e8-b47e-c6541fb13b0a/ascreenshot.jpeg?tl_px=178,22&br_px=1038,503&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


68. Click "Empty Comments"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/e4eaeb23-991f-46c9-a361-770edcbfc9e5/ascreenshot.jpeg?tl_px=392,0&br_px=1375,549&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=459,171)


69. Click "FIREWALL OBJECTS"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/78085098-acb2-4bbd-a787-3e907d7af4bd/ascreenshot.jpeg?tl_px=0,0&br_px=1376,769&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=336,65)


70. Click "Hosts"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c95e594a-9464-4a0b-b9c7-00ce8c0d783c/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=394,175)


71. Click "Firewall Users"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/7b165a88-953c-4888-ab08-4b0d49d56dbd/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=343,175)


72. Click "Hosts"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/f2a63b91-8e0c-479d-b788-576fef7360c6/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=401,174)


73. Click "Host Groups"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/9953cb52-6fa5-4986-8ae0-50f6606c68ab/ascreenshot.jpeg?tl_px=67,0&br_px=926,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,173)


74. Click "Services"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/221ad3be-1afb-4a94-a7c4-7bfdbdd5b409/ascreenshot.jpeg?tl_px=176,0&br_px=1036,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,173)


75. Click "Service Groups"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/7453661b-1d9f-422b-81e4-9eb6f0efa58a/ascreenshot.jpeg?tl_px=287,0&br_px=1147,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,176)


76. Click "Virtual IP"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/1bdeb99d-7d3f-4c2c-a4b9-cd3ef0172ee5/ascreenshot.jpeg?tl_px=237,0&br_px=1384,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=524,165)


77. Click "Interfaces"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/585cca03-4610-4716-a5f0-a6caeb680033/ascreenshot.jpeg?tl_px=459,0&br_px=1319,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,178)


78. Click "COMPLIANCE"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/3373d2e4-296b-4877-910b-670bb473015e/ascreenshot.jpeg?tl_px=0,0&br_px=859,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=304,96)


79. On the Compliance Tab, choose the audit policy against which you would like to run the Audit.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c5c6aaa0-1111-47ee-a331-41c3a664454b/ascreenshot.jpeg?tl_px=9,0&br_px=869,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,160)


80. Click "Audit"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/4a82a35a-acb0-4e7e-b7d7-d4ef356cd968/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=570,150)


81. Click "Export" to export the Audit Results into a CSV file

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/51cb4fff-74e9-4bd2-9ed6-3f1040b69d97/ascreenshot.jpeg?tl_px=525,18&br_px=1385,499&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=726,212)


82. Select the columns or Click "Select All"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/6347470b-3c20-4efd-ab27-8a0f365c9ea0/ascreenshot.jpeg?tl_px=0,9&br_px=1146,650&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=494,277)


83. Click "Export"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/93f4b7ad-f5d5-478d-8986-06cd953529ce/ascreenshot.jpeg?tl_px=8,8&br_px=1385,777&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=720,276)


84. From the menu on the right, click "Reports"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/db0e3ce9-3f54-4e73-9e20-e42903fcc05d/ascreenshot.jpeg?tl_px=0,134&br_px=859,615&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=45,212)


85. Check the asset you'd like to generate the report

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/03a4b332-485a-4bbd-a917-be899b68b7c5/ascreenshot.jpeg?tl_px=0,222&br_px=859,703&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=259,212)


86. Click "Generate Report"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/c187b215-f676-4b8e-8a3f-c283ead6f43b/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=972,159)


87. Click the "Report Title" field.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/9dba1172-38f9-4852-b735-7a321c371e8f/ascreenshot.jpeg?tl_px=392,0&br_px=1252,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,169)


88. Click "Next"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/db5fd8a9-df78-41f8-99ed-4187e05f5532/ascreenshot.jpeg?tl_px=402,166&br_px=1385,715&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=868,243)


89. Select the desired sections to include in the report

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/bd1d7b75-db12-42c5-8d25-8b34dcd310f8/ascreenshot.jpeg?tl_px=418,0&br_px=1278,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,188)


90. Click "Basic Checklist"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/300b999f-62a1-4216-abb8-7d27d9d218fb/ascreenshot.jpeg?tl_px=367,74&br_px=1227,555&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


91. Click "Review Summary"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/4873e922-87b2-45cf-9ddb-be52b26150df/ascreenshot.jpeg?tl_px=373,90&br_px=1233,571&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


92. Click "Firewall Users"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/2e589f45-9164-41a1-bcec-24605fe6725d/ascreenshot.jpeg?tl_px=381,45&br_px=1241,526&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=402,212)


93. Click "Generate Audit Report"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/02b77aef-4e91-4580-8de4-65f9c011c94d/ascreenshot.jpeg?tl_px=525,300&br_px=1385,781&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=697,344)


94. Click "EXPORT"


95. Click "CLOSE"


96. Click "1. Report Title"


97. Click the "Pdf" field.


98. Click "Next"


99. Click here.


100. Click the "Report Title" field.


101. Type " [[delete]]"


102. Click "Report Title
 
Report Format
Pdf
Excel
Report Type
Executive
Detailed"


103. Click "Next"


104. Click "Generate Audit Report"


105. Click "EXPORT"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-25/84324ec5-51f1-47dd-993b-bb3a57823a0c/ascreenshot.jpeg?tl_px=238,0&br_px=1385,640&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/8B5CF6_standard.png&wat_pad=958,80)


>> Alert!
 The report generation process may take up to 50 mins depending on the size of the firewall ruleset, objects. Please be patient.

#### [Made with Scribe](https://scribehow.com/shared/Step-by-Step_Guide_to_integrate_a_Firewall_in_Firesec__vm1DzK2oQlaT2VG_SNehNg)


