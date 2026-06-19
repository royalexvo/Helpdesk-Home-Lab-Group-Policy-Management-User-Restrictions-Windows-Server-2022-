# Helpdesk Home Lab – Group Policy Management & User Restrictions (Windows Server 2022)

<h2>Description</h2>

This lab demonstrates Group Policy administration within an Active Directory environment. The goal of this lab is to practice configuring desktop restrictions, enforcing corporate wallpapers, controlling user access to system features, managing shutdown options, configuring screen saver policies, and applying centralized workstation management through Group Policy Objects (GPOs).

In this lab, the following tasks were completed:

- <b>Edited the Default Domain Policy</b>
- <b>Configured a custom desktop wallpaper through Group Policy</b>
- <b>Created a shared folder for wallpaper deployment</b>
- <b>Configured share permissions for wallpaper access</b>
- <b>Granted a domain user read access to the wallpaper file</b>
- <b>Configured desktop wallpaper enforcement</b>
- <b>Prevented users from changing the desktop wallpaper</b>
- <b>Reviewed desktop personalization policies</b>
- <b>Reviewed screen saver policy settings</b>
- <b>Reviewed screen timeout policy settings</b>
- <b>Reviewed Start Menu policy settings</b>
- <b>Configured shutdown and restart restrictions</b>
- <b>Removed shutdown and restart options from the Start Menu</b>
- <b>Reviewed login and lock screen settings</b>
- <b>Reviewed CTRL+ALT+DELETE policy settings</b>
- <b>Restricted password change functionality</b>
- <b>Disabled Task Manager through Group Policy</b>
- <b>Tested policy enforcement on a Windows 11 workstation</b>
- <b>Reviewed Administrative Template settings</b>
- <b>Reviewed Windows Component policy settings</b>
- <b>Reviewed password policy settings</b>
- <b>Reviewed account lockout policy settings</b>

This lab demonstrates how administrators can centrally manage user experience, workstation restrictions, desktop customization, and security controls through Active Directory Group Policy. :contentReference[oaicite:0]{index=0}

<h2>Languages and Utilities Used</h2>

- <b>Group Policy Management Console (GPMC)</b>
- <b>Active Directory</b>
- <b>Windows Server 2022</b>
- <b>Windows 11</b>
- <b>Server Manager</b>
- <b>Administrative Templates</b>
- <b>File Explorer</b>
- <b>Shared Folders</b>

<h2>Environments Used</h2>

- <b>Domain Controller: Windows Server 2022</b>
- <b>Client Machine: Windows 11</b>
- <b>Active Directory Domain Environment</b>
- <b>Oracle VirtualBox</b>

<h2>Program walk-through:</h2>

<p align="center">

<p align="center">
<b>Step 1 – Create a Wallpaper Repository</b><br/><br/>
Create a wallpaper sub-folder in our share drive that will store the corporate wallpaper image:<br/>
<img src="INSERT_STEP_3_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 2 – Configure Share Permissions</b><br/><br/>
Assign share permissions required for users to access the wallpaper file:<br/>
<img src="INSERT_STEP_4_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 3 – Configure Wallpaper Policy</b><br/><br/>
Specify the network path for the desktop wallpaper within Group Policy Editor:<br/>
<img src="INSERT_STEP_6_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 4 – Deploy the Wallpaper Configuration</b><br/><br/>
Apply wallpaper settings on the Windows 11 machine. I had to use a workaround because I don't have Windows 11 activated on the machine:<br/>
<img src="INSERT_STEP_7_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 5 – Prevent Wallpaper Changes</b><br/><br/>
Configure restrictions that prevent users from changing the desktop wallpaper:<br/>
<img src="INSERT_STEP_8_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 6 – Configure Screen Saver Policies</b><br/><br/>
Enable screen saver and set the timeout out option to 15 minutes within the Group Policy Editor:<br/>
<img src="INSERT_STEP_9_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 7 – Configure Shutdown Restrictions</b><br/><br/>
Remove shutdown and restart options from the Windows Start Menu:<br/>
<img src="INSERT_STEP_11_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 8 – Review Login and Lock Screen Policies</b><br/><br/>
Review user login, lock screen, and authentication-related policy settings:<br/>
<img src="INSERT_STEP_12_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 9 – Configure Password Change Restrictions</b><br/><br/>
Restrict user access to password management options through Group Policy:<br/>
<img src="INSERT_STEP_13_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 10 – Disable Task Manager</b><br/><br/>
Configure Group Policy settings to prevent users from launching Task Manager:<br/>
<img src="INSERT_STEP_14_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 11 – Review Administrative Templates</b><br/><br/>
Explore available Administrative Template settings for user and computer management:<br/>
<img src="INSERT_STEP_15_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 12 – Review Windows Component Policies</b><br/><br/>
Review Windows component settings including Edge, Calculator, and system applications:<br/>
<img src="INSERT_STEP_16_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 13 – Test Group Policy Enforcement</b><br/><br/>
Log in as a domain user and verify wallpaper, shutdown, and Task Manager restrictions:<br/>
<img src="INSERT_STEP_17_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 14 – Review Password and Lockout Policies</b><br/><br/>
Review password age, password complexity, and account lockout policy settings:<br/>
<img src="INSERT_STEP_18_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 15 – Validate User Experience Restrictions</b><br/><br/>
Confirm that all Group Policy changes are successfully applied to the Windows 11 workstation:<br/>
<img src="INSERT_STEP_19_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>
