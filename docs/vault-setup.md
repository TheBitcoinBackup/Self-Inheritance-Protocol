---
layout: default
title: Vault Setup
nav_order: 3
parent: null
has_children: false
---

## 1. Vault Setup

Need help with this step? [Book a free consultation](https://thebitcoinbackup.com)

### Video Guides
Follow along with the complete video series on either:
- [YouTube](https://www.youtube.com/watch?v=QSkuBn9uqHc&list=PL3s9juCCLq05UbdxikNPa8hOmddvS2BPa&index=5)
- [Internet Archive](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+1.mp4)

### Vault Structure
![Multi-Signature Setup](/assets/images/Vault%20Setup.png)

### Multi-Signature Structure
- **Type**: 3-of-5 multisignature wallet
- **Keys Required**: Any 3 of 5 signing keys to authorize transactions
- **Key Composition**: Each signing key combines:
  - Seed (12-word mnemonic)
  - Passphrase (additional 12-word mnemonic)

### Role Separation

#### Guardians (4 + Owner)
- Hold individual Seeds
- Passive, protective role
- Cannot access funds independently
- Store and protect recovery packages
- Do not open packages without owner permission

#### Heirs (2)
- Hold copies of the Passphrase
- Cannot access funds without guardian cooperation
- Require guardian authorization for recovery
- Receive complete recovery instructions

### Setup Variations

#### Standard Setup (Recommended)
- 4 Guardians + Owner (Seeds)
- 2 Heirs + Owner (Passphrase)
- 3-of-5 multisignature requirement

#### Alternative Configurations
1. **Minimal Setup**
   - 2 Guardians + Owner
   - 1 Heir + Owner
   - 2-of-3 multisignature

2. **Extended Setup**
   - 4 Guardians + Owner
   - 3+ Heirs + Owner
   - 3-of-5 multisignature

Before choosing your setup, use the Adaptation Guide to determine your guardian and heir structure:
[Download Adaptation Guide](https://github.com/TheBitcoinBackup/Self-Inheritance-Protocol/blob/main/assets/docs/starter-kit/Adaptation%20Guide%20-%20Self-Inheritance%20Protocol.pdf)
