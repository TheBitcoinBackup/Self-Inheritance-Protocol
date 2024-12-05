---
layout: default
title: Software Preparation
nav_order: 4
parent: null
has_children: false
---

## 3. Software Preparation

Need help with this step? [Book a consultation](https://thebitcoinbackup.com/services)

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

Need expert guidance for this security-critical step? [Book a consultation](https://thebitcoinbackup.com/services)

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
