# Vault Setup Implementation Procedures

## Prerequisites
- Private workspace
- Ability to dedicate several days to setup
- Understanding of Bitcoin basics

## 1. Workspace Organization

### Online Area Setup
```
Online Area (Main Desk)
└── For following course and wallet interface
    ├── Dedicated laptop
    ├── Course materials
    └── Printer/laminator (behind laptop)
```

### Offline Area Setup
```
Offline Area (Separate Desk)
└── For handling sensitive data
    ├── Signing device operations
    ├── Backup creation
    └── Recovery package assembly
```

Verification:
- Ensure offline desk is not visible from laptop webcam
- Confirm printer/laminator placement prevents accidental capture of sensitive data
- Test workspace security by locking room when leaving

## 2. Protocol Structure

### Standard Configuration (3-of-5 Multisig)
- 5 Seeds distributed to:
  - 4 guardians
  - Owner (you)
- 1 Passphrase distributed to:
  - 2 heirs
  - Owner (you)

### Role Definitions

#### Guardians
- Hold individual Seeds
- Protect and secure recovery package
- Do not open package without permission
- Cannot access funds independently

#### Heirs
- Hold copy of Passphrase
- Can only access vault through guardian cooperation
- Receive signing device and instructions
- Cannot access funds independently

## 3. Recovery Package Types

### Guardian Package
```
Guardian Package
├── Black Envelope (Seed)
│   ├── Paper backup
│   ├── Metal backup
│   └── QR code
├── Orange Envelope (Wallet)
│   └── Wallet Descriptor
└── Green Envelope (Instructions)
    └── Recovery Instructions
```

### Heir Package
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

## 4. Setup Adaptation Guidelines

### When to Modify Setup
1. **Fewer Heirs**
   - One heir: Create single heir package
   - No changes to guardian structure

2. **Fewer Guardians**
   - Minimum: 2 guardians + owner
   - Switch to 2-of-3 multisig
   - Maintain owner as guardian

3. **More Heirs**
   - Add passphrase copy per heir
   - No changes to guardian structure

### International Distribution Considerations
- Consider metal backup creation at destination
- Plan for airport security with metal components
- Maintain package security during transit

## Next Steps
1. Proceed to Hardware Preparation section
2. Gather required materials
3. Begin setup process

## Notes
- Take time to choose guardians and heirs carefully
- Document decisions but keep information secure
- Focus on workspace setup before beginning key generation
