# RE:WEAR — frontend prototype

React + Vite frontend for a circular-fashion marketplace:
- Resell pre-loved clothing.
- Exchange clothes with other community members.
- Fabric Revival: list damaged/unwanted clothes for tailor purchase offers.
- Tailor Studio: discover independent makers.
- Garment Life Advisor: rule-based guidance for a garment's next life.

## Run locally
Requires Node.js 18+ (Node 20+ recommended).

```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. In Vercel choose Add New → Project and import the repository.
3. Use build command `npm run build` and output directory `dist`.
4. Deploy. `vercel.json` includes an SPA rewrite for client-side navigation.

## Demo limitations
This is frontend-only. Listings, cart, wishlist and fabric/swaps are stored in browser localStorage. Offers and swap proposals are simulated locally and are not shared with other users. There is no real authentication, database, image upload service, payment processing, or messaging. Images load from Unsplash and need internet access. For a real marketplace, add a backend, database, authentication, secure offer workflows, image storage, moderation and payments.
