# Azure Sentinel SIEM with Live Honeypot

This project involved setting up Azure Sentinel, a scalable, cloud-native, security information event management (SIEM) and security orchestration automated response (SOAR) solution. I connected Azure Sentinel to a live virtual machine that acted as a honeypot, which enabled me to observe real-time attacks from around the globe.

<h1> Project Outline: </h1>

<img src="https://i.imgur.com/RNjbBTD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Azure Sentinel Setup: </h2>  I began by setting up Azure Sentinel, configuring it to collect security data from all users, devices, applications, and infrastructure in the cloud.

<img src="https://i.imgur.com/CQRCzBQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Honeypot Configuration: </h2> 

I then established a live virtual machine to act as a honeypot. This decoy system was intended to lure cyber attackers, allowing me to study their activities without endangering my actual infrastructure.

<img src="https://i.imgur.com/QUFiP25.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Observing Live Attacks: </h2>

With the honeypot in place, I can monitor real-time attacks. In this project, I focused on Remote Desktop Protocol (RDP) brute force attacks, a common method used by attackers attempting to gain unauthorized access to systems.

<h2> Geolocation Lookup with PowerShell: </h2> 

To gain more insights about the attackers, I used a custom PowerShell script. This script fetched the geolocation information of the attackers, providing me with details about their approximate physical location.

<img src="https://i.imgur.com/BTC3EV4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Visualizing Attack Data: </h2> 

Finally, I plotted the attackers' geolocation data on the Azure Sentinel Map. This visualization allowed me to see the global distribution of the attacks, which offered a more tangible understanding of the threats I faced.

<img src="https://i.imgur.com/efUQcJd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Please note that this project was intended for educational and research purposes. Always ensure you're in compliance with all relevant laws and regulations when setting up and using a honeypot.

<h2> Getting Started: </h2>
To get started with this project, you'll need an Azure account with permissions to set up Azure Sentinel and a virtual machine. Familiarity with PowerShell scripting is also beneficial for customizing and running the geolocation lookup script.
