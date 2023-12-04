# VPNs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Setting up and using ProtonVPN</h1>
This tutorial outlines the steps to setup ProtonVPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Have Azure account
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<strong>(Create a virtual machine in Azure)</strong><br>
  - Go to portal.azure.com <br>
  - Click Virtual machines <br>
  - Click Create, then Azure virtual machine<br>
  - Add a virtual machine name <br>
  - Resource group will be created automatically <br>
  - Set region to somewhere that is different from where you live <br>
  - For image pick Windows 10 Pro <br>
  - Set the Size to 2 vcpus or more <br>
  - Set your Username and Password to something you will remember <br>
  - Click Review + Create <br>
  - After it's done validating click Create 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<strong>(Log into the virtual machine with Remote desktop connection)</strong></p><br>
  - Click Start <br>
  - Search for Remote Desktop Connection <br>
  - Enter the public IP address of the newly created virtual machine <br>
  - Click Connect <br>
  - Click More choices <br>
  - Click Use a different account <br>
  - Enter the Username and Password that you have created for the virtual machine <br>
  - Click OK <br>
  - Click Yes <br> 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <strong>(Get IP address and city for the virtual machine)</strong> <br>
  From within the virtual machine visit whatismyipaddress.com <br>
  Make a note of the IP address and city <br>

  <strong>Sign up and download ProtonVPN</strong> <br>
  Go to your actual computer <br>
  Search ProtonVPN <br>
  Click Create account <br>
  Click Get Proton Free <br>
  Enter your Email address <br>
  Set your password <br>
  Once your account is created copy the URL and paste it into your virtual machine <br>
  Sign in to ProtonVPN from your virtual machine <br>
  Download the Windows ProtonVPN client <br>
  Install the file <br>

<p>
  <strong>Test the VPN</strong> <br>
  - Go to the ProtonVPN app <br>
  - Sign in <br> 
  - Next to Free connection click Connect <br>

</p>
  

</p>
<br />
