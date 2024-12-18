---
layout: default
title: Transactions
nav_order: 9
parent: null
has_children: false
---

## 7. Transactions

Need help with this step? [Book a free consultation](https://thebitcoinbackup.com)

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

![Transaction Signing Flowchart](https://github.com/TheBitcoinBackup/Self-Inheritance-Protocol/blob/main/assets/docs/recovery-instructions/transaction-signing-flowchart/Transaction%20Signing%20Flowchart.png)

This diagram shows the complete process of collecting three signatures from different guardians.

Must collect 3 signatures using any 3 of the 5 Signing Keys:
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
