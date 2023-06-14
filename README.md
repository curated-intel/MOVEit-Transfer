![image](https://github.com/curated-intel/MOVEit-Transfer/assets/59974887/6dafdc96-efde-4b99-b144-113e71170fda)


# MOVEit Transfer Hacking Campaign Tracking
- A repository for tracking events related to the MOVEit Transfer Hacking Campaign
- Events mapped to the Diamond Model, plus resources and information

### Event Summary Diagram
![image](https://github.com/curated-intel/MOVEit-Transfer/assets/59974887/d8938624-069f-4356-87e9-583cc4c892de)

| Publish Date | Type | Description | Source |
| --- | --- | --- | --- |
| 31 May | Resource | Initial Vendor Advisory, IOCs | [community.progress.com](https://community.progress.com/s/article/MOVEit-Transfer-Critical-Vulnerability-31May2023) | 
| 1 June | Resource | IOCs, Sigma & YARA Rules by Nextron Systems | [twitter.com/cyb3rops](https://twitter.com/cyb3rops/status/1664306595432394752) |
| 1 June | Capabilities | Rapid7 Observed Exploitation of Critical MOVEit Transfer Vulnerability since 27th Mary 2023, IOCs | [rapid7.com](https://www.rapid7.com/blog/post/2023/06/01/rapid7-observed-exploitation-of-critical-moveit-transfer-vulnerability/) |
| 1 June | Infrastructure | GreyNoise has observed scanning activity for the login page of MOVEit Transfer located at /human.aspx as early as March 3rd, 2023 | [greynoise.io](https://www.greynoise.io/blog/progress-moveit-transfer-critical-vulnerability) |
| 1 June | Resource | CrowdStrike shared FQL rules | [r/crowdstrike](https://www.reddit.com/r/crowdstrike/comments/13xujxt/20230601_situational_awareness_active_intrusion/) |
| 1 June | Capabilities | Huntress analysis of the MOVEit Transfer vulnerability, IOCs | [huntress.com](https://www.huntress.com/blog/moveit-transfer-critical-vulnerability-rapid-response) |
| 1 June | Capabilities | TrustedSec MOVEit Transfer campaign analysis, IOCs | [trustedsec.com](https://www.trustedsec.com/blog/critical-vulnerability-in-progress-moveit-transfer-technical-analysis-and-recommendations/) |
| 2 June | Resource | YARA rules for the Web Shell | [github.com/AhmetPayaslioglu](https://github.com/AhmetPayaslioglu/YaraRules/blob/main/MOVEit_Transfer_Critical_Vulnerability.yara) |
| 2 June | Resource | Sigma rule for MOVEit exploitation | [github.com/tsale](https://github.com/tsale/Sigma_rules/blob/main/Threat%20Hunting%20Queries/MOVEit_exploitation.yml) |
| 2 June | Resource | MOVEit Web Shell Checker | [github.com/ZephrFish](https://github.com/ZephrFish/MoveIT-WebShellCheck) |
| 2 June | Information | CVE-2023-34362 in MOVEit Transfer added to the NIST National Vulnerability Database | [nvd.nist.gov](https://nvd.nist.gov/vuln/detail/CVE-2023-34362) |
| 2 June | Capabilities | Mandiant campaign analysis, IOCs, YARA rules | [mandiant.com](https://www.mandiant.com/resources/blog/zero-day-moveit-data-theft) |
| 2 June | Information | CVE-2023-34362 in MOVEit Transfer added to the CISA Known Exploited Vulnerability (KEV) Database | [cisa.gov](https://www.cisa.gov/news-events/alerts/2023/06/02/cisa-adds-one-known-exploited-vulnerability-catalog) |
| 2 June | Adversary | Microsoft formally attributed the MOVEit Transfer campaign to the threat group called CL0P (aka Lace Tempest, FIN11, TA505) | [twitter.com/MsftSecIntel](https://twitter.com/MsftSecIntel/status/1665537730946670595) |
| 2 June | Victim | The University of Rochester mentions a "data breach, which resulted from a software vulnerability in a product provided by a third-party file transfer company, has affected the University and approximately 2,500 organizations worldwide." | [rochester.edu](https://www.rochester.edu/data-security/) | 
| 5 June | Resource | Identifying Data Exfiltration in MOVEit Transfer Investigations | [crowdstrike.com](https://www.crowdstrike.com/blog/identifying-data-exfiltration-in-moveit-transfer-investigations/) |
| 5 June | Victim | Austrian Financial Market Authority (FMA) files stolen from MOVEit software | [ots.at](https://www.ots.at/presseaussendung/OTS_20230605_OTS0139/finanzmarktaufsichtsbehoerde-fma-von-moveit-hacker-angriff-betroffen?app=1) |
| 5 June | Victim | Zellis' MOVEit Transfer breached, impacting British Airways, BBC, Boots, and Aer Lingus, potentially others | [therecord.media](https://therecord.media/bbc-british-airways-hit-by-zellis-zero-day) |
| 5 June | Adversary | Clop ransomware claims responsibility for MOVEit extortion attacks via a [ransom note](https://github.com/curated-intel/MOVEit-Transfer/blob/main/Images/note.png) on their leak site | [bleepingcomputer.com](https://www.bleepingcomputer.com/news/security/clop-ransomware-claims-responsibility-for-moveit-extortion-attacks/) |
| 6 June | Victim | University of Rochester and the Government of Nova Scotia are the first known MoveIT victims in North America | [therecord.media](https://therecord.media/rochester-university-nova-scotia-move-it-victims) |
| 7 June | Adversary | Clop ransomware tells those affected to email them before 14 June or stolen data will be published | [BBC](https://www.bbc.com/news/technology-65829726) |
| 7 June | Adversary/Capabilities | FBI & CISA joint advisory on CL0P, details about other TA505 campaigns, and other incidents such as the GoAnywhere attacks, IOCs, YARAs  | [cisa.gov](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a) |
| 7 June | Victim/Capabilities | SentinelOne's campaign analysis, hunting queries, IOCs | [sentinelone.com](https://www.sentinelone.com/blog/moveit-transfer-exploited-to-drop-file-stealing-sql-shell/) |
| 7 June | Victim | Extreme Networks declares having learned that their instance of MOVEit Transfer tool was impacted by a malicious act | [computerweekly.com](https://www.computerweekly.com/news/366539753/Extreme-Networks-emerges-as-victim-of-Clop-MOVEit-attack) |
| 8 June | Capabilities | Kroll's Timeline of the campaign (dating it back to 2021), IOCs | [kroll.com](https://www.kroll.com/en/insights/publications/cyber/clop-ransomware-moveit-transfer-vulnerability-cve-2023-34362) |
| 9 June | Resource | Progress Software issues a new patch covering new vulnerabilities | [progress.com](https://www.progress.com/security/moveit-transfer-and-moveit-cloud-vulnerability)
| 9 June | Victim | Illinois government among victims of global ransomware attack | [chicagotribune.com](https://www.chicagotribune.com/politics/ct-illinois-government-ransomware-attack-20230609-anvuvxf6lbdubev4xkgpyt3upe-story.html) |
| 9 June | Victim | Minnesota Department of Education hit by cybersecurity attack | [cbsnews.com](https://www.cbsnews.com/minnesota/news/minnesota-department-of-education-hit-by-cybersecurity-attack-95000-students-data-breached/) |
| 9 June | Victim | HSE states no more than 20 people's data breached in cyber-attack | [hse.ie](https://www.hse.ie/eng/services/news/media/pressrel/hse-statement1.html) |
| 9 June | Capabilities | Horizon3AI's analysis of the MOVEit Transfer campaign, accompanied by a Proof-of-Concept (PoC) for CVE-2023-34363, and IOCs | [horizon3.ai](https://www.horizon3.ai/moveit-transfer-cve-2023-34362-deep-dive-and-indicators-of-compromise/) |
| 12 June | Victim | Ofcom (the UK’s communications regulator) and Ernst & Young (EY), one of the 'Big 4' accounting firms | [bbc.co.uk](https://www.bbc.co.uk/news/technology-65877210) |
| 13 June | Victim | Transport for London (TfL) is warning 13,000 staff - half its entire workforce - that their details have been stolen by CL0P, via following the Zellis payroll outsourcer MOVEit Transfer hack | [twitter.com/gazthejourno](https://twitter.com/gazthejourno/status/1668594412782252038) |
| 13 June | Victim | Prudential Assurance Malaysia Berhad (PAMB) and Prudential BSN Takaful Berhad (PruBSN) can confirm that we are among many companies around the world that have been affected by the global MOVEit data-theft attack | [prudential.com.my](https://www.prudential.com.my/en/our-company-newsroom/announcements/moveit-cyber-security-incident/)|
| 13 June | Victim | State of Missouri Issues Statement on Recent Global Cyberattack | [oa.mo.gov](https://oa.mo.gov/commissioners-office/news/state-missouri-issues-statement-recent-global-cyberattack) |
| 14 June | Victim | Victims Listed on CL0P's leak site: 1st Source Bank, Datasite LLC, First National Bankers Bankshares Inc (FNBB), Green Shield (health services organization in Canada, only payer-provider in Canada), Heidelberger, Leggett & Platt, National Student Clearinghouse, ÖKK Kranken- und Unfallversicherungen AG, Putnam Investments, United HealthCare Services Inc, Shell, and the University of Georgia | [CL0P Data Leak Site](https://github.com/curated-intel/MOVEit-Transfer/blob/main/Images/paste.png) |
