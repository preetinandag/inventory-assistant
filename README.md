# StockSaathi — Independent Inventory Assistant & Restock Advisor

A completely standalone, offline-ready smart inventory management and reorder forecasting application for retail, FMCG, and kirana stores.

---

## 🚀 Instant View (Zero Install, Zero Server Needed)

You do **not** need to install anything, run any commands, or have internet access to use StockSaathi:
1. Go to the project folder:
   `c:\Users\JSPMUNI-HPC-45\Downloads\StockSaathi-Independent\`
2. Double-click **`index.html`** or right-click -> **Open with Google Chrome / Microsoft Edge**.
3. The entire application runs directly in your browser with 100% interactive functionality:
   - **Dashboard**: Live KPI metrics (total stock valuation in ₹, retail value, margin %, urgent alerts).
   - **Restock Advisor**: Dynamic math based on supplier lead times, safety stocks, and sales velocity.
   - **Products**: Search, filter, add, edit, and delete SKUs and inventory.
   - **Sales & Movements**: Real-time sales transactions and supplier restock ledger.
   - **Reports & Valuation**: One-click export to CSV.
   - **Local Storage**: All edits, sales, restocks, and policy changes automatically save to your browser's local storage.

---

## 🛠️ Developer Setup (React + Vite + TypeScript)

If you wish to deploy this to **Vercel**, **Netlify**, **GitHub Pages**, or customize the React code:

```bash
# 1. Install dependencies
npm install

# 2. Run local development server
npm run dev

# 3. Build for production deployment
npm run build
```

---

## 🛡️ Lovable Dependencies Removed
- ❌ No external tracking scripts (`events.js`, `lovable.js`).
- ❌ No "Edit with Lovable" banners or watermarks.
- ❌ No authentication expiration (`401 Unauthorized` preview locks).
- ❌ No external cloud server requirement.
- ✅ Fully self-hosted, offline-capable, and private.
