<h1>Azure Sentinel-Honeypot Project</h1>
<h2>Description</h2>
<b>This PowerShell script parses Windows Event Log data for failed RDP attacks and uses a third-party API to retrieve geographic information about the attackers' locations.
</b>
<br />
<br />
In this demonstration, I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honeypot. We'll observe live RDP brute force attacks from around the world. Using a custom PowerShell script, I will look up the attackers' geolocation information and plot it on an Azure Sentinel map.
<br />
<br />

<img width="1920" alt="Screenshot 2024-07-17 at 12 36 38 PM" src="https://github.com/user-attachments/assets/e952668f-7ce3-4900-92db-79b5ff5dd7fa">

<h2>Languages Used</h2>

- <b>PowerShell:</b> Extracts RDP failed logon logs from Windows Event Viewer

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API


<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<img width="1521" alt="Screenshot 2024-07-17 at 1 28 55 PM" src="https://github.com/user-attachments/assets/fd9272dd-0ea2-4164-9e64-c249b5ed8f44">


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
