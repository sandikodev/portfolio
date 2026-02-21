# 🩺 Deep Technical Analysis: sandikodev Ecosystem (Feb 2026)

Laporan ini menyajikan bedah teknis mendalam terhadap 17 proyek dalam ekosistem **sandikodev** dan **PT Koneksi Jaringan Indonesia**. Laporan ini menggabungkan ringkasan teknis cepat dengan deskripsi mendalam untuk setiap proyek.

---

## 🏛️ 1. Core Meta-Frameworks & Infrastructure

### 🏔️ **1. Margin Pro**

| Kategori | Teknologi |
| :--- | :--- |
| **Runtime** | Bun |
| **Framework** | Koda Zenith (Internal Meta-Framework) |
| **UI Library** | React 19 |
| **Styling** | Tailwind CSS v4 |
| **Database** | Turso (Edge LibSQL) |
| **ORM** | Drizzle |
| **API** | Hono (RPC System) |
| **Build Tool** | Vite 6 |
| **Lokasi** | `/home/dev/project/margins-pro` |

#### **Deskripsi Tentang Margin Pro**
**Margins Pro** adalah sebuah platform SaaS (*Software as a Service*) profesional yang dirancang khusus sebagai **Intelligence Pricing System** untuk membantu para pengusaha kuliner (UMKM) mengelola aspek finansial bisnis mereka dengan lebih cerdas dan akurat.

1.  **Solusi Utama untuk Pengusaha Kuliner**: Hadir sebagai alat bantu bagi pemilik bisnis kuliner (restoran, kafe, hingga *cloud kitchen*) untuk menghitung HPP secara mendetail, mensimulasikan profit margin di GoFood/GrabFood/ShopeeFood, dan mencegah kerugian.
2.  **AI Integration**: Menggunakan **Google Gemini Flash 2.0** untuk saran optimalisasi harga secara cerdas.
3.  **Local & Cloud Sync**: Input data instan di lokal, disinkronkan ke Turso di latar belakang.
4.  **Arsitektur Tingkat Tinggi**: Dibangun di atas **Koda Zenith** dengan *Dual-Mode SSR Engine* (Resumable Mode) untuk performa tanpa _flicker_.

---

### 🏔️ **2. KodaJS (Koda Zenith Documentation)**

| Kategori | Teknologi |
| :--- | :--- |
| **Runtime** | Bun |
| **Framework** | Astro v5.x |
| **UI Visuals** | Three.js + Lenis |
| **Styling** | Tailwind CSS v4 |
| **Type Safety** | TypeScript Strict |
| **Lokasi** | `/home/dev/project/kodajs.github.io` |

#### **Deskripsi**
Landing page & pusat dokumentasi untuk meta-framework **Koda Zenith**. Menampilkan visualisasi 3D futuristik via Three.js dan _smooth scrolling_ via Lenis.

---

### 🏔️ **3. Awan (awan-kinton)**

| Kategori | Teknologi |
| :--- | :--- |
| **Runtime** | Python v3.11+ |
| **Package Mgr** | Poetry |
| **CLI Engine** | Typer & Click |
| **Integration** | Docker SDK for Python |
| **Templating** | Jinja2 + PyYAML |
| **Lokasi** | `/home/dev/web/awan` |

#### **Deskripsi**
CLI untuk manajemen platform PaaS *self-hosted*. Memudahkan operasional server, pengelolaan kontainer Docker, dan otomatisasi deployment berbasis YAML.

---

## 🎓 2. Educational & Social Platforms

### 🎓 **4. SigmaBOT Platform**

| Kategori | Teknologi |
| :--- | :--- |
| **Main Engine** | Astro 5 |
| **UI Library** | React 19 + Tailwind CSS 4 |
| **Database** | Turso (SQLite) + Drizzle ORM |
| **Auth** | Better Auth (Google OAuth) |
| **Payment** | Midtrans |
| **Email** | Resend |
| **Deployment** | Vercel |
| **Lokasi** | `/home/dev/project/sigmabots-platform` |

#### **Deskripsi**
Platform *e-learning* IoT & Robotika berbasis bundel hardware (Arduino, ESP32, Raspberry Pi). Identitas visual bergaya **Comic Book UI** yang unik.

---

### 🎓 **5. Aksesekolah.id**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Next.js 16 (App Router) |
| **Backend CMS** | Headless WordPress |
| **ORM** | Prisma |
| **Runtime** | Node.js + Vercel Edge |
| **Database** | LibSQL / PostgreSQL |
| **UI Library** | Radix UI + Tailwind CSS |
| **Lokasi** | `/home/dev/web/instances/clients/services/aksesekolah.id` |

#### **Deskripsi**
Platform _website builder_ dan sistem manajemen akademik *open-source* untuk sekolah Indonesia, menggunakan arsitektur *hybrid* Next.js + Headless WordPress.

---

### 🎓 **6. We Will Shine**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | SvelteKit 2 + Svelte 5 (Runes) |
| **Backend** | Supabase |
| **AI Mentor** | Google Gemini AI |
| **Styling** | Tailwind CSS v4 |
| **Deployment** | GitHub Pages |
| **Lokasi** | `/home/dev/web/instances/clients/services/we-will-shine` |

#### **Deskripsi**
Aplikasi bimbingan karir dan *student wellbeing* berbasis AI mentor, dibuat sebagai hadiah digital untuk siswa SMP IT Masjid Syuhada. Fitur gamifikasi, karir berbasis nilai Islam, dan AI sebagai teman bicara.

