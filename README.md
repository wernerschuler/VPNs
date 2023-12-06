<h1>Setting up and using ProtonVPN</h1>
This tutorial outlines the steps to setup ProtonVPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> 

<h2>List of Prerequisites</h2>

- Access to Microsoft Azure
- Free version of ProtonVPN

<h2>Steps</h2>

<p><strong>(1. Create a virtual machine in Azure)</strong><br></p>

<p>
  <img src="https://i.imgur.com/EeULlca.png" height="50%" width="60%" alt="Create virtual machine"/> <br> <br> 
  - Go to portal.azure.com <br>
  - Click Virtual machines <br>
  - Click Create, then Azure virtual machine<br>
  - Add a virtual machine name <br>
  - Resource group will be created automatically <br>
  - Set region to somewhere that is different from where you live <br>
  - For image pick Windows 10 Pro <br> <br>
  <img src="https://i.imgur.com/nWLXFFx.png" height="50%" width="60%" alt="Create virtual machine 2"/> <br> <br>
  - Set the Size to 2 vcpus or more <br>
  - Set your Username and Password to something you will remember <br>
  - Click Review + Create <br>
  - After it's done validating click Create 
</p>
<br />

<p>
<strong>(2. Log into the virtual machine with Remote desktop connection)</strong></p><br>
<img src="https://i.imgur.com/D3ce1QI.png" height="50%" width="60%" alt="Remote connection"/> <br>
  - Click Start <br>
  - Search for Remote Desktop Connection <br>
  - Enter the public IP address of the newly created virtual machine <br>
  - Click Connect <br> <br>
  <img src="https://i.imgur.com/M3SkZ2l.png" height="50%" width="60%" alt="Remote connection"/> <br>
  - Click More choices <br>
  - Click Use a different account <br>
  - Enter the Username and Password that you have created for the virtual machine <br>
  - Click OK <br>
  - Click Yes <br> 
</p>
<br />

<p>
  <strong>(3. Get IP address and location for the virtual machine)</strong> <br>
   - From within the virtual machine visit whatismyipaddress.com <br>
   - Make a note of the IP address and city <br> </p>


<p> <strong>(4. Sign up and download ProtonVPN)</strong> <br>
   - Go to your actual computer <br>
  - Search ProtonVPN <br>
  - Click Create account <br>
  - Click Get Proton Free <br>
  - Enter your Email address <br>
  - Set your password <br>
  - Once your account is created copy the URL and paste it into your virtual machine <br>
  - Sign in to ProtonVPN from your virtual machine <br>
  - Download the Windows ProtonVPN client <br>
  - Install the ProtonVPN file <br> </p>

<p>
  <strong>(5. Test the VPN)</strong> <br>
  - From your virtual machine go to the ProtonVPN app <br>
  - Sign in <br> <br>
  <img src="https://i.imgur.com/GdHex8Z.png" height="50%" width="60%" alt="Japanese Amazon"/> <br>
  - Next to Free connection click Connect <br>
  - Browse to whatismyipaddress.com <br>
  - Make a note of the IP address and location <br> <br>
  <img src="https://i.imgur.com/1EUwmke.png" height="50%" width="60%" alt="Japanese Amazon"/> <br>
  - Try browsing to Amazon and/or Disney and see if there is anything different about the sites in relation to the location of your VPN server <br>
    &nbsp Because I am connected to a Japanese server Japanese websites have appeared in my Google search
</p>
  
</p>
<br />
