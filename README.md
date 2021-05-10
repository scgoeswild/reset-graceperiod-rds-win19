# reset-graceperiod-rds-win19

Tested with Windows Server 2019

For whatever reason, you may end up in a situation where you need to extend the grace period for Windows RDS server (remote desktop services, aka terminal server.) This can be a pain, especially if things time out and you lose RDP access to the server. In the Windows Server 2012 and Server 2012 R2 era, Microsoft provided the following PowerShell script for this scenario. But they no longer test or maintain the script. I have tested on Windows Server 2019 and it definitely still works.

To use the script, simply save to your RDS server and run in an elevated PowerShell prompt. The script is interactive and will tell you how many days are left (very handy as you can look it up extremely quickly this way) and lets you choose if you want to reset the time or not.