---

### 🎓 **7. Naikkelas.id**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | SvelteKit 2 + Svelte 5 |
| **Deployment** | Cloudflare Pages |
| **Database** | Turso + Drizzle ORM |
| **Content** | MDSvex (Markdown-Svelte) |
| **Utilities** | html2canvas + jsPDF |
| **Lokasi** | `/home/dev/web/instances/clients/services/naikkelas.id` |

#### **Deskripsi**
LMS modern di *Cloudflare Edge* dengan materi interaktif Markdown-Svelte dan fitur ekspor sertifikat/modul ke PDF.

---

### 🎓 **8. SMA UII Institutional Services**

| Kategori | Teknologi |
| :--- | :--- |
| **LMS Engine** | Moodle |
| **Library Sys** | SLiMS |
| **Core System** | Custom PHP/Node Server |
| **Lokasi** | `/home/dev/web/instances/smauii/services` |

#### **Deskripsi**
Ekosistem layanan digital SMA UII Yogyakarta mencakup portal akademik kustom, Moodle untuk LMS, dan SLiMS untuk perpustakaan digital.

---

## 🔬 3. Research & Data Analytics

### 🔬 **9. Citation (CORM)**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Next.js 16 + Turbopack |
| **AI SDK** | Vercel AI SDK |
| **Search Engine** | Perplexity API |
| **Vector DB** | Pinecone |
| **Database** | Turso + Drizzle |
| **Lokasi** | `/home/dev/web/citation` |

#### **Deskripsi**
Asisten riset digital dan pencari sitasi ilmiah berbasis AI untuk komunitas fisika Indonesia.

---

### 🔬 **10. Klub Fisika Indonesia**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Astro v5 + Qwik City |
| **CMS** | TinaCMS |
| **Rendering** | KaTeX + Mermaid.js |
| **Optimization** | LHCI (Lighthouse CI) |
| **Lokasi** | `/home/dev/web/instances/clients/services/klubfisika.github.io` |

#### **Deskripsi**
Portal komunitas saintifik KF13 dengan standar 100/100 Lighthouse menggunakan **Qwik Resumability** dan visual ilmiah (LaTeX, Mermaid).

---

### 🔬 **11. Kiro (Chat Analyzer)**

| Kategori | Teknologi |
| :--- | :--- |
| **Runtime** | Python v3.6+ |
| **Dependency** | Poetry |
| **Capabilities** | Metadata Extraction, Chat Merge |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/kiro` |

#### **Deskripsi**
Toolkit Python internal untuk menganalisa dan menggabungkan log chat AI dari asisten Kiro.

---

## 🎬 4. Creative & Media Studio

### 🎬 **12. Mantra AI Director Studio**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | SvelteKit 2 + Svelte 5 |
| **Runtime** | Bun |
| **AI Model** | Google Gemini Pro |
| **State Mgmt** | TanStack Svelte Query v6 |
| **Lokasi** | `/home/dev/web/instances/clients/services/mantra.studio` |

#### **Deskripsi**
Studio *AI prompt engineering* untuk pembuatan video sinematik dengan konsistensi karakter dan kontrol narasi mendalam.

---

### 🎬 **13. Pocat**

| Kategori | Teknologi |
| :--- | :--- |
| **Backend** | AdonisJS 6 (TypeScript) |
| **Frontend** | React 18 + TanStack Router |
| **Types Link** | Tuyau (Auto Type Contract) |
| **Media** | FFmpeg + yt-dlp |
| **Database** | Turso (SQLite) |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/pocat` |

#### **Deskripsi**
AI Video Clipper yang mengubah video panjang (YouTube) menjadi klip viral pendek. *Type safety* end-to-end via **Tuyau**.

---

## 🛠️ 5. Utility & Life Journey

### 🛠️ **14. Kartu Siswa Generator**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Qwik v1.x |
| **Build Tool** | Vite |
| **Styling** | Tailwind CSS |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/kartu-siswa-generator` |

---

### 🛠️ **15. SnapCode.me**

| Kategori | Teknologi |
| :--- | :--- |
| **Approach** | Buildless (No npm/vite) |
| **Tech Stack** | Pure HTML5, JS, CSS3 |
| **Container** | Docker |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/snapcode.me` |

---

### 🛠️ **16. HyperFocus**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Astro v5.6 + Starlight |
| **Hosting** | GitHub Pages |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/hyperfocus` |

#### **Deskripsi**
Dokumentasi perjalanan 10 tahun karir Sandikodev (2016–2026), menjelajahi setiap layer teknologi dari client-side hingga DevOps infrastruktur.

---

### 🛠️ **17. Portfolio (sandikodev.github.io)**

| Kategori | Teknologi |
| :--- | :--- |
| **Framework** | Astro (Hybrid Svelte) |
| **Styling** | Tailwind CSS v4 |
| **Hosting** | Netlify / GitHub Pages |
| **Lokasi** | `/home/dev/web/instances/sandikodev/services/portfolio` |

---

## 📈 Kesimpulan Ekosistem

| Aspek | Standar Minimum |
| :--- | :--- |
| **Runtime** | Bun / Node.js Edge |
| **Type-Safety** | TypeScript Strict + Hono RPC / Tuyau |
| **Database** | Turso (Edge LibSQL) |
| **Deployment** | Vercel / Cloudflare / GitHub Pages |

---
*Maintained and analyzed by Antigravity Technical Assistant.*
