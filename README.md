# Google-Cloud-Associate-Engineer-Certification

# Google Cloud Ecosystem

## Google Cloud Platform and Services
* CPUs, Memory Disks, Interfaces
* Servers VM Instances
* Clusters Cluster Management
* Serverless Autoscaling
* IT Ops, SysOps, DevOps, Low Ops, No Ops
* **Managing components:** component health, component functions, and performance, component backup, and replacement.
* **Managing systems:** system avaliablilty, system performance, system costs.
* **Managing resources:** users and identities,access to recources, resource consumptions
* OPEN SOURCE software
* Providers
* Developers

## Infrastructure Analogy
*

## Google Cloud Shell
*
## API interfaces
*
## Google Cloud Platform Virtual Cloud (VPC) Objects
* Projects
* Networks
* Subnetworks
* Regions
* Zones
* IP addresses
* vIRTUAL mACHINES
* Routes
* FireWalls

### Projects & Networks
**A project:**
Assosiates objects and services with billing. Contains networks(quota max 5).
**A network:**
Has no IP ADDRESS RANGE.
Is global and spans all avaliable regions.
Contains subnetworks.
Can be of type defoult, auto mode, or custom mode.

_Auto mode network can be converted to custom mode network, but "once custom, always custom."_  

## IP Adresses
* DNS resolution for internal addresses

* Assign a range of IP addresses as ali

## Virtual Networks

* Cloud Virtual Networks(CVN), Projects, Networks, Subnetworks, IP addresses, Routes, Firewall rules.

## Virtual Machines

* GCE, tags, VM options, vCPUs, disk options, images, and special features of persistent
disks for VMs
* Lab: Creating Virtual Machines
* Lab: Working with Virtual Machines

##  Cloud IAM
* Members, roles, organizations, account administration, service accounts
* Lab: Cloud IAM

## Data Storage Services

* Cloud Storage(only one not a database), Firebase can be an option as well, Datastore, Bigtable, Cloud Resource Manager
* Lab: Billing Administration
* Lab: Examining Billing Data and BigQuery

## Resource Management
* Billing, Quotas, Labels, Names, Cloud Resourse Manager
* Lab: Billing Administration
* Lab: Examining Billing Data and BigQuery

## Resource Monitoring
* Stackdriver, Monitoring, Logging, Error Reporting, Tracing, Debugging.
* Lab: Resource Monitoring(Stackdriver)
* Lab: Error Reporting and Debugging(Stackdriver)

## Interconnecting Networks
* VPNs, Cloud Router, Cloud Interconnect, Direct Peering, Cloud DNS
* Labs: Virtual Private Networks (VPN)
* Labs: Dynamic VPN with Cloud Routers
## Load Balancing
* Network Load Balancing, HTTP(S) Load Balancing, SSL Load Balancing and Internal Load Balancing, Managed Instance Groups.
* Lab: VM Automation and Load Balancing

### Day 1

1. Confirm one VM instance is always one exactly one physical host.
 a. Confirmed, at least for CPU and RAM, things like disks can come from other host.

2. Can you increase CPU for a VM without shutdown?
 a. NO

3. In the Minecraft exercise, Why is the data on the SSD lost on stop and start?
 a. It was just because the secondary disk had not been re-mounted in Linux after restart

4. Is there such a thing as composite roles inGCP?
  a.I dont think so, but you can filter the list of permissions by existing roles when creating the new one. So you could filter for each role to the new composite role.

5. Are there any tools or strategies to sync IAM permission between AWS and GCP? How would the difference in inheritance exclusion work?

  a. Somewhat useful blog by [Google](https://cloud.google.com/blog/products/gcp/google-cloud-iam-for-aws-users)

  b. Maybe Stratoscale, cant tell for sure [link](https://www.stratoscale.com/products/indentity-access-management/) 

  c. Jump Cloud Directory as a Service, seems more likely, but still not sure [link](https://jumpcloud.com/product/)

  d. Salespoint, seems most likely
[link](https://www.sailpoint.com/solutions/?elqct=Website&elqchannel=OrganicDirect)

   i. __"Our Cloud Identity Governance Platform allows you to connect and centrally control access to every application, file folder and cloud platform across your hybrid IT environment.”__

 

### Day 2
1. Do signed URLs for cloud storage require a public/private key pair on the part of the recepient? The signing is done by the sender.
a. No

2. When downloading a cloud storage object via REST API, if it has been encrypted with customer supplied key, how and when is it decrypted?

**More Resources:**


* [Get an account](https://cloud.google.com/)
## Path to Success

* [Review the exam guide](https://cloud.google.com/certification/guides/cloud-engineer/)

* [Get familiar with Stackdriver](https://www.qwiklabs.com/quests/35)

* [where you can take the exam.](https://cloud.google.com/certification/cloud-engineer) 
 
* [GDC Prizing Calculator](https://cloud.google.com/products/calculator/)

## Architecting with Google Cloud Platform: Infrastructure

* Google Cloud Platform Fundamentals: Core Infrastructure
* Essential Cloud Infrastructure: Foundation
* Essential Cloud Infrastructure: Core Services
* Elastic Cloud Infrastructure: Scaling and Automation
* Elastic Cloud Infrastructure: Containers and Services




## Suggested study resources for this section

* Google Cloud Platform Overview: https://cloud.google.com/docs/overview/
* Google Cloud Identity: https://cloud.google.com/identity/
* Google Cloud Pricing Calculator: https://cloud.google.com/products/calculator/
* Google Cloud Billing documentation: https://cloud.google.com/billing/docs/
* Stackdriver Fundamentals Quest: https://www.qwiklabs.com/quests/35
* Cloud SDK installation and quick start https://cloud.google.com/sdk/#Quick_Start
* gcloud tool guide https://cloud.google.com/sdk/gcloud/

## Suggested study resources for this section

* Google Cloud Pricing Overview: https://cloud.google.com/pricing/
* Google Cloud Pricing Calculator: https://cloud.google.com/products/calculator/
* Google’s Pricing philosophy: https://cloud.google.com/pricing/philosophy/
* Compute Engine Documentation: https://cloud.google.com/compute/docs/
* Choosing the right compute option in GCP: https://cloud.google.com/blog/products/gcp/choosing-the-right-compute-option-in-gcp-a-decision-tree
* Choosing a compute option: https://cloud.google.com/docs/choosing-a-compute-option
* Storage Classes: https://cloud.google.com/storage/docs/storage-classes
* Cloud Storage Options: https://cloud.google.com/storage-options/
* Load Balancing: https://cloud.google.com/load-balancing/docs/load-balancing-overview
