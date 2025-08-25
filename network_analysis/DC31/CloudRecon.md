# CloudRecon

Category: Network Analysis

Tags: Network Analysis

Tool Presented at: Defcon 31 - (Y.2023)

Author/presenter: [Jason Haddix](https://twitter.com/Jhaddix), [Gunnar Andrews](https://twitter.com/G0LDEN_infosec)

## Tool Description

![CloudRecon](https://pbs.twimg.com/media/F3B-xpYaEAI3Tp7?format=jpg&name=small)

CloudRecon is a suite of tools for red teamers and bug hunters to find ephemeral and development assets in their campaigns and hunts.

Often, target organizations stand up cloud infrastructure that is not tied to their ASN or related to known infrastructure. Many times these assets are development sites, IT product portals, etc. Sometimes they don't have domains at all but many still need HTTPs.

CloudRecon is a suite of tools to scan all the cloud providers and find these hidden gems for testers, by inspecting those SSL certificates.

The tool suite is three parts in GO:

- CloudScrape - A LIVE running tool to inspect the ranges for a keywork in SSL certs OU, CN, and SN fields in real time.
- CertStan - a tool to retrieve the ranges of AWS, GCP, and Azure, and download all their certs to your box. So you can have your OWN cert.sh database.
- CertSniff - a tool to parse and search through the downloaded certs for keywords.

## Reference Links:

- Link to Tool⚙️ => https://github.com/g0ldencybersec/CloudRecon
- Link to slide✍️ => _pending_
- Link to Talk(presentation)📺 => _pending_

## Author Description

_Jason Haddix_ is the CISO and “Hacker in Charge” at BuddoBot, a world-class adversary emulation consultancy. He's had a distinguished 15-year career in cybersecurity previously serving as the CISO of Ubisoft, Head of Trust/Security/Operations at Bugcrowd, Director of Penetration Testing at HP, and Lead Penetration Tester at Redspin. He has also held positions doing mobile penetration testing, network/infrastructure security assessments, and static analysis. Jason is a hacker and bug hunter to the core, and he is ranked 51st all-time on Bugcrowd's leaderboards. Currently, he specializes in recon and web application analysis. Jason has also authored many talks on offensive security methodology, including speaking at cons such as; DEF CON, Black Hat, OWASP, RSA, Nullcon, SANS, IANS, BruCon, Toorcon, and many more. Jason currently lives in Colorado with his wife and three children.

_Gunnar Andrews_ is an offensive security enthusiast from the Midwest. He enjoys offensive tool development, fitness, adventures, and gaming!

## Author's Social Links:

- [Twitter: Jason Haddix (@Jhaddix)](https://twitter.com/Jhaddix)
- [Twitter: Gunnar Andrews (@g0lden_infosec)](https://twitter.com/G0LDEN_infosec)
- [Website](#)
