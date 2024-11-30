# Self-Inheritance Protocol

<p align="center">
  A protocol for securing Bitcoin inheritance across generations<br>
  <a href="https://thebitcoinbackup.com">thebitcoinbackup.com</a>
</p>

## Table of Contents
- [Overview](#overview)
  - [Protocol Summary](#protocol-summary)
  - [Core Principles](#core-principles)
- [1. Vault Setup](#1-vault-setup)
  - [Video Guides](#video-guides)
  - [Multi-Signature Structure](#multi-signature-structure)
  - [Role Separation](#role-separation)
  - [Trust Model](#trust-model)
  - [Setup Variations](#setup-variations)
- [2. Hardware Preparation](#2-hardware-preparation)
  - [Video Guides](#video-guides-1)
  - [Required Materials](#required-materials)
  - [Workspace Organization](#workspace-organization)
- [3. Software Preparation](#3-software-preparation)
  - [Video Guides](#video-guides-2)
  - [Operating System](#operating-system)
  - [Wallet Software](#wallet-software)
  - [Signing Device Firmware](#signing-device-firmware)
- [4. Keys Generation](#4-keys-generation)
  - [Video Guides](#video-guides-3)
  - [Seed Generation Process](#seed-generation-process)
  - [Passphrase Generation](#passphrase-generation)
  - [Adding Passphrase to Seeds](#adding-passphrase-to-seeds)
- [5. Backups](#5-backups)
  - [Video Guides](#video-guides-4)
  - [Paper Backups](#paper-backups)
  - [Metal Backups](#metal-backups)
- [6. Wallet Generation](#6-wallet-generation)
  - [Video Guides](#video-guides-5)
  - [Public Key Export](#public-key-export)
  - [Wallet Creation](#wallet-creation)
  - [Wallet Descriptor Backup](#wallet-descriptor-backup)
- [7. Transactions](#7-transactions)
  - [Video Guides](#video-guides-6)
  - [Receiving Bitcoin](#receiving-bitcoin)
  - [Sending Bitcoin](#sending-bitcoin)
  - [Transaction Signing](#transaction-signing)
- [8. Recovery Packages](#8-recovery-packages)
  - [Video Guides](#video-guides-7)
  - [Package Types](#package-types)
  - [Assembly Process](#assembly-process)
  - [Distribution](#distribution)
- [Security Considerations](#security-considerations)
  - [Critical Security Points](#critical-security-points)
  - [International Transport Notes](#international-transport-notes)
- [License](#license)

## Overview

### Protocol Summary
The Self-Inheritance Protocol is a comprehensive system for creating secure, multi-generational Bitcoin vaults using multi-signature wallets. It enables individuals to establish trustless inheritance systems without relying on third parties.

This protocol helps you create a 3-of-5 multi-signature Bitcoin vault where:
- 5 Seeds are distributed among 4 guardians and yourself
- 1 Passphrase is shared between 2 heirs and yourself
- Only by combining Seeds with the Passphrase can funds be accessed
- Recovery requires cooperation between guardians and heirs

### Core Principles
1. **Trustless Operation**: No reliance on third parties
2. **Security First**: Air-gapped operations, multiple backups
3. **Future Proof**: Designed for long-term storage
4. **Self Sovereign**: Complete control over your Bitcoin
5. **Verifiable**: All steps include verification procedures

## 1. Vault Setup

### Video Guides
Watch the detailed video guides for this section:
- [Welcome to the Course](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+1.mp4)
- [The Logic Behind Cold Storage](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+2.mp4)
- [Single Signature vs Multi Signature](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+3.mp4)
- [Signing Keys - Seeds and Passphrase](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+4.mp4)
- [Vault Setup Overview](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+5.mp4)
- [Recovery Packages Distribution](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+6.mp4)
- [The Right Setup for You](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+1+-+Lesson+7.mp4)

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

## 2. Hardware Preparation

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Hardware Preparation](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+2+-+Lesson+1.mp4)
- [Hardware Material Requirements](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+2+-+Lesson+2.mp4)
- [Seedsigner Assembly](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+2+-+Lesson+4.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+2+-+Lesson+5.mp4)

### Required Materials

#### Computing Hardware
- [ ] Dedicated laptop with charger
- [ ] USB stick for OS installation

#### Signing Devices (3 sets needed)
- [ ] Seedsigner (assembled or components)
- [ ] Micro USB cable
- [ ] Power bank
- [ ] Micro SD card

#### Metal Backup Materials
- [ ] Metal washers (150) - M8 x 24mm
- [ ] Bolts (10) - M8 x 35mm
- [ ] Nuts (10) - M8
- [ ] Letter/number stamping set
- [ ] Hammer
- [ ] Blockmit jig

#### Paper Backup Materials
- [ ] Printer
- [ ] Thermal laminator
- [ ] A5/6x9 Laminating sheets (300)
- [ ] A4/8.5x11 Paper sheets (200)
- [ ] A5/5.5x8.5 Graph paper (20)
- [ ] Pencils (2)
- [ ] Black permanent markers (2)

#### Recovery Package Materials
- [ ] A4/8.5x11 Poly mailers (10)
- [ ] A5/6x9 Black envelopes (5)
- [ ] A5/6x9 Red envelopes (3)
- [ ] A5/6x9 Yellow envelopes (7)
- [ ] A5/6x9 Green envelopes (7)
- [ ] A5/6x9 Pink/Violet envelopes (3)

### Workspace Organization

#### Online Area Setup
```
Online Area (Main Desk)
└── For following course and wallet interface
    ├── Dedicated laptop
    ├── Course materials
    └── Printer/laminator (behind laptop)
```

#### Offline Area Setup
```
Offline Area (Separate Desk)
└── For handling sensitive data
    ├── Signing device operations
    ├── Backup creation
    └── Recovery package assembly
```

## 3. Software Preparation

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Software Setup](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+1.mp4)
- [Downloading New OS](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+2.mp4)
- [Installing New OS](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+3.mp4)
- [Installing Wallet Management Interface](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+4.mp4)
- [Downloading Signing Device Firmware](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+5.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+3+-+Lesson+6.mp4)

### Operating System

#### Download Required Files
1. Download Ubuntu Desktop ISO
2. Download Balena Etcher
3. Prepare USB drive (8GB minimum)

#### Installation Steps
1. Create bootable USB with Balena Etcher
2. Boot dedicated laptop from USB
3. Install Ubuntu:
   - Choose "Erase disk and install Ubuntu"
   - Complete basic setup
   - Keep system offline when possible

### Wallet Software

#### Sparrow Wallet Installation
1. Download from sparrowwallet.com:
   - Sparrow Wallet (.deb file)
   - Manifest file
   - Manifest signature
2. Verify download integrity
3. Install using package manager
4. Configure for network connection

### Signing Device Firmware

#### Seedsigner Setup
1. Download from seedsigner.com:
   - Seedsigner firmware (Pi0 version)
   - Manifest and signature files
2. Verify firmware integrity
3. Flash firmware to SD card
4. Test device operation:
   - Insert SD card
   - Connect power
   - Verify boot sequence

## 4. Keys Generation

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Key Generation](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+1.mp4)
- [Signing Device vs Hardware Wallet](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+2.mp4)
- [Seeds Generation](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+3.mp4)
- [Passphrase Generation](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+4.mp4)
- [Adding Passphrase to Seeds](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+5.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+4+-+Lesson+6.mp4)

### Seed Generation Process

#### Required Materials
- Seedsigner
- Casino dice
- Power bank
- Temporary paper
- Permanent marker
- Graph paper for QR codes

#### Generate Each Seed
```
For each of the 5 Seeds:

1. Power on Seedsigner
2. Select "New Seed"
3. Input 50 dice rolls
4. Record temporarily:
   - Label ("Seed 1", "Seed 2", etc.)
   - 12 words
   - Fingerprint without passphrase

5. Verify Seed:
   - Delete seed from device
   - Re-enter 12 words
   - Confirm fingerprint matches

6. Create final backups:
   - Write on paper stock
   - Create QR code on graph paper
   - Mark both with "Seed X"
```

### Passphrase Generation

#### Generation Steps
```
1. Power on Seedsigner
2. Select "New Seed"
3. Input 50 dice rolls
4. Record:
   - Label as "Passphrase"
   - 12 words
5. Create 3 copies on paper stock
```

### Adding Passphrase to Seeds

#### Combine and Verify
```
For each Seed:

1. Scan Seed QR code
2. Add passphrase
3. Record on paper backup:
   - "Fingerprint with passphrase"
   - New fingerprint value
4. Clear device
5. Verify:
   - Reload Seed and Passphrase
   - Check fingerprint matches
```

## 5. Backups

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Backups](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+5+-+Lesson+1.mp4)
- [Paper Backups](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+5+-+Lesson+2.mp4)
- [Metal Backups](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+5+-+Lesson+3.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+5+-+Lesson+4.mp4)

### Paper Backups

#### Required Materials
- Laminating machine
- Laminating pouches (6x9 or A5 size)
- Paper copies of:
  - 5 Seeds (with fingerprints)
  - 5 Seed QR codes
  - 3 Passphrase copies

#### Lamination Process
```
1. Power on laminator and wait for ready signal
2. For each backup:
   - Place in laminating pouch
   - Feed through laminator
   - Allow to cool
   - Trim edges if needed

3. Verify after lamination:
   - All text is readable
   - No bubbles or defects
   - Good seal on all edges
```

### Metal Backups

#### Required Materials
- Metal washers (M8 x 24mm)
- Bolts (M8 x 35mm)
- Nuts (M8)
- Letter/number stamping set
- Hammer
- Blockmit jig

#### Creation Process
```
For Each Seed (5 total):
1. First washer:
   - Stamp "SEED X" (where X is 1-5)
   
2. Following washers:
   - Stamp word number (1-12)
   - Stamp word below number
   
3. Assembly:
   - Thread all washers onto bolt
   - Secure with nut
   - Verify all words readable

For Passphrase (3 copies):
1. First washer:
   - Stamp "PASSPHRASE"
   
2. Following washers:
   - Stamp word number (1-12)
   - Stamp word below number
   
3. Assembly:
   - Thread all washers onto bolt
   - Secure with nut
   - Verify all words readable
```

## 6. Wallet Generation

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Wallet Generation](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+6+-+Lesson+1.mp4)
- [Generating the Wallet](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+6+-+Lesson+2.mp4)
- [Wallet Descriptor Backup](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+6+-+Lesson+3.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+6+-+Lesson+4.mp4)

### Public Key Export

#### Required Materials
- Dedicated laptop with Sparrow
- Seedsigner
- Power bank
- Seed QR codes
- Passphrase backup

#### Export Process
```
For each Signing Key:
1. Power on Seedsigner
2. Scan Seed QR code
3. Verify fingerprint
4. Add passphrase
5. Verify fingerprint with passphrase
6. Export Public Key via QR
7. Scan into Sparrow
8. Label as "Seed X + Passphrase"
9. Clear device
```

### Wallet Creation

#### In Sparrow Wallet
1. Create New Wallet
2. Configure:
   - Multi-signature
   - 3-of-5 policy
   - Native Segwit
3. Import all 5 public keys
4. Create wallet

### Wallet Descriptor Backup

#### Create Backups
```
1. In Sparrow:
   - Export Wallet Descriptor
   - Save as PDF
2. Print 7 copies in A5
3. Laminate all copies
4. Verify QR codes scan correctly
```

## 7. Transactions

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Transactions](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+7+-+Lesson+1.mp4)
- [Receiving Bitcoin](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+7+-+Lesson+2.mp4)
- [Sending Bitcoin](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+7+-+Lesson+3.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+7+-+Lesson+4.mp4)

### Receiving Bitcoin

#### Generate Address
```
In Sparrow:
1. Select Receive tab
2. Click "Get Next Address"
3. Optional but recommended:
   - Verify address with Seedsigner
   - Scan address QR
   - Scan wallet descriptor
   - Confirm address belongs to wallet
4. Share address with sender
```

### Sending Bitcoin

#### Create Transaction
```
In Sparrow:
1. Select Send tab
2. Enter:
   - Recipient address
   - Amount
   - Fee rate
3. Create Transaction
4. Save unsigned transaction (PSBT)
```

#### Sign Transaction
Must collect 3 signatures using any 3 of the 5 Seeds:
```
For each signature:
1. Load Signing Key:
   - Scan Seed QR into Seedsigner
   - Verify fingerprint
   - Enter passphrase
   - Verify fingerprint with passphrase

2. Sign Transaction:
   - Show transaction QR in Sparrow
   - Scan with Seedsigner
   - Review transaction details
   - Confirm to sign
   - Scan signed transaction back

3. Clear Seedsigner

4. After 3 signatures:
   - Click Broadcast
   - Monitor transaction status
```

## 8. Recovery Packages

### Video Guides
Watch the detailed video guides for this section:
- [Introduction to Recovery Packages](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+8+-+Lesson+1.mp4)
- [Recovery Package Distribution](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+8+-+Lesson+2.mp4)
- [Recovery Instructions](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+8+-+Lesson+3.mp4)
- [Recovery Package Assembly](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+8+-+Lesson+4.mp4)
- [Section Summary](https://archive.org/details/the-bitcoin-backup-self-inheritance-protocol/Section+8+-+Lesson+5.mp4)

### Package Types

#### Guardian Package Contents
```
Guardian Package
├── Black Envelope (Seed)
│   ├── Paper backup (words + fingerprints)
│   ├── Metal backup
│   └── QR code
├── Orange Envelope (Wallet)
│   └── Wallet Descriptor
└── Green Envelope (Instructions)
    └── Recovery Instructions
```

#### Heir Package Contents
```
Heir Package
├── Red Envelope (Passphrase)
│   ├── Paper backup
│   └── Metal backup
├── Orange Envelope (Wallet)
│   └── Wallet Descriptor
├── Green Envelope (Instructions)
│   └── Recovery Instructions
└── Violet Envelope (Device)
    ├── Signing device
    ├── SD card
    └── USB cable
```

### Assembly Process

#### Prepare Envelopes
```
Label each envelope:
- Black: "Seed 1" through "Seed 5"
- Red: "Passphrase"
- Orange: "Wallet Descriptor"
- Green: "Recovery Instructions"
- Violet: "Signing Device"
```

#### Package Assembly
```
1. Verify contents match checklists
2. Insert materials into appropriate envelopes
3. Seal envelopes
4. Label outer package:
   "Property of [OWNER]
    Protected by [GUARDIAN/HEIR NAME]
    at [LOCATION]
    DO NOT OPEN without [OWNER]'s permission
    If moved, alert [OWNER] immediately"
```

### Distribution

#### Security Considerations
```
For Local Distribution:
1. Deliver packages personally
2. Explain basic responsibilities
3. Verify storage location
4. Document distribution

For International Distribution:
1. Consider metal backup creation at destination
2. Travel with paper backups only
3. Create metal backups upon arrival
4. Complete package assembly on-site
```

## Security Considerations

### Critical Security Points
1. **Workspace Security**
   - Private, lockable room
   - Separate online/offline areas
   - No cameras in offline area
   - Secure storage when paused

2. **Key Generation Security**
   - Use casino-grade dice only
   - 50 dice rolls per seed/passphrase
   - Never digitize seeds or passphrase
   - Clear devices after each use

3. **Backup Security**
   - Verify all backups immediately
   - Test QR codes scan correctly
   - Confirm fingerprints match
   - Destroy temporary materials

4. **Distribution Security**
   - Personal delivery only
   - No shipping services
   - Consider airport security with metal backups
   - Verify recipient understanding

### International Transport Notes
- Metal backups will raise security concerns at airports
- Consider creating metal backups at destination
- Travel with paper backups only when crossing borders
- Local metal backup creation recommended

## License
This protocol is released under the MIT License. See the LICENSE file for details.

## Author
[Quentin Ehrenmann -- The Bitcoin Backup]  
Website: [thebitcoinbackup.com](https://thebitcoinbackup.com)
