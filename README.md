# SOC-Home-Lab
My SOC Home Lab Journey
## Objective
Set up a Windows 10 virtual machine to serve as the endpoint for a Security Operations Centre (SOC) home lab.
 
## Tools Used
- VirtualBox
- Windows 10 ISO
- Host Operating System: Windows
 
## Tasks Completed
✅ Installed Oracle VirtualBox
 
✅ Created a Windows 10 Virtual Machine
 
✅ Allocated Resources
- RAM: 4 GB
- Disk: 60 GB
 
✅ Attached Windows 10 ISO
 
✅ Installed Windows 10 Successfully
 
✅ Verified VM Boots Correctly
 
## Key Skills Practised
- Virtualization
- Windows Deployment
- Lab Environment Configuration
- SOC Infrastructure Setup
 
## Lessons Learned
- How virtualization supports SOC training environments
- Benefits of isolated testing environments
- Basic Windows deployment and configuration
 
Screenshots
 
### VirtualBox Manager
 
virtualbox.png
 
### Windows 10 Desktop
 
Windows10VM.png
 
### System Information
 
System Information.png
## Next Steps
- Install Sysmon
- Configure Sysmon logging
- Generate Windows Event Logs
- Begin endpoint monitoring
Task 2: Sysmon Installation & Configuration
Objective

Deploy Microsoft Sysmon on a Windows 10 virtual machine to improve endpoint visibility and generate detailed security telemetry for monitoring and analysis.

Tools Used
Windows 10 Virtual Machine
Microsoft Sysmon
SwiftOnSecurity Sysmon Configuration
Event Viewer
Implementation Steps
Downloaded Microsoft Sysmon from the Sysinternals Suite.
Downloaded the SwiftOnSecurity Sysmon configuration file.
Installed Sysmon using an elevated Command Prompt.
Applied the SwiftOnSecurity configuration during installation.
Verified the Sysmon service was running successfully.
Confirmed event generation within Event Viewer.
Verification

Successfully verified:

Sysmon service status: Running
Sysmon driver loaded successfully
Event generation present in Event Viewer
Telemetry collection functioning as expected
Key Events Captured

Sysmon provides visibility into:

Process Creation (Event ID 1)
Network Connections (Event ID 3)
File Creation Events
Registry Activity
Driver Loading
Process Terminations
Skills Developed
Endpoint Monitoring
Windows Event Logging
Security Telemetry Collection
Log Analysis
Threat Detection Fundamentals
SOC Operations
Outcome

Successfully installed Microsoft Sysmon on a Windows 10 virtual machine and configured it using the SwiftOnSecurity Sysmon configuration. Verified service status and confirmed event generation in Event Viewer. This enhanced endpoint visibility by capturing detailed telemetry such as process creation, network connections, and file activity, mirroring security monitoring capabilities commonly used by SOC analysts.
Evidence
Screenshots

Upload the following screenshots:

Sysmon installation successful
Sysmon service running
Event Viewer showing Sysmon Operational logs
Lessons Learned
Sysmon significantly enhances native Windows logging capabilities.
Proper configuration is essential to reduce log noise while maintaining visibility.
Endpoint telemetry provides valuable data for threat detection and incident investigation.
Security Operations Centres rely heavily on host-based logs for monitoring suspicious activity.
