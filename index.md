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

[Key Features](#key-features){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Personas]({{ site.baseurl }}{% link docs/personas/persona.md %}){: .btn .fs-5 .mb-4 .mb-md-0 }

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

[View details]({{ site.baseurl }}{% link docs/integrations.md %}){: .btn .btn-green }

### Releases

#### Version 1.24 
Stable 
{: .label .label-green }
New Release
{: .label .label-purple }

Features

1. Additional Security Configuration Checks 
    i. Fortinet
    ii. Juniper
    iii. Palo Alto
2. Generate Organization Reports
3. Transfer Assets across Business Units
4. Speed and Performance Improvements
5. Bug Fixes from older versions

#### Version 1.23 

Legacy 
{: .label .label-yellow }

Features

1. Additional Security Configuration Checks 
    i. Fortinet
    ii. Juniper
    iii. Palo Alto
2. Bug Fixes from older versions
3. Security Fixes



---

## Review

Review us on Gartner Peer Insights

<script type="text/javascript" src="https://www.gartner.com/reviews/public/Widget/js/widget.js"></script>
	<script type="text/javascript">
		GartnerPI_Widget({
			size: "small",
			theme: "dark",
			sourcingLink: "https://gtnr.io/2GB846TOz",
			widget_id: "YzkyYzU0ZTYtMWUxYS00NGY1LWE0MzctZWZiMTI1MDllNDdi",
			version: "2",
		container: document.querySelector("#Review”)
		})
	</script>

## Copyright
Firesec is &copy; 2018-{{ "now" | date: "%Y" }} by [Network Intelligence](https://www.niiconsulting.com).

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
