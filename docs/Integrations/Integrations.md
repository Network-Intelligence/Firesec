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

<details><summary>Version 1.35</summary>
<div markdown="1">
### Firesec version v 1.35 supported devices 
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
