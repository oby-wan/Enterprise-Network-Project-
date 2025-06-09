The reason this project exists is to create a resilient, secure and scalable enterprise network infrastructure that optimally and fully serves the academic, administrative, and operational activities in TTI’s multi-campus structure. The design served does both the present needs and the future growth due to persistent availability in uninterrupted access, management, and policy application(audit) throughout all campuses. 
![Physical Topo](https://github.com/user-attachments/assets/8f666424-85ce-4024-be35-4e3815c4922e)

Our works includes the design of the Layer 2 and Layer 3 topologies, secure site-to-site WAN access through the BCNET/CANARIE infrastructure, and the Active Directory service integration with DNS, DHCP, GPO, and other IAM services for control and policy enforcement. Moreover, we are implementing a secure Internet Edge with Cisco ASA appliances, VLAN Firewall segmentation for departmental isolation, and central Splunk logging fort real-time monitoring and fault detection.  

This case study is based on real-world tendering simulating a consulting project where every student group acts as a separate consulting firm to develop a proposed documentation and implementation network solution. Our design features LAN and WAN connectivity across several sites, remote access, data segmentation, distribution of central control, and high availability clusters. Following the industry best practices, we are supported with Cisco networking, Microsoft Active Directory, secure firewall appliances, and other leading technologies, demonstrating TTI's flexible, practical, and scalable solutions. 

![Physical Topo](https://github.com/user-attachments/assets/ac26ae9c-0dea-413d-bc7d-ce4fa47c97f2)


Each element of the network is realizing high availability and responsiveness such that they are always available and when an outage occurs the services are still maintained and smoothly delivered, sustain TTI's digital operations. 
![Logical](https://github.com/user-attachments/assets/e0c3ef20-50e3-4586-beed-15e1a4b10986)
![Logi2cal](https://github.com/user-attachments/assets/64800963-c979-43a9-ac9d-5abc67b2b0c3)

Integrating centralized logging through Splunk with Active Directory replication for regionally dispersed sites, implementing high availability for DHCP and DNS, as well as role-based access controls meets functional and security compliance. Our proof-of-concept implementation verifies each technical component and checks the feasibility of the proposed solution in the working enterprise environment. 
![FW1Addresses](https://github.com/user-attachments/assets/ea0dd9c9-5af6-421c-91ba-57df5f30e0d2)
![FW1 IPsec Tunnel](https://github.com/user-attachments/assets/c051701f-dd25-4a8e-b31b-3dfd129d6b79)

This report captures the technical reasoning of the design and implementation processes along with the advantages that our architecture would bring to TTI's future business activities. With this effort, we demonstrate applying learned concepts in a collaborative setting designed to simulate real world situations. 

![Dc1 DNS zones](https://github.com/user-attachments/assets/442ebcb1-d74b-47d0-869d-db74c6a85737)
![DHCP Failover](https://github.com/user-attachments/assets/9a55eb43-eef5-4d91-91b2-4e315d8d8cef)


We are proposing the establishment of a site-to-site VPN connection between our AWS cloud infrastructure and the on-premises data center at our Vancouver site. This connection will allow for secure, encrypted communication between both environments, ensuring that data and application traffic can flow seamlessly and securely between the cloud and the on-prem system. The core of the project will involve deploying a web server hosted on an EC2 instance in AWS. This EC2 instance will be part of a custom Virtual Private Cloud (VPC), specifically designed for this hybrid cloud architecture, which ensures that the deployed resources remain secure and highly available. [AWSProjectProposal-Group3.docx](https://github.com/user-attachments/files/20648598/AWSProjectProposal-Group3.docx)
