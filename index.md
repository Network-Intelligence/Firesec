---
layout: default
title: Home
nav_order: 1
description: "Firesec Documentation."
permalink: /
---

# Introduction to Firesec
{: .fs-9 }

Firesec™ is a Security Analysis and Orchestration platform. It is designed solve problems of these 4 personas - CISO, Security Consultant, Security Auditor and Network Administrator. It is an automated solution for security configuration analysis and compliance readiness. It supports a wide variety of firewalls and helps enhance the security of your network as well as significantly speed up compliance to standards such as PCI DSS, CI Security Benchmarks etc.,
{: .fs-6 .fw-300 }

[Key Features](#key-features){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Personas]({{ site.url }}{% link docs/personas/persona.md %}){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Key Features

- Automate the task of analysing security device configurations.
- Highlight non-compliances and insecure rules.
- Optimize the configurations to improve device security and performance.
- View and explore the network topography and determine insecure access paths and fix these problems using network visualization.
- Reduce the mean time taken to remediate the security issues, using the Change Management and Orchestration features

## Integrations

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

[View details]({{ site.baseurl }}{% link docs/Integrations/Integrations.md %}){: .btn .btn-green }

### Releases

#### Version 1.27 
Stable 
{: .label .label-green }
New Release
{: .label .label-purple }

Features
- [x] New Reporting Engine
- [x] System Diagnostics added to measure time taken for Parsing, Analysis & Reports

- [x] Export To Excel Functionality
  - Firewall Name or Organization Name is appended to the filename on download
  - Policy Name column added to selection of columns to Export to Excel

- [x] Reports
  - Mark Exception Icon in Excel Report
  - Additional columns added in Audit Schedule Detail section (Executive Summary) Excel Report
  - Additional columns added in Audit Schedule Detail section (Executive Summary) PDF Report

- [x] UI Improvements 
 - Compliance tab {Perf}
 - Firewall Objects Tab {Perf} 
 - View & Download Config {Perf}
 - Listing Business Unit Names grouped by Organization Name in Asset Page BU Selection Drop Down.
 - Reports Page refresh timer extended to 5 mins (earlier 10 secs)
 - Button Iconography
 - Mark Exception Icon in ViewConfigDetails Page 
 - Compliance Audit Page - additional columns added

- [x] Improvements and Fixes 
 - Core Parsing engine handles spaces, backslashes and double quotes encountered in Fortinet Config
 - Policy Filter Query
 - Report Filter Query
 - Organization Report Query

#### Version 1.26 

Legacy 
{: .label .label-yellow }

Features

1. Security Configuration Checks 
    i. Fortinet
    ii. Juniper
    iii. Palo Alto
2. Generate Organization Reports
3. Transfer Assets across Business Units
4. Bug Fixes from older versions

---

## Review

<div>Review us on [Gartner Peer Insights](https://www.gartner.com/peer-insights/home) Platform
<div class="GartnerPeerInsightsWidget">  </div>
</div>
<script type="text/javascript" src="https://www.gartner.com/reviews/public/Widget/js/widget.js"></script>
<script type="text/javascript">
  const gpiContainerDiv = document.querySelector('.GartnerPeerInsightsWidget');
		GartnerPI_Widget({
			size: "small",
			theme: "dark",
			sourcingLink: "https://gtnr.io/2GB846TOz",
			widget_id: "YzkyYzU0ZTYtMWUxYS00NGY1LWE0MzctZWZiMTI1MDllNDdi",
			version: "2",
		container: gpiContainerDiv
		});
	</script>

## Copyright
Firesec is &copy; 2018-{{ "now" | date: "%Y" }} by [Network Intelligence](https://www.niiconsulting.com). All Rights Reserved.
* * *
 The Software and any accompanying documentation are copyrighted and protected by copyright laws and international copyright treaties, as well as other intellectual property laws and treaties.

<button class="btn js-toggle-dark-mode">Switch to dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>
