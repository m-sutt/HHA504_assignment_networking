# Assignment: Networking in Azure and GCP - IPs and Domain Management

## Instructions

### 1. Create a Virtual Private Cloud (VPC)
- **GCP:**
  - Access the Google Cloud Console and create a new VPC network.
  - Configure the IP address range and subnets similarly to your Azure setup.
<img width="1124" alt="GCP1" src="https://github.com/user-attachments/assets/a0f70098-3590-4635-bb4f-f13cd1a220c9">

<img width="1495" alt="GCP2" src="https://github.com/user-attachments/assets/aead0fcf-862f-4f06-99e7-8b6755baccaa">

<img width="1505" alt="GCP3" src="https://github.com/user-attachments/assets/b2edc46b-3994-4bfb-ab10-9a51099550ca">


### 2. Assign a Dedicated IP
- **GCP:**
  - Reserve a static external IP address for a Compute Engine instance within your VPC.

<img width="1499" alt="GCP4" src="https://github.com/user-attachments/assets/df131e2f-81ee-4085-a207-d43eb6ad9b43">

<img width="1501" alt="GCP5" src="https://github.com/user-attachments/assets/3dc6ddcc-f2d8-45b6-bfc6-794864360dd0">

<img width="1489" alt="GCP6" src="https://github.com/user-attachments/assets/e68b5d51-384d-4f34-95b5-5bdcab854362">

<img width="1500" alt="GCP7" src="https://github.com/user-attachments/assets/0d73ad7f-cc51-48ee-afb5-ce87d6056f2c">

### 3. Map IP to a Domain
- **GCP:**
  - Use Google Cloud DNS or an external domain registrar to map the reserved IP address to a domain name.

<img width="1500" alt="GCP8" src="https://github.com/user-attachments/assets/59931c16-f3f0-4208-a0c1-d7aa99e6b8f8">


### 4. Explore VPN and Tunnels (Optional)
- **GCP:**
  - Explore the Cloud VPN service and outline the process to create a tunnel between two VPCs.
  - I attempted to do this but could not figure out how to actually do it. Not quite sure what "Remote peer IP address" was referring to.
  
<img width="696" alt="GCP10" src="https://github.com/user-attachments/assets/e105eaf0-4878-4a93-940e-174ea85907ce">


## Instructions

### 1. Create a Virtual Private Cloud (VPC)
- **Azure:**
<img width="1446" alt="Azure1" src="https://github.com/user-attachments/assets/12b53968-fb5c-4a60-b221-7c03a0604d16">

<img width="1436" alt="Azure2" src="https://github.com/user-attachments/assets/1478ff0a-84f4-45df-b70e-f49c8ddb23c6">

<img width="1444" alt="Azure3" src="https://github.com/user-attachments/assets/e99dfe18-4c9b-45f6-94ce-76d5deab8b3b">


### 2. Assign a Dedicated IP
- **Azure:**
  - Reserve a static public IP address for a resource (e.g., a virtual machine) within your VNet.
  - Unable to create a VM on Azure

<img width="1429" alt="Azure4" src="https://github.com/user-attachments/assets/4aa8cd44-24f0-4ce2-a5ce-da73bbd0f43c">
<img width="1438" alt="Azure5" src="https://github.com/user-attachments/assets/3ff35ca3-2d44-4929-8d2d-e1fb7d67cfbc">



## Notes
- **GCP**
  - Relatively easy to use i.e., create and delete instances.
  - Friedly UI/UX.
  - The hardest about this was due to my lack of experience with GCP.
- **Azure**
  - The creation of a VPC is very simple.
  - I cannot get pass the "Size" option on Azure to create a VM.


