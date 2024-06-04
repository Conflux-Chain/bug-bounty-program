# Conflux Bug Bounty Program

As a cutting-edge public chain project, Conflux deeply understands the importance of system security for the entire ecosystem. To protect the Conflux system infrastructure and comprehensively enhance system security, Conflux has launched the Bug Bounty program. We sincerely invite our community members to join hands in discovering and fixing potential risks in the system. This program is not only a core measure to maintain the platform's security and integrity but also actively encourages security researchers and white hats to disclose system vulnerabilities to the official in a more responsible manner. We welcome security researchers and the public (referred to as "reporters" or "you") to help improve the system's security. If you believe you have found vulnerabilities, privacy issues, exposed data, or other security problems in any Conflux products, we hope to hear your suggestions through the Bug Bounty program according to this policy.

## Bug Scope

The scope of this program primarily covers Conflux's officially developed projects and products, including but not limited to:

1. Conflux-Rust: Conflux core protocol
2. Multi-language SDK frameworks: JavaScript, Python, Java, Go
3. Official wallets and DApps: Fluent Wallet, ConfluxHub
4. Infrastructure services: ConfluxScan, Confura Service

### Items not covered by this Bug Bounty program

To avoid any confusion, the following are considered outside the current policy scope and do not qualify for the Bug Bounty program:

- Social engineering attacks (e.g., phishing)
- Vulnerability attacks on third-party services
- Denial of Service attacks (DoS, DDoS)
- Minor issues in spelling and documentation
- Product experience feedback

Nevertheless, we may still reward any errors that have a significant impact on the overall security of the system, so we still encourage you to report relevant errors through the Bug Bounty or other means.

## Known Issue Assurance

Conflux commits to providing Known Issue Assurance to bug submissions through their program. This means that Conflux will either disclose known issues publicly or at the very least privately via a self-reported bug submission in order to allow for a more objective and streamlined mediation process to prove that an issue is known. Otherwise, assuming the bug report itself is valid, it would result in the bug report being considered in-scope and due 100% of the reward with respect to the bug bounty program terms.

## Bounty Levels

We categorize the bounties into five levels based on the severity and impact range of the vulnerabilities:

### 1. Informational

Description: These issues do not directly impact system security but help improve the overall security and robustness of the system.

Reward: 300 - 500 CFX

Examples:

- Security suggestions
- Code improvement suggestions that do not involve security risks

### 2. Low

Description: These vulnerabilities have a minor impact on system security but still need to be fixed to prevent possible future exploitation, such as information leakage, minor configuration errors, etc.

Reward: 500 - 1,000 CFX

Examples:

- Non-sensitive information leakage
- Minor configuration errors

### 3. Medium

Description: These vulnerabilities have a certain impact on system security but will not result in direct catastrophic consequences, such as cross-site scripting (XSS), moderately severe smart contract vulnerabilities, etc.

Reward: 1,000 - 5,000 CFX

Examples:

- Moderately severe smart contract vulnerabilities
- Cross-site scripting attacks

### 4. High

Description: These vulnerabilities may cause partial system functionality failure or carry exploitation risks, such as privilege escalation, sensitive data leakage, etc.

Reward: 5,000 - 20,000 CFX

Examples:

- Access control errors
- Vulnerabilities leading to user data leakage

### 5. Critical

Description: These vulnerabilities pose a serious threat to the security and integrity of the system, such as unauthorized fund transfers, severe smart contract vulnerabilities, etc.

Reward: 20,000 - 100,000 CFX

Examples:

- Major logical errors in smart contracts
- Vulnerabilities that could lead to large-scale fund losses

## Participation Guidelines

- Compliance: Please ensure your research and submissions comply with legal regulations and ethical standards. It is prohibited to conduct any destructive testing or attacks.

### Responsible Submission

After discovering a vulnerability, please contact us and report the vulnerability information as soon as possible via the official email; include a vulnerability description, vulnerability PoC, and repair suggestions.

### Bug PoC

For Bug PoC details, please refer to [Vulnerability PoC Guide and Rules](./bug-poc.md)

### Restrictions on Security Researcher Eligibility

Security researchers who fall under any of the following are ineligible for a reward

- Current employees, vendors (auditors), partners and contractors are not eligible to participate in the bug bounty program

### Participation Methods

- Send issue detail and PoC to `build@confluxnetwork.org`

### Contact Us

If have any problems contact us through email: build@confluxnetwork.org

## Bounty Issuance

Evaluation: We will evaluate based on the importance of the vulnerability module, actual impact, and discovery difficulty, and determine the bounty level.
Issuance: Rewards will be issued after the vulnerability is confirmed and fixed, through cryptocurrency or other appropriate means.
Disclosure: After the vulnerability is fixed, we will disclose the vulnerability details and the repair plan, and thank you for your contribution.

## Importance of Bug Bounties

Given Conflux's leading position in decentralized applications, financial services, and smart contracts, ensuring its network security is particularly important. The implementation of the Bug Bounty program not only enhances the security of the Conflux protocol and effectively prevents potential malicious exploitation but also stimulates the enthusiastic participation of community members in
