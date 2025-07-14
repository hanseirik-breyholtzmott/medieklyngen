# Medieklyngen (Media Cluster Norway) 🌐

[![Website](https://img.shields.io/badge/Visit-Medieklyngen-blue?style=for-the-badge&logo=google-chrome)](https://www.medieklyngen.no)

A modern, dynamic, and responsive website built with **Next.js**, **Sanity**, and **TailwindCSS** — showcasing Medieklyngen: a Norwegian media-tech cluster and member organization driving innovation in media.

📍 Based in Bergen, Medieklyngen operates from the heart of Media City Bergen — Norway’s national media and mediatech hub — bringing together over 100 member organizations, including universities, research institutions, media-tech companies, and newsrooms.

---

## 🚀 Features

- **Dynamic page builder with drag‑and‑drop via Sanity Visual Editing**  
  Admins can add, remove, and reorder content blocks directly on the live page, with intuitive in-context editing powered by Sanity’s Visual Editing.

- **Array-based modular content system**  
  Sanity schemas are designed with arrays of customizable section blocks (e.g. hero, features, testimonials, calls to action), making page layouts fully flexible.

- **Hybrid rendering with Next.js**  
  - **Server-Side Rendering (SSR)** for dynamic previews and real-time content editing  
  - **Static-Site Generation (SSG)** for production-ready, performant delivery

- **Sanity headless CMS** for managing:
  - News articles
  - Events
  - Member listings
  - Job openings
  - Fully customizable page sections

- **TailwindCSS** for modern, responsive, utility-first styling

- **SEO-friendly markup** and best practices throughout

- **Contact form** that routes submissions to `post@medieklyngen.no`

- **Multi-page structure**:
  - Home
  - News
  - Events
  - Members
  - Job Openings
  - Contact
  - Project Reynir

---

## 📦 Tech Stack

- **Next.js** – React framework for SSR/SSG and routing
- **Sanity** – Headless CMS with Visual Editing
- **TailwindCSS** – Utility-first CSS framework
- **Vercel** (or equivalent) – Deployment platform
- **Optional**: Cloudflare (DNS/CDN), Prisma, MongoDB, Firebase, Supabase

---

## 🛠 Getting Started

### Prerequisites

- Node.js ≥ 16
- npm or yarn
- (Optional) Sanity CLI:  
  ```bash
  npm install -g @sanity/cli
