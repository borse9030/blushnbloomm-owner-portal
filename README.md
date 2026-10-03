# Bloom&blush — Owner Studio Portal

Exclusive, private management dashboard for **Bloom&blush Boutique Gifting & Floral Studio** (Siddhi Kokate, Pimpri-Chinchwad, Pune).

---

## 🌸 Key Capabilities

- **Catalog & Product Management**:
  - Add, edit, duplicate, and delete handcrafted creations.
  - Optional base price with Indian Currency (`₹`) auto-formatting.
  - Automatic fallback to **"Price on Request"** for bespoke custom orders.
  - Multi-tag customization options and suitable celebration occasions.
- **Collection Management**:
  - Curate the 6 core luxury collections (*Money Garlands, Artisanal Bouquets, Customized Hampers, Wedding Gifting, Customized Keepsakes, Luxury Add-ons*).
- **Studio Achievements & Milestones**:
  - Showcase high-profile offerings (e.g., Lalbaugcha Raja Ceremonial Garlands, royal trousseau orders).
  - Support for both image and video showcase cards.
- **Real-Time Cloud Synchronization**:
  - Real-time two-way synchronization via **Google Firebase Firestore**.
  - Direct repository sync to the customer website catalog (`borse9030/blushnbloomm`).
  - Offline-first cache with browser `localStorage`.
- **Media Asset Management**:
  - Cloudflare R2 S3-compatible cloud storage integration.
  - Direct upload or external link support with live preview.

---

## 🚀 Running Locally

1. Open a terminal in this directory:
   ```bash
   cd blushnbloomm-owner-portal
   ```
2. Start the local server:
   ```bash
   npm start
   ```
3. Open your browser and navigate to:
   [http://localhost:3001](http://localhost:3001)

---

## 🌐 Deploying to Vercel

1. Push your changes to this repository.
2. In [Vercel Dashboard](https://vercel.com), import `borse9030/blushnbloomm-owner-portal`.
3. Framework Preset: **Other**. Root Directory: `./`.
4. Deploy! The portal will be live on your custom domain or Vercel subdomain with automatic HTTPS and `noindex` privacy headers.

---

## 🔐 Security & Access Control

- This repository is set to **Private** to protect studio pricing workflows, direct Firebase configuration, and proprietary curation tools.
- HTTP security headers enforce `X-Robots-Tag: noindex, nofollow` to prevent search engine indexing.

---

*Handcrafted for Siddhi Kokate • Bloom&blush Studio, Pune*
