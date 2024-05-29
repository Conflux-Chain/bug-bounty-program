# Vulnerability PoC Guide and Rules

## Web2 PoC Guide

- A PoC for Web2 vulnerabilities does not necessarily have to be executable code. Including a short textual video content in the vulnerability report, showcasing the attack process, can also serve as a PoC. For video PoCs, HTTP request information must also be provided.
- Screenshots demonstrating the final attack effect can also serve as a PoC.
- HTTP request information can serve as a PoC.
- Command line or any executable code implemented through programming can serve as a PoC.
- Within the Web2 PoC verification rules, taking over a subdomain and providing proof is allowed.
- External links that can take over assets within the domain should provide proof according to the Web2 PoC rules.
- Generally, white hats are allowed to conduct black-box testing that does not affect the availability of the program/site. If the attack could cause the application/site to crash, white hats must first request and obtain permission from the official team.
- White hats must adhere to any other guidelines specified in the Bug Bounty program.
- If more PoC information is required for verification purposes and the white hat refuses to provide it, the PoC is usually considered invalid.
- If the white hat does not follow the guidelines, their report may be closed, and they may lose eligibility for the reward.

## Web2 PoC Rules

- Do not insert malicious JavaScript code into the website. Only insert harmless JavaScript code that does not affect other users and any other functions of the application. The code insertion method must not break website functionality.
- If you need to edit the website to prove the existence of a vulnerability, make the minimal edits necessary, such as inserting HTML comments (invisible to others), to avoid intrusiveness. The PoC should not affect the website's state and should avoid publicly disclosing the vulnerability's existence.
- Do not upload or attempt to upload web shells. If you need to upload files to build a PoC, upload empty files or non-executable text files.
- Do not disclose, modify, or access sensitive information beyond what is necessary for the Bug Bounty program without authorization.

## Web3 PoC Guide

- Protocol and implementation vulnerabilities should always be verified by forking the official repository code. Before submitting the vulnerable code to the official team, ensure it does not affect the mainnet protocol.
- For most projects, especially smart contract projects, a valid PoC is required to be considered a valid submission. Without providing a PoC, it is sometimes impossible to determine whether a vulnerability truly exists, and more importantly, whether the vulnerability will have an actual impact. A high-quality PoC can clearly demonstrate the existence of the vulnerability and its real impact on the system.
- The PoC for smart contracts should always be implemented using Hardhat or other tools to fork from the mainnet, rather than deploying and setting up local non-on-chain contract states, which might have mismatches with on-chain contract states.
- The PoC should include executable code to demonstrate the vulnerability exploitation. White hats can choose any framework or language to write the PoC. White hats should mention all dependencies, configuration files, and environment variables required to run the PoC, as well as any other requirements needed to run the tests. Code screenshots are not accepted.
- The PoC should have clear print statements and/or comments to detail each step of the attack and show relevant information, such as stolen/frozen funds, etc.
- White hats can directly upload the PoC, including all configuration files, to Google Drive and provide the official team with a share link.
- If the PoC is simple enough and does not require any configuration files, it can be shared directly with the official team by submitting the code.
- Additionally, it is recommended that white hats identify and provide data on the total amount of at-risk funds, such as by calculating the total number of tokens multiplied by the average price of the tokens over 7 days at the time of the vulnerability submission.
- White hats must follow any other guidelines specified in the Bug Bounty program under which they are submitting the vulnerability report.

## Web3 PoC Rules

- Do not conduct tests on public testnets or mainnets.
- Do not submit incomplete or partial vulnerability PoCs.

Violating the above rules may result in facing a range of legal risks.