# Wallet Generation

## Overview
Create a 3-of-5 multisignature wallet by:
1. Creating wallet in Sparrow
2. Exporting public keys from Seeds + Passphrase
3. Combining public keys in Sparrow
4. Backing up wallet descriptor

## Required Materials

### Online Area (Laptop)
- Dedicated laptop with Sparrow
- Printer for descriptor backup

### Offline Area
- Seedsigner with firmware
- Power bank
- Seed backups (QR codes)
- Passphrase backup
- Graph paper for backups

## Wallet Creation Process

### 1. Initialize Wallet in Sparrow
```
1. Open Sparrow Wallet
2. File -> New Wallet
3. Name your wallet
4. Select "Multi-signature"
5. Configure:
   - Policy: 3 of 5
   - Script: Native Segwit
   - 5 cosigners
```

### 2. Export Public Keys
For each Signing Key (repeat 5 times):
```
Offline Area:
1. Power on Seedsigner
2. Scan Seed QR code
3. Verify fingerprint
4. Add passphrase
5. Verify fingerprint with passphrase
6. Select "Export Wallet"
7. Show QR code

Online Area:
1. In Sparrow, scan QR with laptop camera
2. Label as "Seed X + Passphrase"
3. Click Next
```

### 3. Create Wallet
```
1. Review all 5 public keys imported
2. Click Create Wallet
3. Sparrow generates wallet
4. Review wallet summary
```

## Wallet Descriptor Backup

### Create Backups
```
1. In Sparrow:
   - File -> Export Wallet
   - Select Descriptor
   - Save PDF

2. Print 7 copies:
   - Set paper size to A5
   - Print in high quality
   - Verify QR codes clear
```

### Backup Verification
```
1. In Sparrow:
   - File -> New Wallet
   - Scan descriptor QR
   - Verify wallet loads correctly
2. Delete test wallet
```

### Laminate Backups
```
1. Laminate all copies
2. Allow to cool
3. Verify QR codes still scan
4. Trim if needed
```

## Storage Organization
```
Wallet Generation Materials
├── Online Area
│   └── Sparrow Wallet configured
└── Offline Area
    ├── 7 Wallet Descriptors (laminated)
    ├── All Seed backups
    └── All Passphrase backups
```

## Next Steps
1. Test receive address generation
2. Test transaction creation
3. Prepare for recovery package assembly

## Troubleshooting

### QR Code Scanning Issues
```
If Sparrow won't scan public key QR:
1. Adjust screen brightness
2. Clean camera
3. Try different angles
4. Ensure good lighting
```

### Descriptor Issues
```
If descriptor won't scan:
1. Print new copy
2. Use higher quality settings
3. Ensure clean lamination
4. Try different lighting
```

## Important Notes
- Keep seeds/passphrase in offline area
- Clear signing device after each use
- Double-check all fingerprints
- Maintain separation of spaces
