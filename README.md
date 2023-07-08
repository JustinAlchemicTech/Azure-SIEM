# Azure Sentinel SIEM with Live Honeypot

This project involved setting up Azure Sentinel, a scalable, cloud-native, security information event management (SIEM) and security orchestration automated response (SOAR) solution. I connected Azure Sentinel to a live virtual machine that acted as a honeypot, which enabled me to observe real-time attacks from around the globe.

Project Outline
Azure Sentinel Setup: I began by setting up Azure Sentinel, configuring it to collect security data from all users, devices, applications, and infrastructure, both on-premises and in multiple clouds.

Honeypot Configuration: I then established a live virtual machine to act as a honeypot. This decoy system was intended to lure cyber attackers, allowing me to study their activities without endangering my actual infrastructure.

Observing Live Attacks: With the honeypot in place, I can monitor real-time attacks. In this project, I focused on Remote Desktop Protocol (RDP) brute force attacks, a common method used by attackers attempting to gain unauthorized access to systems.

Geolocation Lookup with PowerShell: To gain more insights about the attackers, I used a custom PowerShell script. This script fetched the geolocation information of the attackers, providing me with details about their approximate physical location.

Visualizing Attack Data: Finally, I plotted the attackers' geolocation data on the Azure Sentinel Map. This visualization allowed me to see the global distribution of the attacks, which offered a more tangible understanding of the threats I faced.

Please note that this project was intended for educational and research purposes. Always ensure you're in compliance with all relevant laws and regulations when setting up and using a honeypot.

Getting Started
To get started with this project, you'll need an Azure account with permissions to set up Azure Sentinel and a virtual machine. Familiarity with PowerShell scripting is also beneficial for customizing and running the geolocation lookup script.
