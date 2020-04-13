### 3.1.1 Preparing to Handle Incidents 
### 3.1.1 インシデントハンドリングの準備

The lists below provide examples of tools and resources available that may be of value during incident handling.  
以下のリストは、インシデントハンドリング中に価値があると思われる利用可能なツールとリソースの例を提供しています。 

These lists are intended to be a starting point for discussions about which tools and resources an organization’s incident handlers need.  
これらのリストは、組織のインシデント・ハンドラーがどのようなツールやリソースを必要としているかを議論するための出発点となることを意図しています。 

For example, smartphones are one way to have resilient emergency communication and coordination mechanisms.  
例えば、スマートフォンは、回復力のある緊急通信と調整メカニズムを持つための一つの方法です。 

An organization should have multiple (separate and different) communication and coordination mechanisms in case of failure of one mechanism.  
組織は、1つのメカニズムが故障した場合に備えて、複数の（別々の、異なる）通信および調整メカニズムを持つべきです。 

#### Incident Handler Communications and Facilities:  

■ Contact information for team members and others within and outside the organization (primary and backup contacts), such as law enforcement and other incident response teams; information may include phone numbers, email addresses, public encryption keys (in accordance with the encryption software described below), and instructions for verifying the contact’s identity 
■ On-call information for other teams within the organization, including escalation information 
■ Incident reporting mechanisms, such as phone numbers, email addresses, online forms, and secure instant messaging systems that users can use to report suspected incidents; at least one mechanism should permit people to report incidents anonymously 
■ Issue tracking system for tracking incident information, status, etc. 
■ Smartphones to be carried by team members for off-hour support and onsite communications 
■ Encryption software to be used for communications among team members, within the organization and with external parties; for Federal agencies, software must use a FIPS-validated encryption algorithm20 
■ War room for central communication and coordination; if a permanent war room is not necessary or practical, the team should create a procedure for procuring a temporary war room when needed 
■ Secure storage facility for securing evidence and other sensitive materials  

#### Incident Analysis Hardware and Software:  

■ Digital forensic workstations21 and/or backup devices to create disk images, preserve log files, and save other relevant incident data 
■ Laptops for activities such as analyzing data, sniffing packets, and writing reports 
■ Spare workstations, servers, and networking equipment, or the virtualized equivalents, which may be used for many purposes, such as restoring backups and trying out malware 
■ Blank removable media 
■ Portable printer to print copies of log files and other evidence from non-networked systems 
■ Packet sniffers and protocol analyzers to capture and analyze network traffic 
■ Digital forensic software to analyze disk images 
■ Removable media with trusted versions of programs to be used to gather evidence from systems 
■ Evidence gathering accessories, including hard-bound notebooks, digital cameras, audio recorders, chain of custody forms, evidence storage bags and tags, and evidence tape, to preserve evidence for possible legal actions  

#### Incident Analysis Resources:  

■ Port lists, including commonly used ports and Trojan horse ports 
■ Documentation for OSs, applications, protocols, and intrusion detection and antivirus products 
■ Network diagrams and lists of critical assets, such as database servers 
■ Current baselines of expected network, system, and application activity ■ Cryptographic hashes of critical files22 to speed incident analysis, verification, and eradication  

#### Incident Mitigation Software:  

■ Access to images of clean OS and application installations for restoration and recovery purposes  



Many incident response teams create a jump kit, which is a portable case that contains materials that may be needed during an investigation. The jump kit should be ready to go at all times. Jump kits contain many of the same items listed in the bulleted lists above. For example, each jump kit typically includes a laptop, loaded with appropriate software (e.g., packet sniffers, digital forensics). Other important materials include backup devices, blank media, and basic networking equipment and cables. Because the purpose of having a jump kit is to facilitate faster responses, the team should avoid borrowing items from the jump kit.  


Each incident handler should have access to at least two computing devices (e.g., laptops). One, such as the one from the jump kit, should be used to perform packet sniffing, malware analysis, and all other actions that risk contaminating the laptop that performs them. This laptop should be scrubbed and all software reinstalled before it is used for another incident. Note that because this laptop is special purpose, it is likely to use software other than the standard enterprise tools and configurations, and whenever possible the incident handlers should be allowed to specify basic technical requirements for these specialpurpose investigative laptops. In addition to an investigative laptop, each incident handler should also have a standard laptop, smart phone, or other computing device for writing reports, reading email, and performing other duties unrelated to the hands-on incident analysis.  


Exercises involving simulated incidents can also be very useful for preparing staff for incident handling; see NIST SP 800-84 for more information on exercises23 and Appendix A for sample exercise scenarios. 