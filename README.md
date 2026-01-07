# Microsoft-Sentinel-Home-Lab
## Objective

- Deployed a vulnerable Windows VM in Azure
- Disabled the firewall and deliberately exposed the VM to the internet to act as a honeypot
- Simulated attacks by attempting multiple failed RDP logins with incorrect usernames and passwords
- Verified the activity locally in Event Viewer, identifying Event ID 4625 (failed logon attempts)

### Skills Learned
[Bullet Points - Remove this afterwards]

- Practical experience with cloud-based SIEM deployment
- Understanding how raw logs become actionable security insights
- Hands-on exposure to KQL, threat hunting, and visual analytics
- Seeing how quickly exposed systems attract real-world attacks
  
### Tools Used

- Microsoft Sentinel
- Windows Security Events
- SIEM & Log Management
- Log Analytics Workspace
- SecurityEvent logs in Sentinel
- Windows Event Viewer
- Virtual Machines

## Steps
<img src="https://i.postimg.cc/PJ6463dz/Whats-App-Image-2025-12-30-at-4-34-39-PM.jpg" height="80%" width="80%" alt="Virtual network"/>
<img src="https://i.postimg.cc/MTqmz2TV/Whats_App_Image_2025_12_30_at_4_34_42_PM.jpg" height="80%" width="80%" alt="Microsoft Windows Desktop"/>
<img src="https://i.postimg.cc/Zngfb7Xq/Whats_App_Image_2025_12_30_at_4_36_12_PM.jpg" height="80%" width="80%" alt="Logs Analytics Workspace"/>
<img src="https://i.postimg.cc/5NTGbyMQ/Whats_App_Image_2025_12_30_at_4_36_15_PM.jpg" height="80%" width="80%" alt="Logs Query"/>
<img src="https://i.postimg.cc/90Sxm8sZ/Whats_App_Image_2025_12_30_at_4_36_17_PM.jpg" height="80%" width="80%" alt="GeoIP Watchlist"/>
<img src="https://i.postimg.cc/C5tvhP9R/Whats_App_Image_2025_12_30_at_4_36_18_PM.jpg" height="80%" width="80%" alt="Workbook"/>



