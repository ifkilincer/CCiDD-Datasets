# CCiDD-Dataset
The most common attack scenarios and user traffic in daily life were used in the study. In the study, it was requested that the target system reflects a realistic system. Web-Browsing, e-commerce, Remote Desktop, Meetings, Social Media, P2P traffics given were used for normal user traffic. Three separate physical computers with i7 processor and 16 GB RAM were installed on the target network for attack traffic. Later, Windows XP, Windows 7, Windows 10, Windows Server 2012, Ubuntu 20.04, Turkish operating system Pardus, bWAPP and Metasploit machines were installed on virtually every computer. A total of 24 virtual computers were installed on 3 physical machines in total. It is ensured that all computers get ip from DHCP server. 
CICFlowMeter software was used to create the data set. Data packets were collected with Wireshark for each attack scenario organized from the attacker machine and for the applications tested on the user's computer. The obtained Wireshark Capture files are parsed with CICFlowMeter software. CICFlowMeter is an open source software that separates network traffic into 80 features. Creates Biflows and extracts features from online network traffic or ready “pcap” extension files 
Details: https://www.sciencedirect.com/science/article/pii/S0045790622001598?dgcid=coauthor#fig0006 
