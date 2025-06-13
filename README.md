<h1>Group Policy Management (GPMC) – Edit The Group Policy Of A Domain</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to edit the Group Policy of a Domain using Group Policy Management. Editing the Group Policy of a domain using Group Policy Management allows administrators to centrally configure and enforce settings across all computers and users within that domain. This includes managing everything from security policies to desktop configurations. By modifying Group Policy settings, administrators can control aspects like software deployment, user experience, and security configurations.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Group Policy Management Tool</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: Group Policy = the rules of a user group (password length, etc)</b></span>  
<br/><br/><br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	Two ways to get to Group Policy Manager: 1) Through Server Manager  (AND)  2) Windows search: Group Policy Management</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>WAY ONE: Use Search Bar at the bottom of Windows Server.  Type: Server Manager.  Click: Tools (top right).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Hf9neXA.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/iGkK9it.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/6djpmj3.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Group Policy Management.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0crc4Ze.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/i55NJh7.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>WAY TWO: Use Search Bar at the bottom of Windows Server  (OR)  Windows OS with RSAT Tools.  Type: Group Policy Management</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/pPrSCrK.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/JlJKF0q.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: The Forest you want to edit.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/3SMPnGG.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/qKhhzam.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: Domains.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/IYVmByl.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/Jls7oHR.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: The domain you want to edit.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/hf39XOH.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/bxzgozW.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: Default Domain Policy. If you get a warning message: Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/D56mpv8.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/pWfgS7N.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/hrqI7V2.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Edit.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/2tpGhTG.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/k3eucp8.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click OR Double: Computer Configuration  (OR)  User Configuration. Then, Click OR Double- Click: Policies  (OR)  Preferences.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/CdrnlaZ.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/lrLLnqp.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/FSg9e71.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/iN4dH2Y.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


