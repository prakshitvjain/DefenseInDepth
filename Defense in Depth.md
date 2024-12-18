Defense in Depth (DID) is a robust strategy adopted by organisations to protect infrastructure from adversaries by implementing multiple layers of defenses. As the complexity and sophistication of cyber threats increased, Instead of relying on one protective measure, this multilayered defensive approach has proven to be a pain for attackers.

Different organisations require different protective measures depending upon the context of the organisation. In this article, we are going to discuss a generalized version of a Defense in Depth strategy. This technique promotes a proactive and holistic approach to security taking into account various threat vectors and potential vulnerabilities across different layers of the infrastructure.

![Defense In Depth](https://github.com/prakshitvjain/DefenseInDepth/blob/main/DefenseInDepth.png)
## Data Layer
Data Layer consists of sensitive data of the Organisation or PII (Personally Identifiable Information) which should be protected with multiple techniques and practices such as

- Data Classification
- Data Encryption
- Access Control - Principle of Least Privilege (PoLP)
- DLP - Data Loss Prevention
- Backup and Recovery
- Secure Data Storage (server and cloud)
- Monitoring Logs
- Regular Auditing

## Application Layer
The Application Layer refers to the Web Application itself and how it is developed, maintained and how it handles the user engagement and data.

- Secure Development Life Cycle (secure coding, automated tools for vulnerability scanning)
- Input Validation (SQLi & XSS)
- Authentication (MFA - Multi Factor Authentication)
- Authorization
- Session Management (session tokens are randomly generated, encrypted , safe from hijacking)
- Error and Exception Handling (provide meaningful error messages while not disclosing system information that attackers may use)
- Secure Configuration (Disable unnecessary features, set standards for password and other security settings)
- Secure File and Resource handling (RCE - Remote Code Execution)
- VAPT (Vulnerability Assessment and Penetration Testing)

## Host Layer
The Host layer focuses on securing individual hosts such as server workstations or other endpoints within a network from threats such as malware, phishing etc..

- Patch management
- Host based firewalls
- Strong authentication
- Data Encryption
- Log Monitoring
- Privilege Management
- Anti-viruses

## Internal Network
This Layer covers the components of the internal network such as Interconnected Systems, Devices and Resources within the organisation's network infrastructure. 
It refers to network components and assets that reside within the organisation's boundaries.
It focuses on protecting the network from threats that may arise from within the organisation or after a successful external breach.

- Network Segmentation VLAN, SDN (software define networking) - to prevent lateral movement in-case of breach.
- Access control (LoLP) - ACL (access control lists) - NAC (Network access controls)
- Network Monitoring - Logs - Incident response - SIEM (Security Information and Event Management)
- VPNs (Virtual Private Networks) are to be used in cases of remote access.

## Perimeter
The Perimeter represents the boundary where the organisation's internal network interfaces with the External network. It focuses on protecting the boundary or outer edge from unauthorized access and external threats.

- Firewalls (Stateful firewalls to filter and monitor the traffic)
- IDS / IPS (detect attack patterns and perform anomaly test)
- DMZ (de-militarized zone) - (to separate the public facing systems i.e Web server, Email servers from internal network ) - reverse proxies 
- WAF (to protect internal network from direct exposure to internet) 
- Secure Gateway (Web and Email - to scan incoming requests)

## Physical Layer
The Physical Layer focuses on protecting physical assets and infrastructure of the organisation. It focuses on safeguarding physical locations, facilities, equipment, devices and hardware from unauthorized access, theft, damage and tampering.

- Perimeter protection (fences, gates, walls, security guards, bio-metric etc..)
- Facility Security (Surveillance cameras, alarms)
- Data center security (Bio-metrics - Secure Access Cards)
- Temperature and Humidity monitoring to protect critical infrastructure.
- Intrusion Detection Systems (for server room etc.)
- Equipment protection (Secure critical hardware by locking them in secure cabinets)
- Secure disposal of unnecessary hardware, sensitive physical assets, hard drives, media tapes or printed documents.
- Emergency response (Employees must be trained to respond to different kinds of emergencies including natural disasters)
- Third party vendor management (Vendor should be monitored on how they handle you organisation's data) 

## Policies, Procedures and Awareness
Policies and Procedures provide a clear guideline on what is to be done and how it should be done. They help small scale organisations implement security measures that are followed by giant organisation.

- Risk Assessment
- Security Policies
     - Acceptable User Policy
     - Access Control
     - Data Handling
     - Data Retention/Destruction
- Policy Review and Approval
- Policy Distribution and Awareness
- Procedure Development
- Employee Training
- Compliance Monitoring
- Incident Response
- Review and Analysis
- Continuous Improvement
