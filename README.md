# Bellz Beauty & Nailz

Next.js 14 (App Router) front end. Deploys on Vercel. Supabase and Stripe come next.

## Run it locally
```bash
npm install
npm run dev     # http://localhost:3000
```

## Put it on GitHub + Vercel
1. Copy these files into your GitHub repo and push to `main`.
2. In Vercel, import the repo. Framework is detected as Next.js. Click Deploy.

## What is placeholder right now
- `lib/data.js`: sample sets and prices (replace with Isabella's real list)
- `components/NailSvg.js`: drawn nails standing in for real photos
- `components/Header.js`: text logo (swap for the logo image in `public/img/`)
- `app/about/page.js`: photo placeholder
- `public/img/*.jpg`: reference images for the leopard and lace look. Replace with images you own or have licensed before launch.

## Next up (not built yet)
- Supabase: `products`, `orders`, `order_items`, `messages` tables; Storage buckets for gallery, sizing photos, custom inspiration uploads
- Stripe: Checkout session from the cart, webhook to save paid orders, shipping at checkout
- Contact form: POST to `/api/contact`
- Required sizing photo (hand + quarter) step in checkout
- `.env.example` lists the keys to add in Vercel
