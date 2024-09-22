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


### 5. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the VPC/VNet creation and IP reservation process in both Azure and GCP.
  - Documentation of the steps taken to map the IP address to a domain in both platforms.
  - (Optional) Brief notes on VPN setup in Azure and GCP.
- Commit and push this Markdown document, along with the screenshots, to your GitHub repository.

## Notes
**GCP**
- Relatively easy to use i.e., create and delete instances.
- Friedly UI/UX.
- The hardest about this was due to my lack of experience with GCP.


