# Transactions Guide

## Receiving Bitcoin

### Required Materials
- Dedicated laptop with Sparrow
- Seedsigner (for address verification)
- Wallet descriptor
- Sending wallet/address

### Generate Receiving Address
```
In Sparrow:
1. Select Receive tab
2. Click "Get Next Address"
3. New address appears with QR code
```

### Optional: Verify Address (Recommended)
```
1. In Seedsigner:
   - Power on device
   - Scan address QR from Sparrow
   - Scan wallet descriptor QR
   - Confirm address belongs to wallet

2. In Sparrow:
   - Share verified address with sender
   - Or use to send from another wallet
```

### Monitor Receipt
```
In Sparrow:
1. Watch Transactions tab
2. Wait for transaction to appear
3. Wait for confirmations
```

## Sending Bitcoin

### Required Materials
- Dedicated laptop with Sparrow
- Seedsigner
- 3 Seeds (QR codes)
- Passphrase
- Power bank

### Create Transaction
```
In Sparrow:
1. Select Send tab
2. Enter:
   - Recipient address
   - Amount
   - Fee rate
3. Click Create Transaction
4. Save unsigned transaction (PSBT)
```

### Sign Transaction
Must collect 3 signatures using any 3 of the 5 Seeds:

For each signature:
```
1. Load Signing Key:
   - Scan Seed QR into Seedsigner
   - Verify fingerprint
   - Enter passphrase
   - Verify fingerprint with passphrase

2. Sign Transaction:
   - In Sparrow: Show transaction QR
   - Scan with Seedsigner
   - Review transaction details
   - Confirm to sign
   - Scan signed transaction back to Sparrow

3. Clear Seedsigner
```

### Broadcast Transaction
```
In Sparrow:
After collecting 3 signatures:
1. Click Broadcast
2. Monitor transaction status
3. Wait for confirmations
```

## Security Notes

### Receiving
- Always verify new addresses
- Wait for confirmations
- Keep transaction records

### Sending
- Triple check recipient address
- Review transaction details carefully
- Clear signing device after each use
- Save PSBTs securely
- Remember geographic distribution of Seeds

## Common Scenarios

### Local Spending
```
If you have 3 Seeds locally:
1. Create transaction
2. Sign with 3 Seeds
3. Broadcast
```

### Distributed Signing
```
If Seeds are with guardians:
1. Create and save transaction
2. Visit Guardian 1:
   - Load transaction
   - Sign with Seed 1
   - Save partial
3. Repeat with Guardian 2 and 3
4. Broadcast final
```

## Troubleshooting

### Transaction Creation
```
Issue: Fee too low
Solution: Adjust fee rate higher

Issue: Insufficient funds
Solution: Check UTXO selection
```

### Signing
```
Issue: Wrong fingerprint
Solution: 
- Verify correct Seed
- Check passphrase entry
- Clear device and retry
```

### Broadcasting
```
Issue: Network error
Solution: 
- Check internet connection
- Retry broadcast
- Verify all signatures present
```

## Next Steps
After testing transactions:
1. Record any useful notes
2. Clear all devices
3. Secure all materials
4. Proceed to Recovery Packages

## Important Reminders
- Never keep seeds/passphrase digitally
- Always verify addresses
- Take time reviewing transactions
- Clear devices after use
