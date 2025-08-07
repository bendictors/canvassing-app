# Canvassing — Verifiable Task Platform for Africa

Canvassing is a mobile-first task and survey platform powered by zkTLS and XION SDK. It connects web3 users in Africa with research tasks and pays users in stablecoins upon verified completion.

## Overview
- Mobile app built for low-end devices
- Integrates zkTLS for zero-knowledge proof verification
- Uses XION (Dave SDK) to store on-chain proofs
- Pays in stablecoins: GoodDollar, cUSD, USDC, USDT
- Wallet integration with MiniPay

## Features
- Task discovery & instructions
- Verifiable task completion
- On-chain proof of activity
- Activity history
- Achievements & daily streaks
- MiniPay wallet connection
- Secure payouts & referral tracking
  
## How Features Work

Once users sign up, they can browse available tasks on the Earn page, each showing details like the reward amount, time required, and instructions. After completing a task, users earn instantly and their activity is logged in the Activity page, where they can track tasks completed, earnings received, and referrals made. 

The app also features a MiniPay-style wallet, where users can withdraw their stablecoin earnings such as cUSD, USDC, G$, or USDT — directly to their wallets with zero gas fees. To make the experience engaging, Canvassing includes a gamified Milestones section where users unlock badges, complete daily streaks, and build a reputation over time. There’s also a referral program with automated tracking and bonus rewards once invited friends complete profiles and connect wallets.

### The Trust Layer — zkTLS Integration 

To ensure that every task completed is authentic and secure, Canvassing uses zkTLS — a privacy-preserving verification technology. zkTLS allows the app to prove that a user completed a task — such as filling out a survey — without revealing their answers or personal data. This means the app can cryptographically confirm a user’s action happened securely, in the correct environment, and only once, preventing fraud or repeated submissions. Every task shown in the Activity page includes a tag like “Verified with zkTLS,” making the proof process visible and reinforcing trust between users and researchers.

### The Infrastructure — XION SDK (Dave) Integration
After a task is verified with zkTLS, Canvassing uses the XION SDK (Dave) to package that proof and store it on-chain. This creates a transparent, tamper-proof, and decentralized record of every verified task and payout. For users, this means their work is publicly and immutably recorded. For researchers and stakeholders, it ensures that every data point is backed by cryptographic truth. Whether it's a survey completed or a payout claimed, XION ensures that nothing can be faked, edited, or deleted.



## Demo
- [Demo Video on YouTube](https://youtu.be/Li9LIXWcyjw)
- [Prototype](https://www.figma.com/proto/EuTIr7lXngLJRq63EMDqt6/Projects?node-id=519-3393&t=XVPTS8Lqb9fAJvxA-1)

## Tech Stack
- Figma (UI/UX)
- zkTLS (Verification)
- XION Dave SDK (On-chain Proofs)
- MiniPay (Wallet integration)
- Stablecoins: G$, cUSD, USDC

## 📁 Files
- `/docs` → pitch deck, full proposal
- `/screens` → app UI screenshots
- `README.md` → overview

## 👥 Team
- Benedictors Ogada (Design) – [LinkedIn](https://www.linkedin.com/in/benedictors-ogada-9b905b16a/)
