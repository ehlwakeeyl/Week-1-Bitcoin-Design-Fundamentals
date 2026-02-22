# Onboarding User Flows  
## Strike vs BlueWallet vs Zeus

---

# Strike Onboarding User Flow  
(Entity: Strike)

## New User Flow (Sign Up Path)

Launch App  
↓  
Welcome Screen  
- Login  
- Sign Up  
↓  
Enter Phone/Email  
↓  
OTP Verification  
↓  
Enter Personal Details  
↓  
Create PIN  
↓  
Set Up 2FA (Authenticator)  
↓  
Save Recovery Codes  
↓  
Start KYC  
    ├─ Upload ID  
    ├─ Selfie Verification  
    └─ Address Details  
↓  
Verification Processing  
↓  
Access Dashboard  
- Send  
- Receive  
- Add Funds  

---

## Returning User Flow

Launch App  
↓  
Enter PIN  
↓  
Mandatory 2FA  
↓  
Access Dashboard  

---

# BlueWallet Onboarding User Flow  
(Entity: BlueWallet)

## First-Time User Flow

Launch App  
↓  
Add Wallet Screen  
↓  
Tap “Add Wallet”  
↓  
Choose Wallet Type  
    ├─ Bitcoin (On-chain)  
    └─ Lightning  
↓  

### If Bitcoin (On-Chain) Selected:
Generate Wallet  
↓  
Display 12/24 Word Seed Phrase  
↓  
User Confirms Backup  
↓  
Wallet Created  
↓  
Dashboard  

---

### If Lightning Selected:
Create Lightning Wallet  
↓  
(Optionally custodial unless connecting own node)  
↓  
Wallet Created  
↓  
Dashboard  

---

## Existing User Flow (Import Wallet)

Launch App  
↓  
Add Wallet  
↓  
Import Wallet  
↓  
Enter Seed Phrase  
↓  
Wallet Restored  
↓  
Dashboard  

---

# Zeus Wallet Onboarding User Flow  
(Entity: Zeus Wallet)

## First-Time Launch

Launch App  
↓  
Intro Slides (Lightning Education)  
    ├─ Slide 1  
    ├─ Slide 2  
    └─ Slide 3  
↓  
Main Entry Screen (4 CTAs)  
    ├─ Quick Start  
    ├─ Advanced Setup  
    ├─ Connect Existing Node  
    └─ Other Options  
↓  

---

## Quick Start Path

Select Quick Start  
↓  
Create New Wallet  
↓  
Generate Seed Phrase  
↓  
Confirm Backup  
↓  
Begin Node Setup  
↓  
Sync Process (Loading Node Data)  
↓  
Access Lightning Dashboard  

---

## Advanced Setup Path

Select Advanced Setup  
↓  
Manual Configuration  
    ├─ Node Connection Details  
    ├─ Host/IP  
    ├─ Macaroon / Credentials  
↓  
Authenticate Node  
↓  
Sync Node  
↓  
Access Lightning Dashboard  

---

## Connect Existing Node Path

Select Connect Existing Node  
↓  
Enter Node Credentials  
↓  
Verify Connection  
↓  
Sync  
↓  
Access Dashboard  

---

# Complexity Comparison

| Wallet | Steps to Access Wallet | Primary Complexity Source |
|--------|------------------------|---------------------------|
| Strike | Medium | KYC + 2FA |
| BlueWallet | Short | Seed phrase responsibility |
| Zeus | Long | Node setup + Lightning sync |

---

Each onboarding flow reflects the technical depth of its intended audience.