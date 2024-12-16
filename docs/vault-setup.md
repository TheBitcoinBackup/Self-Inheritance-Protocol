---
layout: default
title: Vault Setup
nav_order: 3
parent: null
has_children: false
---

## 1. Vault Setup

Need help with this step? [Book a consultation](https://thebitcoinbackup.com/services)

### Video Guides
Watch the detailed video guides for this section:
- [Welcome to the Course](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+1.mp4)
- [The Logic Behind Cold Storage](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+2.mp4)
- [Single Signature vs Multi Signature](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+3.mp4)
- [Signing Keys - Seeds and Passphrase](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+4.mp4)
- [Vault Setup Overview](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+5.mp4)
- [Recovery Packages Distribution](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+6.mp4)
- [The Right Setup for You](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+7.mp4)

### Vault Structure
![Multi-Signature Setup](/assets/images/multi-signature-setup.png)

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

### Trust Model
```
Guardian 1 --[Seed 1]--> |
Guardian 2 --[Seed 2]--> |
Guardian 3 --[Seed 3]--> |--[3 of 5 Required]-- Vault Access
Guardian 4 --[Seed 4]--> |
Owner     --[Seed 5]--> |

Heir 1    --[Passphrase]--> |
Heir 2    --[Passphrase]--> |--[Required for each Seed]
Owner     --[Passphrase]--> |
```

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
