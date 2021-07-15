---
layout: default
title: Integrations
nav_order: 4
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

Online (Automatic) - Firesec connects directly with the network device either using CLI or API.[^1] 
Further, allow customers to setup a scheduled analysis.

Offline (Manual) - Firesec takes the configuration file of the network device to carry out the analysis[^2]

[^1]: Requires Administrator user credentials to access CLI or API to execute show commands
[^2]: Analysis limited to the data available in the configuration

## Supported Devices

#### Firesec integration with **Network Devices** 

- [x] CheckPoint
- [x] Cisco
- [x] Fortinet
- [x] Juniper
- [x] Palo Alto
- [x] SonicWall
- [x] Sophos (includes erstwhile Cyberoam devices too)

- [x] AWS Security Groups
- [x] Azure Network Security Groups

#### Firesec integration with **Change Management Solutions** 

- [x] ServiceNow
- [x] Fresh Service 
- [x] Service Desk Plus

#### Firesec integration with **Vulnerability Management Solutions**

- [x] Rapid 7 Nexpose
- [x] Nessus

| Legend |
| --- | --- |
| Supported | ✅ |
| Not Supported | ❌ |
| Not Applicable | 🚫 | 
| Beta | ꞵ |

<details><summary>Version 1.19</summary>
<div markdown="1">
### Firesec version v 1.19 supported devices 
Stable 
{: .label .label-green }
New Release
{: .label .label-purple }

<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions| Manual (Config File)|Automatic (SSH)|Automatic (API)|
|---|---|---|---|---|---|---|
| Firewall|Cisco|ASA|v8.x|✅|✅|🚫|
| Firewall|Cisco|ASA|v9.x|✅|✅|🚫|
| Router|Cisco|IOS|v12.x|✅|✅|🚫|
| Router|Cisco|IOS|v15.x|✅|✅|🚫|
| Switch|Cisco|IOS|v12.x|✅|✅|🚫|
| Firewall|CheckPoint|GAIA|R77.30|✅|🚫|🚫|
| Firewall|CheckPoint|GAIA|R80.10|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R80.20|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R81|🚫|🚫|✅|
|Firewall|Cyberoam||10.6.3|✅|❌|🚫|
|Firewall|Fortinet|FortiGate|v4.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v5.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v6.x|✅|✅|✅|
|Firewall|Juniper|vSRX|v12.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v14.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v19.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v20.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v6.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v7.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v8.x|✅|❌|✅|
|Firewall|Sonicwall|SonicOS|6.5.0.2|✅|✅|❌|
|Firewall|Sonicwall|SonicOS|6.5.4.4|✅|✅|❌|
|Firewall|Sophos|SophOS|v1701|✅|❌|✅|
|Cloud|AWS|NSG|3|🚫|🚫|✅|
|Cloud|Azure|NSG|3|🚫|🚫|✅|
|Firewall|Cisco|Firepower|v6.4|🚫|🚫|ꞵ|
|Management Console|Cisco|FMC|v6.4|🚫|🚫|ꞵ|
|Management Console|CheckPoint|SmartConsole|R80.10|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.20|🚫|🚫|✅|
|Vulnerability Manager|Rapid7|InsightVM||🚫|🚫|ꞵ|
|Vulnerability Manager|Tenable|Nessus||🚫|🚫|ꞵ|

</div>

</div>
</details>

<details><summary>Version 1.18</summary>
<div markdown="1">
### Firesec version v 1.18 supported devices

<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions| Manual (Config File)|Automatic (SSH)|Automatic (API)|
|---|---|---|---|---|---|---|
| Firewall|Cisco|ASA|v8.x|✅|✅|🚫|
| Firewall|Cisco|ASA|v9.x|✅|✅|🚫|
| Router|Cisco|IOS|v12.x|✅|✅|🚫|
| Router|Cisco|IOS|v15.x|✅|✅|🚫|
| Switch|Cisco|IOS|v12.x|✅|✅|🚫|
| Firewall|CheckPoint|GAIA|R77.30|✅|🚫|🚫|
| Firewall|CheckPoint|GAIA|R80.10|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R80.20|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R81|🚫|🚫|✅|
|Firewall|Cyberoam||10.6.3|✅|❌|🚫|
|Firewall|Fortinet|FortiGate|v4.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v5.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v6.x|✅|✅|✅|
|Firewall|Juniper|vSRX|v12.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v14.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v19.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v20.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v6.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v7.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v8.x|✅|❌|✅|
|Firewall|Sonicwall|SonicOS|6.5.0.2|✅|✅|❌|
|Firewall|Sonicwall|SonicOS|6.5.4.4|✅|✅|❌|
|Firewall|Sophos|SophOS|v1701|✅|❌|✅|
|Cloud|AWS|NSG|3|🚫|🚫|✅|
|Cloud|Azure|NSG|3|🚫|🚫|✅|
|Firewall|Cisco|Firepower|v6.4|🚫|🚫|ꞵ|
|Management Console|Cisco|FMC|v6.4|🚫|🚫|ꞵ|
|Management Console|CheckPoint|SmartConsole|R80.10|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.20|🚫|🚫|✅|
|Vulnerability Manager|Rapid7|InsightVM||🚫|🚫|ꞵ|

</div>

</div>
</details>


<details><summary>Version 1.17</summary>
<div markdown="1">
### Firesec version v 1.17 supported devices

<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions| Manual (Config File)|Automatic (SSH)|Automatic (API)|
|---|---|---|---|---|---|---|
| Firewall|Cisco|ASA|v8.x|✅|✅|🚫|
| Firewall|Cisco|ASA|v9.x|✅|✅|🚫|
| Router|Cisco|IOS|v12.x|✅|✅|🚫|
| Router|Cisco|IOS|v15.x|✅|✅|🚫|
| Switch|Cisco|IOS|v12.x|✅|✅|🚫|
| Firewall|CheckPoint|GAIA|R77.30|✅|🚫|🚫|
| Firewall|CheckPoint|GAIA|R80.10|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R80.20|🚫|🚫|✅|
| Firewall|CheckPoint|GAIA|R81|🚫|🚫|✅|
|Firewall|Cyberoam||10.6.3|✅|❌|🚫|
|Firewall|Fortinet|FortiGate|v4.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v5.x|✅|✅|🚫|
|Firewall|Fortinet|FortiGate|v6.x|✅|✅|✅|
|Firewall|Juniper|vSRX|v12.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v14.x|✅|❌|❌|
|Firewall|Juniper|vSRX|v19.x|✅|❌|✅|
|Firewall|Juniper|vSRX|v20.x|✅|❌|✅|
|Firewall|Palo Alto|PanOS|v6.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v7.x|✅|❌|❌|
|Firewall|Palo Alto|PanOS|v8.x|✅|❌|✅|
|Firewall|Sonicwall|SonicOS|6.5.0.2|✅|✅|❌|
|Firewall|Sonicwall|SonicOS|6.5.4.4|✅|✅|❌|
|Firewall|Sophos|SophOS|v1701|✅|❌|✅|
|Cloud|AWS|NSG|3|🚫|🚫|✅|
|Cloud|Azure|NSG|3|🚫|🚫|✅|
|Firewall|Cisco|Firepower|v6.4|🚫|🚫|ꞵ|
|Management Console|Cisco|FMC|v6.4|🚫|🚫|ꞵ|
|Management Console|CheckPoint|SmartConsole|R80.10|🚫|🚫|✅|
|Management Console|CheckPoint|SmartConsole|R80.20|🚫|🚫|✅|

</div>

</div>
</details>

***