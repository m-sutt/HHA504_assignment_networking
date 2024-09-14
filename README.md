# HHA504_assignment_networking

## Objective
The objective of this assignment is to explore the networking features in Azure and Google Cloud Platform (GCP), focusing on Virtual Private Cloud (VPC), Virtual Private Network (VPN), IP addresses, and domain management. You will gain practical experience in assigning dedicated IPs and mapping them to domains.


### 1. Create a Virtual Private Cloud (VPC)
- **Azure:**
  - Navigate to the Azure portal and create a new Virtual Network (VNet).
  - Choose a simple IP address range and subnet configuration.
- **GCP:**
  - Access the Google Cloud Console and create a new VPC network.
  - Configure the IP address range and subnets similarly to your Azure setup.

### 2. Assign a Dedicated IP
- **Azure:**
  - Reserve a static public IP address for a resource (e.g., a virtual machine) within your VNet.
- **GCP:**
  - Reserve a static external IP address for a Compute Engine instance within your VPC.

### 3. Map IP to a Domain
- **Azure:**
  - Use Azure DNS or an external domain registrar to map the reserved IP address to a domain name.
- **GCP:**
  - Use Google Cloud DNS or an external domain registrar to map the reserved IP address to a domain name.

### 4. Explore VPN and Tunnels (Optional)
- **Azure:**
  - Explore the VPN Gateway service and document the steps you would take to set up a site-to-site VPN.
- **GCP:**
  - Explore the Cloud VPN service and outline the process to create a tunnel between two VPCs.

### 5. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the VPC/VNet creation and IP reservation process in both Azure and GCP.
  - Documentation of the steps taken to map the IP address to a domain in both platforms.
  - (Optional) Brief notes on VPN setup in Azure and GCP.
- Commit and push this Markdown document, along with the screenshots, to your GitHub repository.

## Deliverables
- September 22 2024: 11:59pm EST
- A Markdown document in a GitHub repository called `HHA504_assignment_networking` that includes:
  - Screenshots of VPC/VNet creation and IP reservation.
  - Steps and screenshots for mapping IPs to domains.
  - (Optional) Notes on VPN setup in Azure and GCP.


# Assignment: Exploring Serverless Computing and Cron Jobs in Azure, GCP, and GitHub

## Objective
The objective of this assignment is to introduce you to serverless computing and the use of cron jobs in cloud environments. You will deploy serverless functions on both Azure and Google Cloud Platform (GCP), and create a scheduled task using GitHub Actions.

## Instructions

### 1. Deploy a Serverless Function
- **Azure:**
  - Navigate to the Azure portal and create an Azure Function.
  - Choose a simple trigger (e.g., HTTP trigger) and deploy a basic function (e.g., "Hello, World").
- **GCP:**
  - Access the Google Cloud Console and create a Google Cloud Function.
  - Deploy a similar function with an HTTP trigger in GCP.

### 2. Create a Cron Job
- **GitHub Actions:**
  - Create a new GitHub repository (or use an existing one).
  - Set up a GitHub Action workflow that runs a script on a schedule (e.g., daily at midnight). You can use a simple script that logs "Scheduled task executed" to the console.

### 3. Explore Functions as a Service (FaaS)
- Reflect on the use cases for serverless functions in cloud environments. Consider the benefits and limitations of using Functions as a Service (FaaS) in both Azure and GCP.

### 4. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the serverless function deployment process in both Azure and GCP.
  - The code and configuration of your GitHub Action workflow.
  - Screenshots or documentation of the GCP Cloud Scheduler setup.
  - A brief reflection on the use cases, benefits, and limitations of serverless functions.
- Commit and push this Markdown document, along with the screenshots and code, to your GitHub repository.

## Deliverables
- September 29 2024: 11:59pm EST
- A Markdown document in a GitHub repository called `HHA504_assignment_functions` that includes:
  - Screenshots of the serverless function deployments.
  - Code and configuration for the GitHub cron job.
  - Documentation of the GCP Cloud Scheduler setup.
  - Reflection on serverless computing.
