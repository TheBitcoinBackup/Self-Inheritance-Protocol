---
layout: default
title: Wallet Generation
nav_order: 8
parent: null
has_children: false
---

## 6. Wallet Generation

Need help with this step? [Book a consultation](https://thebitcoinbackup.com/services)

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

![Multi-Signature Structure](/Self-Inheritance-Protocol/assets/images/multisig-structure.png)

This diagram shows how the Public Keys combine to create the Multi-Signature Wallet Descriptor.

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
