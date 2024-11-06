# Software Preparation

## Required Software

### Operating System
- Ubuntu Desktop (Latest LTS Version)
- Balena Etcher for USB creation

### Wallet Software
- Sparrow Wallet (Latest Version)
- Manifests and signatures for verification

### Signing Device
- Seedsigner firmware
- Raspberry Pi Zero compatible version

## Operating System Installation

### Download Required Files
1. Download Ubuntu Desktop ISO
2. Download Balena Etcher
3. Prepare USB drive (8GB minimum)

### Create Installation USB
```bash
# Using Balena Etcher:
1. Open Balena Etcher
2. Select Ubuntu ISO file
3. Select USB drive
4. Click 'Flash'
```

### Install Ubuntu
1. Insert USB into dedicated laptop
2. Boot from USB
   - Press appropriate key during startup (usually F12 or Del)
   - Select USB from boot menu
3. Choose "Install Ubuntu"
4. Follow installation wizard:
   - Select language
   - Choose "Erase disk and install Ubuntu"
   - Set timezone
   - Create user account
5. Complete installation and restart

## Sparrow Wallet Installation

### Download and Verify
1. Download from sparrowwallet.com:
   - Sparrow Wallet (.deb file)
   - Manifest file
   - Manifest signature
2. Verify download integrity:
   ```bash
   # Open Sparrow and use built-in verification tool
   1. Click Tools > Verify Download
   2. Add downloaded files
   3. Confirm verification success
   ```

### Installation
```bash
# Install using package manager
1. Double-click .deb file
2. Click Install
3. Enter password when prompted
```

### Initial Configuration
1. Launch Sparrow Wallet
2. Choose network connection method:
   - Public server
   - Private node (if available)
3. Complete initial setup

## Seedsigner Firmware Setup

### Download Firmware
1. Visit seedsigner.com
2. Download:
   - Seedsigner firmware (Pi0 version)
   - Manifest
   - Signature

### Verify Firmware
```bash
# Using Sparrow's verification tool:
1. Open Sparrow Wallet
2. Click Tools > Verify Download
3. Add firmware files
4. Confirm verification
```

### Install Firmware
1. Insert micro SD card
2. Open Balena Etcher
3. Select Seedsigner firmware
4. Select micro SD card
5. Flash firmware
6. Wait for completion
7. Remove SD card safely

### Test Seedsigner
1. Insert micro SD card into Seedsigner
2. Connect power via micro USB
3. Verify boot sequence
4. Test basic navigation
5. Power off device

## Next Steps
1. Verify all software is working
2. Proceed to Keys Generation section
3. Keep dedicated laptop secure

## Notes
- Use only official download sources
- Always verify software signatures
- Keep system updated but stable
- Maintain offline status for Seedsigner

## Troubleshooting Common Issues

### Ubuntu Installation
```
Issue: Boot menu not appearing
Solution: Check boot key for your laptop model

Issue: Installation fails
Solution: Verify USB drive integrity
```

### Sparrow Wallet
```
Issue: Won't connect to network
Solution: Check network settings

Issue: Verification fails
Solution: Re-download files from official source
```

### Seedsigner
```
Issue: Won't boot
Solution: Re-flash SD card

Issue: Screen issues
Solution: Check connections, re-seat components
```
