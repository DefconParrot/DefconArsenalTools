# Ensemble

Category: Bug Bounty

Tags: Bug Bounty, Scanner

Tool Presented at: Defcon 31 - (Y.2023)

Author/presenter: [Anthony 'DotNetRussell' Rusell](https://twitter.com/DotNetRussell)

## Tool Description

**Title** : DEF CON 31 Recon Village - Bug Bounty Recon Bypassing Geographic DNS with Ensemble

![DEF CON 31 Recon Village - Anthony Russell - Bug Bounty Recon Bypassing Geographic DNS with Ensemble](https://github.com/DefconParrot/DefconArsenalTools/assets/30528167/da877686-de2f-4f2b-9731-50602f5eb5c3)

Most bug bounty hunters are missing a huge attack surface when conducting their scans. Often large companies have GeoDNS enabled. If a hunter doesn’t actively bypass GeoDNS by toggling multiple different proxies, or VPNs in different regions, then the hunter only sees the services running on the server located closest to them geographically. The issue with this is that companies often have different services running on servers in different regions. All of which the hunter is missing during their recon phase.

Ensemble, a free open-source tool being released during Defcon 31, will solve this issue. By creating a load balanced, regionally distributed cluster of nodes and a friendly web portal to control them, Ensemble allows attackers to run identical commands simultaneously across multiple geographic regions. The results of the scans are then aggregated and returned to the hunter in an easy-to-use web platform. These commands can then be scheduled to run regularly so that hunter can get back to focusing on the technical details and not need to focus on manually switching proxy locations, VPNs, and rerunning the same commands over and over again which is highly error prone.

## Reference Links:

- Link to Tool⚙️ => https://github.com/DotNetRussell/Ensemble

- Link to slide✍️ => N/A

- Link to Talk(presentation)📺 => https://youtu.be/Bo77s0f1XNc

- Link to blog🧾 => N/A

## Author Description

- _Anthony 'DotNetRussell' Russell_ - Active Duty Army 05-10, Hobbyist Hardware/Software Hacking & a senior SWE.

## Author's Social Links:

- [Twitter: @DotNetRussell](https://twitter.com/DotNetRussell)
- [Website](dotnetrussell.com)
