---
layout: default
title: Fortinet
nav_order: 3
parent: Integrations
has_children: false
has_toc: false
---

## Fortinet
Technology Alliance Partner
{: .label .label-yellow }

## Support Firmware Versions
<div markdown="1">

|Technology|Vendor|Product / OS|Firmware Versions|Automatic (API)|Automatic (SSH)|Manual (Config File)|
|---|---|---|---|---|---|---|
|Firewall|Fortinet|FortiGate|v7.x|✅|✅|✅|
|Firewall|Fortinet|FortiGate|v6.x|✅|✅|✅|
|Firewall|Fortinet|FortiGate|v5.x|✅|✅|✅|

</div>

## Pre-requisites

Read only Super Admin User

- Click on System 
- Click on Administrators
- Click on Create New
- Fill all the fields like name, password and then attach the profile “super reader”.

> If not available profile is not available, create one and grant READ permissions. 

![Fortigate User](../../../../assets/images/fortinetSuperAdmin.png)

# Creating Administrator Users on FortiGate
#### [Made by Rishit Shah with Scribe](https://scribehow.com/shared/Creating_Administrator_Users_on_FortiGate__kcxDeASMRuCpLvWG-xoh5g)
Creating Administrator Users on FortiGate - Local administrator and REST API administrator

#### Creating a Local Administrator on FortiGate

**1. Navigate to the web UI of FortiGate **

**2. Enter Credentials to login to the web UI of Fortigate**

**3. From the menu on the left, Click "System"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/adf6e251-43e6-4c33-afce-0e698c92cfee/user_cropped_screenshot.jpeg?tl_px=0,361&br_px=746,781&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=36,154)

**4. Next click on "Administrators".**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/9b75d045-4202-4256-87ab-80fb50764516/ascreenshot.jpeg?tl_px=0,47&br_px=746,467&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=45,139)

**5. Create a new Administrator User**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/62eec5d8-b767-4e42-afe0-9e9c9044e791/ascreenshot.jpeg?tl_px=0,0&br_px=746,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=249,28)

**6. Click "Administrator"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/df092085-62e5-4950-a7e5-3cdac3b83804/ascreenshot.jpeg?tl_px=0,0&br_px=746,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=234,51)

**7. Enter a desired user name in the "Username" field and enter Passwords**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/b474ae77-5863-49f4-8f74-a758de2ac8f9/ascreenshot.jpeg?tl_px=187,0&br_px=933,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,61)

**8. Enter appropriate comments in the "Comments" field.**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/d1b3c652-5f25-43ff-bf2a-49190ab8f1b0/ascreenshot.jpeg?tl_px=198,281&br_px=944,701&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,139)

**9. Select the administrator profile from the drop down.**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/278f9752-e65c-4726-bb25-953e65226fa2/ascreenshot.jpeg?tl_px=263,308&br_px=1009,728&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,139)

**10. Select "super_admin_readonly"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/d64b6e29-ad45-40f2-9687-755e69ecc7a6/ascreenshot.jpeg?tl_px=193,361&br_px=939,781&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,196)

**11. Valid date the details and click on OK.**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/f3a9ea41-32f4-4021-90a9-d989fbe752a4/ascreenshot.jpeg?tl_px=302,355&br_px=1048,775&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,139)

**12. Click "OK"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/43827d64-d7a8-419c-afda-48823a18e301/user_cropped_screenshot.jpeg?tl_px=156,284&br_px=902,704&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,281)

#### Creating a REST API Administrator User

**13. Click on "Create New"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/0a8a4f45-319b-4bad-96ed-a4261e8d9937/ascreenshot.jpeg?tl_px=0,0&br_px=746,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=252,31)

**14. Select "REST API Admin".**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/848686b2-01c3-4f22-834e-71ede27ef783/ascreenshot.jpeg?tl_px=0,0&br_px=746,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=229,73)

**15. Enter the username and comments**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/96955764-f7d0-4504-a88d-e7f5b2069879/ascreenshot.jpeg?tl_px=95,0&br_px=841,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,69)

**16. Select the administrator profile "super_admin_readonly".**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/34437372-e5d2-49fe-88b2-ba4e1a92172c/ascreenshot.jpeg?tl_px=99,32&br_px=845,452&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,139)

**17. Disable or Uncheck the PKI Group**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/7c548961-adda-4154-a569-62a89aa06dad/ascreenshot.jpeg?tl_px=24,0&br_px=770,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,129)

**18. Click "OK"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/724ad05a-92c9-4bda-8f42-e8a830c247e0/ascreenshot.jpeg?tl_px=385,176&br_px=1131,596&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,139)

**19. Copy the API Key**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/37c98ec6-c2a9-4b05-8eeb-0fb4fd4ad9dc/ascreenshot.jpeg?tl_px=403,0&br_px=1149,420&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,61)

**Alert: The API Key is displayed only once, therefore kindly ensure to securely copy the API Key and save it securely.**

**20. Click "Close"**

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-05-30/2e72d845-ed49-4d96-a8d0-ce19177a139d/ascreenshot.jpeg?tl_px=477,361&br_px=1223,781&sharp=0.8&width=560&wat_scale=50&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-labs-public.s3.us-east-2.amazonaws.com/images/watermarks/watermark_default.png&wat_pad=262,278)
#### [Made with Scribe](https://scribehow.com/shared/Creating_Administrator_Users_on_FortiGate__kcxDeASMRuCpLvWG-xoh5g)





## Step by Step How To

[How To](https://scribehow.com/shared/Creating_Administrator_Users_on_FortiGate__kcxDeASMRuCpLvWG-xoh5g) 

## References 

[FortiGate Local Administrator](https://docs.fortinet.com/document/fortigate/7.4.0/administration-guide/562247/local-authentication)

[FortiGate REST API Administrator](https://docs.fortinet.com/document/fortigate/7.4.0/administration-guide/399023/rest-api-administrator)
