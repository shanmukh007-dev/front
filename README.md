# AutoPulse VSM — Frontend Application

Modern React single-page frontend for the AutoPulse Vehicle Service Management system, built with **React 19**, **TypeScript**, **Vite**, **Tailwind CSS**, and **TanStack Query**.

---

## 🛠️ Tech Stack

* **Framework:** React 19 + TypeScript + Vite
* **Styling:** Tailwind CSS + Radix UI components
* **Icons:** Lucide React
* **Data Fetching:** TanStack Query (React Query v5)
* **Charts:** Recharts

---

## 🚀 Local Development

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the local dev server:**
   ```bash
   npm run dev
   ```
   The application runs at **http://localhost:3000**.
   Vite automatically proxies all `/api/*` calls to the backend on `http://localhost:8080`.

3. **Build for production:**
   ```bash
   npm run build
   ```
   The compiled bundle will be generated in `dist/`.

---

## ☁️ Deployment (Render.com / Vercel / Netlify)

### Option 1: Render.com (Static Site)
* **Build Command:** `npm install && npm run build`
* **Publish Directory:** `dist`
* **Environment Variable:**
  * `VITE_API_BASE_URL`: URL of your deployed backend (e.g., `https://autopulse-vsm-backend.onrender.com`)

### Option 2: 1-Click via `render.yaml`
Render will automatically detect [`render.yaml`](./render.yaml) and configure the build command and publish path.

---

## 🔑 Demo Login Accounts

* **Staff Workshop:** `staff@autovsm.com` / `password123`
* **Customer Portal:** `customer@autovsm.com` / `password123`
