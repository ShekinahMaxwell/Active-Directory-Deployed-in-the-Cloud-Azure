<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Overview</h2>

-

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1381" alt="01" src="https://github.com/user-attachments/assets/56dc32c2-d30d-4459-b58d-f1337cf99c41">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="02" src="https://github.com/user-attachments/assets/f2e54e39-7644-4dd2-a174-283a6f957afa">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="03" src="https://github.com/user-attachments/assets/fab849f9-59d9-4684-a039-6813978d3c1f">
</p>
<p>

<p>
<img width="1436" alt="04" src="https://github.com/user-attachments/assets/f78cb55f-eb80-4935-87af-3ffcafcbc9ad">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="05" src="https://github.com/user-attachments/assets/74ab79c8-0d55-45ca-acdf-de98e699aa64">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="06" src="https://github.com/user-attachments/assets/54e23ec9-1e35-4f4d-8b9e-ebeea10ae85b">
</p>
<p>
.
</p>
<br />

<p>
<img width="1439" alt="07" src="https://github.com/user-attachments/assets/82ac09b1-32b3-407e-aea4-96db82da7be8">
</p>
<p>
.
</p>
<br />

<p>
<img width="1426" alt="08" src="https://github.com/user-attachments/assets/13134acc-b81f-4ca4-876f-87c1751f1328">
</p>
<p>
I forgot to place another arrow here, but click the code next to where it says Network Interface. 
</p>
<br />  
.
</p>
<br />

<p>
<img width="1440" alt="09" src="https://github.com/user-attachments/assets/5aa26c7c-e745-4713-93a2-981d86a020c8">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="10" src="https://github.com/user-attachments/assets/b0725c01-f2e7-49af-89f4-11cbf6f70133">
</p>
<p>
.
</p>
<br />

<p>
<img width="1387" alt="11" src="https://github.com/user-attachments/assets/f804cd16-cab3-4380-8bd3-ae7185148e6c">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="12" src="https://github.com/user-attachments/assets/5481d00d-5a12-4efd-aee1-4f4998f4939f">
</p>
<p>
Copy the IP address of Client-1 virtual machine and open Mac Remote Desktop. Click Add PC > Paste the IP address> Sign in.
</p>
<br />

<p>
<img width="1437" alt="13" src="https://github.com/user-attachments/assets/68259be2-e288-4582-9a91-f268aba3a810">
</p>
<p>
Copy Client-1 Private IP address. Search for the admin command line on your remote desktop and give the command to ping -t the IP address (See image).
</p>
<br />

<p>
<img width="1406" alt="14" src="https://github.com/user-attachments/assets/2ea53c28-fade-4af6-b18b-a955a41f28d1">
</p>
<p>
.
</p>
<br />

<p>
<img width="1417" alt="15" src="https://github.com/user-attachments/assets/5f336147-46a3-4213-9f28-6d370a52acc4">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="16" src="https://github.com/user-attachments/assets/44282b16-679b-4317-aa78-7ca4bd0b9629">
</p>
<p>
<img width="1440" alt="17" src="https://github.com/user-attachments/assets/4c1656b2-9f71-4dfd-aa07-6766ad180db3">
</p>
<p>
Open Windows Firewall> Inbound Rules> Expand the windoe so you can read more options at the top> Click Protocol> Right click on Echo request ICMPv4 and click Allow on both.
</p>
<br />

<p>
<img width="1440" alt="18" src="https://github.com/user-attachments/assets/3e3213ac-5663-4b63-a9a9-ebf07d74dcf2">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="19" src="https://github.com/user-attachments/assets/266d4140-15dd-4b40-9fc3-ced847665dc2">
</p>
<p>
Start Manager> Add Roles and Features> Ensure Role-based is selected and hit Next> Ensure DC-1 is selected and click Next> Click on Active Directory Domain Services >
</p>
<br />

<p>
<img width="1440" alt="20" src="https://github.com/user-attachments/assets/c95d642d-7d8a-4cbf-8aaa-75968535b4f7">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="21" src="https://github.com/user-attachments/assets/600b1c82-abad-4164-9763-3ee54322f5e5">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="22" src="https://github.com/user-attachments/assets/553c0c76-2845-447b-bb04-b80d73e22e0f">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="23" src="https://github.com/user-attachments/assets/45af448f-8fd4-4173-9863-74002358d75a">
</p>
<p>
.
</p>
<br />

<p>
<img width="1440" alt="24" src="https://github.com/user-attachments/assets/7b96fa64-d17e-41d5-bdb0-75a6f3b60193">
</p>
<p>
.
</p>
<br />
