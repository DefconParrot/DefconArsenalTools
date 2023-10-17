#  FuncoPop

Category/Tags: Microsoft, Exploitation, Azure, Cloud Tools

Tool Presented at: Defcon 31 - (Y.2023)

Author/presenter: [Thomas Elling](https://twitter.com/thomas_elling) & [Karl Fosaaen](https://twitter.com/kfosaaen)

## Tool Description

**Title** :  DEF CON Cloud Village - What the Function: A Deep Dive into Azure Function App Security

![FuncoPopLogo](https://notpayloads.blob.core.windows.net/images/FuncoPop-bg-final.png)

FuncoPop includes functions and scripts that support attacking Azure Funtion Apps, primarily through exploiting Storage Account Access. In many environments, users are granted generous Storage Account permissions (Storage Account Contributor) in Azure RBAC, resulting in access to Storage Accounts that support Function Apps. This unintended cross-service access can give an attacker the ability to pivot through Storage Accounts to gain access to Function Apps. This access includes visibility into the Funtion App keys, ability to run code in the Function App containers, and the ability to access Managed Identities attached to the Function Apps.

## Reference Links:

- Link to Tool⚙️ => https://github.com/NetSPI/FuncoPop

- Link to slide✍️ => https://github.com/NetSPI/FuncoPop/blob/main/WhatTheFunction-DC31_CV.pdf

- Link to Talk(presentation)📺 => *pending*

- Link to blog🧾 => N/A


## Author Description

- At the time of talk presentation, both *Karl Fosaaen* & *Thomas Elling* work at [NETSPI](https://www.netspi.com/) as cloud researchers.

![FuncoPop_WhatTheFunction-DC31_CV pdf at main · NetSPI_FuncoPop](https://github.com/DefconParrot/DefconArsenalTools/assets/30528167/c1a162b4-bc22-47fb-93d6-f77666b9c144)

## Author's Social Links:

- [Twitter: Karl Fosaaen](https://twitter.com/thomas_elling)
- [Twitter: Thomas Elling](https://twitter.com/thomas_elling)
