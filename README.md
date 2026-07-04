<div align="center">

# 🌍 WorldVision

**An interactive 3D globe to explore the world and plan your next trip.**

Discover *where* to travel — filter 247 countries by climate, safety and season, and watch matching destinations light up in real time on a rotating 3D globe.

[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-Postgres%20%2B%20Auth-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)
[![Three.js](https://img.shields.io/badge/Three.js-3D-000000?logo=three.js&logoColor=white)](https://threejs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

### 👉 [**Try the live app**](https://worldvision-eta.vercel.app) 👈

</div>

---

## 📸 Preview

<!--
  ADD YOUR SCREENSHOTS HERE.
  Easiest way: edit this file on GitHub (pencil ✏️), then drag & drop your
  images right into the editor — GitHub uploads them and inserts the links.
  Great shots to include: the 3D globe, the filters + a country card,
  the "My World" visited-countries globe, the thematic color layers.
-->

| Interactive globe | Country details | My World |
|:---:|:---:|:---:|
| _screenshot_ | _screenshot_ | _screenshot_ |

---

## ✨ What it does

- **🌐 Interactive 3D globe** — rotate, zoom and click any of 247 countries (Three.js).
- **🔍 Smart destination filters** — search by climate, safety index, landscape type and travel month; matching countries highlight live on the globe.
- **🗺️ Thematic map layers** — recolor the globe by monthly climate, safety, or dominant landscape.
- **🛫 Flight planning** — build and save flight plans with live prices (Amadeus API).
- **📍 "My World"** — mark visited countries, build a wishlist, and share your *"% of the world visited"* stat.
- **🤖 AI country descriptions** — pre-generated offline and stored in the database, so pages load instantly with zero AI cost at runtime.
- **🌍 Multilingual** — full UI in 9 languages (IT, EN, ES, FR, DE, PT, RU, ZH, AR).
- **🔐 Full auth** — sign-up, password reset, profile management and an admin analytics dashboard.

## 🛠️ Built with

| Layer | Technologies |
|-------|--------------|
| **Framework** | Next.js 14 (App Router), React 18, TypeScript |
| **Styling** | Tailwind CSS, shadcn/ui |
| **3D & data viz** | Three.js, D3, TopoJSON, Recharts |
| **Backend** | Supabase (PostgreSQL, Auth, Row Level Security) |
| **APIs** | Amadeus (flights), REST Countries, Travelpayouts |
| **Deployment** | Vercel |

## 🏗️ Engineering highlights

- **Security-first data model** — every user table is protected by Supabase **Row Level Security**, so users can only ever read and write their own data. Privileged keys live only in server-side API routes, never in the browser.
- **No AI at runtime** — country descriptions and translations are generated **offline** and cached in the database → instant loads, near-zero running cost.
- **Server-side secrets** — all third-party API calls run through Next.js API routes, keeping credentials off the client.
- **Performance** — a single 3D scene renders 247 interactive country meshes with smooth zoom, pan and highlight.

## 💡 The idea

Booking sites let you *book*, but not *discover*. WorldVision flips the flow: you start from a **visual, exploratory** experience — spin the globe, filter by what matters to you (weather, safety, vibe), and only then decide where to go. Free for users, monetized through travel affiliate partnerships.

---

## 🔒 Source code

This is a **live commercial project**, so the source code is kept in a **private repository**.
Recruiters or collaborators: I'm happy to grant access on request — just reach out.

<div align="center">

**[🔗 Live app](https://worldvision-eta.vercel.app)** · Built by [@mvsa7](https://github.com/mvsa7)

</div>
