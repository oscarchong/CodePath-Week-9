# Week 9 Project- Honeypot

Time spent: 8 hours

### Honeypots Used:

- Dionaea "mhn-honeypot-1"

Used the google cloud sdk through an mhn-admin VM, I deployed the Ubuntu - Dionaea with HTTP honeypot as instructed

Issues encountered: Needing to alter the google cloud VPC firewall settings to allow for communication from myself to the mhn-admin instance and from the honeypots to the mhn-admin server.

I've left my honeypot running for 7 hours and below are the results collected. 

### Data Collected:

Total Attacks: 1206

#### Top 5 IPs:
- 62.210.141.119 (53 attacks) [France]
- 162.243.160.49 (39 attacks) [USA]
- 188.166.3.86 (76 attacks) [Netherlands]
- 104.248.29.221 (32 attacks) [USA]
- 104.248.19.20 (28 attacks) [USA]

#### Top 5 Ports:
- 8088 (330 times)
- 23 (78 times)
- 445 (69 times)
- 5060 (60 times)
- 8080 (27 times)

Malware Collected: None

Unresolved Issues: NONE
