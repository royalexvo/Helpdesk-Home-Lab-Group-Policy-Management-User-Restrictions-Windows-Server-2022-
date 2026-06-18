<h1>Helpdesk Home Lab – Group Policy Management & User Restrictions (Windows Server 2022)</h1>

<h2>Description</h2>

This lab demonstrates Group Policy Management within an Active Directory environment. The goal of this lab is to practice managing user settings, desktop restrictions, login behavior, wallpaper policies, shutdown options, password controls, and other administrative settings through Group Policy Objects (GPOs) commonly used by help desk technicians and system administrators.

In this lab, the following tasks were completed:

- <b>Opened and reviewed the Default Domain Policy</b>
- <b>Refreshed Group Policy settings on a client machine</b>
- <b>Configured a custom desktop wallpaper through Group Policy</b>
- <b>Created and configured a network share for wallpaper deployment</b>
- <b>Assigned NTFS permissions for wallpaper access</b>
- <b>Granted a domain user read access to the wallpaper share</b>
- <b>Configured desktop wallpaper restrictions</b>
- <b>Prevented users from changing the desktop wallpaper</b>
- <b>Reviewed screen saver policy settings</b>
- <b>Reviewed screen timeout policy settings</b>
- <b>Configured user desktop personalization settings</b>
- <b>Reviewed Start Menu policy options</b>
- <b>Configured power and shutdown restrictions</b>
- <b>Removed shutdown and restart options from the Start Menu</b>
- <b>Restricted access to password management options</b>
- <b>Disabled Task Manager through Group Policy</b>
- <b>Tested Group Policy changes on a Windows 11 workstation</b>
- <b>Reviewed Control + Alt + Delete policy settings</b>
- <b>Reviewed Windows component administrative templates</b>
- <b>Reviewed password and account lockout policy settings</b>

This lab demonstrates how Group Policy can be used to centrally manage user experience, security settings, and workstation restrictions across an Active Directory environment.

<h2>Languages and Utilities Used</h2>

- <b>Group Policy Management Console (GPMC)</b>
- <b>Active Directory</b>
- <b>Windows Server 2022</b>
- <b>Windows 11</b>
- <b>Server Manager</b>
- <b>Administrative Templates</b>
- <b>File Explorer</b>
- <b>Command Prompt (CMD)</b>

<h2>Environments Used</h2>

- <b>Domain Controller: Windows Server 2022</b>
- <b>Client Machine: Windows 11</b>
- <b>Active Directory Domain Environment</b>
- <b>Oracle VirtualBox</b>

<h2>Program walk-through:</h2>

<p align="center">
<b>Step 1 – Open Group Policy Management</b><br/><br/>
Launch Group Policy Management and open the Default Domain Policy for editing:<br/>
<img src="INSERT_STEP_1_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 2 – Review Existing Group Policy Settings</b><br/><br/>
Refresh the policy and review existing user and computer configuration settings:<br/>
<img src="INSERT_STEP_2_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 3 – Upload Wallpaper to the Shared Folder</b><br/><br/>
Use shared folder from previous labs that will host the corporate desktop wallpaper image:<br/>
<img src="INSERT_STEP_3_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 4 – Configure Share Permissions</b><br/><br/>
Transfer the wallpaper from the shared folder into the local share drive we created from previous labs. Assign the appropriate permissions required for users to access the wallpaper file:<br/>
<img src="INSERT_STEP_4_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 5 – Configure NTFS Permissions</b><br/><br/>
Grant users read access to the wallpaper image through NTFS permissions:<br/>
<img src="INSERT_STEP_5_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 6 – Configure Desktop Wallpaper Policy</b><br/><br/>
Specify the wallpaper network path within the Group Policy settings:<br/>
<img src="INSERT_STEP_6_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 7 – Deploy the Wallpaper Configuration</b><br/><br/>
Apply the wallpaper policy and configure the desired wallpaper style settings:<br/>
<img src="INSERT_STEP_7_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 8 – Prevent Wallpaper Changes</b><br/><br/>
Configure restrictions that prevent users from changing the desktop wallpaper:<br/>
<img src="INSERT_STEP_8_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 9 – Review Screen Saver Policies</b><br/><br/>
Explore screen saver timeout and enforcement settings within Group Policy:<br/>
<img src="INSERT_STEP_9_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 10 – Review Desktop Personalization Policies</b><br/><br/>
Review desktop and personalization administrative template settings:<br/>
<img src="INSERT_STEP_10_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 11 – Configure Shutdown Restrictions</b><br/><br/>
Remove shutdown and restart options from the Windows Start Menu:<br/>
<img src="INSERT_STEP_11_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 12 – Configure Password Restrictions</b><br/><br/>
Review and modify password-related options available to users:<br/>
<img src="INSERT_STEP_12_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 13 – Disable Task Manager</b><br/><br/>
Configure Group Policy settings to restrict access to Task Manager:<br/>
<img src="INSERT_STEP_13_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 14 – Review CTRL+ALT+DELETE Policies</b><br/><br/>
Explore security and logon options available through administrative templates:<br/>
<img src="INSERT_STEP_14_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 15 – Test Group Policy Changes</b><br/><br/>
Log in as a domain user and verify wallpaper, shutdown, and Task Manager restrictions:<br/>
<img src="INSERT_STEP_15_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 16 – Review Administrative Templates</b><br/><br/>
Explore additional Group Policy settings available through Windows components and administrative templates:<br/>
<img src="INSERT_STEP_16_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 17 – Review Password and Lockout Policies</b><br/><br/>
Review password complexity, password age, and account lockout configurations:<br/>
<img src="INSERT_STEP_17_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>

<p align="center">
<b>Step 18 – Validate User Experience Restrictions</b><br/><br/>
Confirm that Group Policy changes are successfully applied to the Windows 11 workstation:<br/>
<img src="INSERT_STEP_18_IMAGE_HERE" height="80%" width="80%" alt="Lab Steps"/>
</p>
