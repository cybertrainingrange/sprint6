# SIEM (Security Information and Event Management)

## For the SIEM learning module, we will use Splunk and inject spoof data generated by pwnSpoof. [pwnSpoof](https://github.com/punk-security/pwnspoof) was created by Punk Security as a training exercise to use a log analytic tool such as Splunk and IIS logs to find login brute-force attacks and command injections.

Once you have created a set of logs, the idea is to load them into Splunk and use various techniques to answer the following questions:
1. What was the attackers IP address and user_agent?
2. Did the attacker authenticate and if so, with what account?
3. Where was geo-location of the attacker?
4. When did the attack occur?
5. What kind of attack was it?
6. What happened during the attack?
7. What artifacts may remain on the server?
8. What steps can be taken to remediate?

<p align="center">
<img width="527" alt="Screenshot 2023-06-14 at 5 59 56 PM" src="https://github.com/cybertrainingrange/sprint6/assets/119987538/1e802ab6-1f5d-49f6-bfac-89479b9f5c6c">
</p>

### What is SIEM?
SIEM is a comprehensive approach to managing and analyzing security event data and information from various sources within an organization's network infrastructure. SIEM systems collect, aggregate, correlate, and analyze security event logs and data from diverse sources such as network devices, servers, applications, and security solutions.

When considering a SIEM tool, it's important to evaluate your organization's specific requirements, such as the number of assets to monitor, log volume, compliance needs, and desired features. Additionally, it is advisable to consult the AWS Marketplace and the websites of the respective SIEM tool providers to get the most up-to-date and accurate pricing information.

### [10 Open Source SIEM Tools](https://docs.google.com/document/d/1riXHKLlF_mkX4h9bMYVgxjHBdLPMa6YNKPneNXRs-n4/edit)


### What is Splunk?
#### Splunk is a leading commercial SIEM platform known for its powerful log management and data analytics capabilities. It offers real-time monitoring, event correlation, and a wide range of prebuilt security use cases. Splunk supports integration with various data sources and has a large ecosystem of apps and add-ons.


### Benefits of Splunk
- It creates analytical reports through charts and graphs.
- A Splunk log is highly scalable and easy for organizations to implement.
- It can find useful information within organizations’ data without users having to identify it themselves.
- Its dashboard offers an enhanced graphical user interface (GUI) and real-time visibility.

<p align="center">
<img width="383" alt="Screenshot 2023-06-14 at 5 57 51 PM" src="https://github.com/cybertrainingrange/sprint6/assets/119987538/efcf9aa7-c037-4469-8498-d21b3911beea">
</p>





## Technical Documentation 🤖

### [How to Install Splunk with AWS](https://onedrive.live.com/edit.aspx?resid=C191A1F12836DFB8!6403&ithint=file%2cdocx&authkey=!AN1XZM_v9yTGjrI)
### [How to Inject pwnSpoof Data to Practice Splunk](https://docs.google.com/document/d/1YEcXMn2WSDLs6mpvjedmnkaNR2N38P8IPUElxEuDNgk/edit?usp=sharing)

## 🔗 Authors: 👐

### Nancy Uddin👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nancy-uddin/)
- [@Nancy Uddin](https://github.com/nancyuddin)


### Mayra Castillo👩‍
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayra-castillo-barrios/)
- [@Mayra Castillo](https://github.com/mbarri0s)
