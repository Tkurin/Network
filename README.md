 <h1 align="center" style="font-size: 3em; color: #3498db;">                                                                                                                   
Thane's SIEM Journey                                                                                                                                                        
</h1>                                                                                                                                                                         
                                                                                                                                                                           
<p align="center">                                                                                                                                                            
 A hands-on project documenting the setup and configuration of a home lab focused on Security Information and Event Management (SIEM).                                      
</p>                                                                                                                                                                          
                                                                                                                                                                              
---                                                                                                                                                                           
                                                                                                                                                                             
## 🎯 Project Overview                                                                                                                                                       
                                                                                                                                                                              
This repository serves as a living document of my journey building a functional security lab from the ground up. My goal is to gain practical experience with                 
industry-standard tools and demonstrate my skills in cybersecurity defense, monitoring, and analysis.                                                                         
                                                                                                                                                                              
 ### Core Objectives:                                                                                                                                                          
                                                                                                                                                                           
**🔵 Installing and Setting up Wazuh:**                                                                                                                                   
*   Deploy the Wazuh manager, indexer, and dashboard.                                                                                                                     
*   Install and enroll agents on various endpoints (e.g., Windows, Linux).                                                                                                
*   Customize rules and decoders to monitor critical security events.                                                                                                     
                                                                                                                                                                          
**🧱 Adding a Firewall:**                                                                                                                                                 
*   Implement and configure a firewall (like pfSense or OPNsense) to segment the network and control traffic.                                                             
*   Define strict inbound and outbound rules to create a secure perimeter.                                                                                                
*   Forward firewall logs to Wazuh for centralized analysis.                                                                                                              
                                                                                                                                                                            
**🛡️ Implementing an IDS/IPS:**                                                                                                                                           
*   Deploy an Intrusion Detection and Prevention System (like Suricata or Snort).                                                                                         
*   Configure rulesets to detect known threats and suspicious patterns.                                                                                                   
*   Integrate the IDS/IPS with the firewall to enable active response and block malicious traffic automatically.                                                         
                                                                                                                                                                             
