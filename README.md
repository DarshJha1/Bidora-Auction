# BIDORA — Online Auction Marketplace (Frontend starter)

## Run locally
1. Install Node.js (LTS) from https://nodejs.org/
2. Extract this ZIP.
3. Open the extracted `bidora` folder in VS Code.
4. Open Terminal and run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local URL printed by Vite (usually http://localhost:5173).

## What's included
- React + TypeScript + Vite
- Responsive homepage and marketplace
- Search, category filters, sorting
- Auction detail pages
- Login and registration demonstration forms
- Buyer, seller, and admin dashboard previews
- Seller listing form preview
- Reusable auction cards and sample auction data

## Important limitations
This is a frontend starter, not a production auction platform. Sample data is stored in `src/data.ts`. Authentication, role permissions, persistent watchlists, image uploads, bid submission, auction closing, winner selection, notifications, and payments are NOT connected to a backend. Bid actions explicitly show a demo notice. Do not use it for real auctions or collect real user credentials.

## Next development milestone
Inspect and run this frontend first. Then configure Firebase Authentication, Firestore, Storage, server-side authorization, and trusted server-side bid transactions. Never allow clients to decide auction winners.
