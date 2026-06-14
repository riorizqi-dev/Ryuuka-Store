<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/public/assets/logos/premium-tools-hub.svg">
    <img src="/public/next.svg" alt="Premium Tools Hub" width="200">
  </picture>

  <h1 align="center">Premium Tools Hub</h1>

  <p align="center">
    A modern, feature-rich marketplace platform for digital subscriptions & license vouchers with a premium UI/UX, smooth animations, and QRIS payment integration.
    <br />
    <a href="https://github.com/riorizqi-dev/Ryuuka-Store"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#-features">Features</a>
    ·
    <a href="#-preview">Preview</a>
    ·
    <a href="#-installation">Installation</a>
    ·
    <a href="#-usage">Usage</a>
    ·
    <a href="#-project-structure">Project Structure</a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/github/stars/riorizqi-dev/Ryuuka-Store?style=for-the-badge&logo=github&color=gold" alt="Stars">
    <img src="https://img.shields.io/github/forks/riorizqi-dev/Ryuuka-Store?style=for-the-badge&logo=github&color=blue" alt="Forks">
    <img src="https://img.shields.io/github/issues/riorizqi-dev/Ryuuka-Store?style=for-the-badge&logo=github&color=red" alt="Issues">
    <img src="https://img.shields.io/github/license/riorizqi-dev/Ryuuka-Store?style=for-the-badge" alt="License">
    <br />
    <img src="https://img.shields.io/badge/Next.js-13.5.11-black?style=for-the-badge&logo=next.js" alt="Next.js">
    <img src="https://img.shields.io/badge/TypeScript-5.9.2-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript">
    <img src="https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Prisma-5.22-2D3748?style=for-the-badge&logo=prisma" alt="Prisma">
    <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite" alt="SQLite">
    <img src="https://img.shields.io/badge/Framer_Motion-11.18-0055FF?style=for-the-badge&logo=framer" alt="Framer Motion">
  </p>
</div>

---

## ✨ Features

<table>
  <tr>
    <td align="center">🏠</td>
    <td><b>Premium Landing Page</b> — Showcase sections for featured products, trust indicators, testimonials, and FAQ with smooth scroll animations.</td>
  </tr>
  <tr>
    <td align="center">🔍</td>
    <td><b>Product Catalog & Search</b> — Browse products with real-time search and category filtering (AI, Design, Productivity).</td>
  </tr>
  <tr>
    <td align="center">📦</td>
    <td><b>Product Detail</b> — View product details, select subscription plans, choose quantity, and add to checkout.</td>
  </tr>
  <tr>
    <td align="center">🛒</td>
    <td><b>4-Step Checkout Flow</b>:
      <ol>
        <li>Buyer information input</li>
        <li>Order summary review</li>
        <li>QRIS payment with 15-minute countdown timer</li>
        <li>Upload payment proof (JPG/PNG/WebP, max 3MB) → <code>WAITING_VERIFICATION</code></li>
      </ol>
    </td>
  </tr>
  <tr>
    <td align="center">📊</td>
    <td><b>Order Tracking</b> — Real-time order status updates with dedicated order detail page and history.</td>
  </tr>
  <tr>
    <td align="center">🔐</td>
    <td><b>Admin Dashboard</b>:
      <ul>
        <li>Password-protected admin login via environment variable</li>
        <li>View and manage all incoming orders</li>
        <li>Review payment proof images</li>
        <li>Update order statuses: <code>WAITING_VERIFICATION → VERIFIED → PAID → COMPLETED / REJECTED</code></li>
        <li>Add internal admin notes</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td align="center">⚙️</td>
    <td><b>Admin Settings</b> — Update QRIS payment image URL directly from the admin panel.</td>
  </tr>
  <tr>
    <td align="center">🎨</td>
    <td><b>Premium UI/UX</b> — Built with shadcn/ui components, Framer Motion animations, SplashCursor effects, border glow, and light pillar visual effects.</td>
  </tr>
  <tr>
    <td align="center">🌓</td>
    <td><b>Dark/Light Mode</b> — Seamless theme switching with <code>next-themes</code>.</td>
  </tr>
  <tr>
    <td align="center">📱</td>
    <td><b>Responsive Design</b> — Fully responsive layout optimized for desktop, tablet, and mobile devices.</td>
  </tr>
  <tr>
    <td align="center">🔔</td>
    <td><b>Toast Notifications</b> — Real-time feedback with Sonner toast notifications.</td>
  </tr>
</table>

---

## 📸 Preview

<div align="center">
  <table>
    <tr>
      <td align="center">
        <strong>🏠 Landing Page</strong><br />
        <img src="https://via.placeholder.com/400x250/1a1a2e/ffffff?text=Landing+Page" alt="Landing Page Preview" width="400" />
        <br />
        <em>Landing page with featured products, testimonials & FAQ</em>
      </td>
      <td align="center">
        <strong>🛍️ Products Page</strong><br />
        <img src="https://via.placeholder.com/400x250/16213e/ffffff?text=Products" alt="Products Page Preview" width="400" />
        <br />
        <em>Product catalog with search & category filter</em>
      </td>
    </tr>
    <tr>
      <td align="center">
        <strong>📋 Checkout Flow</strong><br />
        <img src="https://via.placeholder.com/400x250/0f3460/ffffff?text=Checkout" alt="Checkout Preview" width="400" />
        <br />
        <em>Multi-step checkout with QRIS payment</em>
      </td>
      <td align="center">
        <strong>📊 Admin Dashboard</strong><br />
        <img src="https://via.placeholder.com/400x250/1a1a2e/ffffff?text=Admin" alt="Admin Dashboard Preview" width="400" />
        <br />
        <em>Admin panel for order management & settings</em>
      </td>
    </tr>
  </table>

  <p>
    <em>💡 Replace placeholder images above with actual screenshots/GIFs of your app.</em>
  </p>
</div>

---

## 📁 Project Structure

```
premium-tools-hub/
├── prisma/                        # Database schema & seed
│   ├── schema.prisma              # Prisma schema (SQLite)
│   ├── init.sql                   # SQL initialization script
│   └── seed.js                    # Product & plan seed data
│
├── public/                        # Static assets
│   └── assets/                    # Product images & logos
│       ├── chatgpt.svg
│       ├── spotify-premium.svg
│       ├── youtube-premium.svg
│       └── logos/                 # Brand logo assets
│
├── src/                           # Application source code
│   ├── app/                       # Next.js 13 App Router
│   │   ├── (admin)/               # Admin dashboard route group
│   │   │   └── admin/             # Admin pages (orders, settings)
│   │   ├── (dashboard)/           # User dashboard route group
│   │   │   └── orders/            # User order tracking pages
│   │   ├── (site)/                # Public site route group
│   │   │   ├── page.tsx           # Landing page
│   │   │   ├── checkout/          # Checkout flow pages
│   │   │   └── products/          # Product catalog & detail pages
│   │   ├── api/                   # API routes
│   │   │   ├── admin/             # Admin API endpoints
│   │   │   ├── create-order/      # Order creation API
│   │   │   ├── orders/            # Order management API
│   │   │   └── upload-proof/      # Payment proof upload API
│   │   ├── actions.ts             # Server actions
│   │   ├── globals.css            # Global styles & Tailwind
│   │   └── layout.tsx             # Root layout with providers
│   │
│   ├── components/                # React components
│   │   ├── layout/                # Layout components
│   │   │   ├── navbar.tsx         # Navigation bar
│   │   │   └── footer.tsx         # Footer
│   │   ├── shared/                # Shared components
│   │   │   ├── product-card.tsx   # Product card component
│   │   │   ├── checkout-client.tsx # Checkout client logic
│   │   │   ├── order-status-badge.tsx
│   │   │   ├── testimonial-wall.tsx
│   │   │   └── ...                # Other shared components
│   │   └── ui/                    # shadcn/ui primitives
│   │       ├── button.tsx
│   │       ├── card.tsx
│   │       ├── dialog.tsx
│   │       ├── input.tsx
│   │       ├── select.tsx
│   │       ├── sheet.tsx
│   │       ├── tabs.tsx
│   │       └── ...
│   │
│   ├── lib/                       # Utility libraries
│   │   ├── prisma.ts              # Prisma client singleton
│   │   ├── auth.ts                # Admin authentication
│   │   ├── constants.ts           # App constants & config
│   │   ├── data.ts                # Data fetching functions
│   │   ├── utils.ts               # Utility functions
│   │   ├── validations.ts         # Zod validation schemas
│   │   └── image.ts               # Image processing utilities
│   │
│   └── types/                     # TypeScript type definitions
│       └── index.ts               # Shared types (OrderStatus, ProductCategory)
│
├── .env.example                   # Environment variables template
├── next.config.mjs                # Next.js configuration
├── tailwind.config.js             # Tailwind CSS configuration
├── tsconfig.json                  # TypeScript configuration
├── package.json                   # Dependencies & scripts
└── components.json                # shadcn/ui configuration
```

---

## ⚙️ Installation

### Prerequisites

Ensure you have the following installed:

- **Node.js** >= 18.x
- **npm** >= 9.x (or **yarn** / **pnpm**)
- **SQLite** (optional — Prisma handles it automatically)

### Step-by-step Setup

1. **Clone the repository**

```bash
git clone https://github.com/riorizqi-dev/Ryuuka-Store.git
cd Ryuuka-Store
```

2. **Install dependencies**

```bash
npm install
```

> This will automatically run `prisma generate` via the `postinstall` script.

3. **Set up environment variables**

```bash
cp .env.example .env
```

Edit the `.env` file with your configuration:

```env
# Database (SQLite — default)
DATABASE_URL="file:../dev.db"

# Admin panel password
ADMIN_PASSWORD="your-secure-admin-password"

# QRIS payment image URL (optional — can also be set via admin panel)
NEXT_PUBLIC_QRIS_IMAGE_URL=""
```

4. **Initialize the database**

```bash
# Option A: Using Prisma Migrate (recommended)
npm run prisma:migrate -- --name init

# Option B: Using SQLite directly (fallback)
sqlite3 dev.db < prisma/init.sql
```

5. **Seed the database with demo data**

```bash
npm run prisma:seed
```

6. **Start the development server**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🚀 Usage

### Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server on `localhost:3000` |
| `npm run build` | Build for production |
| `npm run start` | Start production server |
| `npm run start:3001` | Start production server on port 3001 |
| `npm run lint` | Run ESLint |
| `npm run prisma:generate` | Generate Prisma Client |
| `npm run prisma:migrate` | Run Prisma database migrations |
| `npm run prisma:seed` | Seed database with demo data |

### Routes

| Route | Description |
|-------|-------------|
| `/` | Landing page |
| `/products` | Product catalog |
| `/products/[slug]` | Product detail page |
| `/checkout` | Checkout flow |
| `/orders` | User order history |
| `/orders/[id]` | Order detail |
| `/admin` | Admin login |
| `/admin/orders` | Admin order management |
| `/admin/orders/[id]` | Admin order detail |
| `/admin/settings` | Admin settings (QRIS config) |

### Admin Access

1. Navigate to `/admin`
2. Enter the password set in `ADMIN_PASSWORD` environment variable
   - Default fallback: `admin123`
3. Manage orders: view payment proofs, update statuses, add notes
4. Configure QRIS payment image via `/admin/settings`

### QRIS Image Priority

The system determines the QRIS image source in this order:

1. **Settings.qrisImageUrl** — Set via Admin Settings panel (`/admin/settings`)
2. **NEXT_PUBLIC_QRIS_IMAGE_URL** — Environment variable
3. **Fallback** — `/assets/qris-default.svg`

---

## 🛠 Technologies Used

### Core
| Technology | Version | Purpose |
|------------|---------|---------|
| [Next.js](https://nextjs.org/) | 13.5.11 | React framework with App Router |
| [TypeScript](https://www.typescriptlang.org/) | 5.9.2 | Type-safe JavaScript |
| [React](https://react.dev/) | 18.2.0 | UI library |

### Styling & UI
| Technology | Version | Purpose |
|------------|---------|---------|
| [Tailwind CSS](https://tailwindcss.com/) | 3.4.17 | Utility-first CSS framework |
| [shadcn/ui](https://ui.shadcn.com/) | — | Reusable UI primitives (New York style) |
| [Framer Motion](https://www.framer.com/motion/) | 11.18.2 | Animation library |
| [Lucide React](https://lucide.dev/) | 0.542.0 | Icon library |
| [Radix UI](https://www.radix-ui.com/) | — | Accessible UI primitives |
| [class-variance-authority](https://cva.style/) | 0.7.1 | Component variant management |
| [tailwind-merge](https://github.com/dcastil/tailwind-merge) | 3.3.1 | Tailwind class merging |

### Backend & Database
| Technology | Version | Purpose |
|------------|---------|---------|
| [Prisma](https://www.prisma.io/) | 5.22.0 | ORM & database toolkit |
| [SQLite](https://www.sqlite.org/) | — | Database engine |
| [Zod](https://zod.dev/) | 4.1.5 | Schema validation |

### Effects & Visuals
| Technology | Version | Purpose |
|------------|---------|---------|
| [Three.js](https://threejs.org/) | 0.167.1 | 3D visual effects |
| [next-themes](https://github.com/pacocoursey/next-themes) | 0.4.6 | Dark/light mode |

### Utilities
| Technology | Purpose |
|------------|---------|
| [Sonner](https://sonner.emilkowal.ski/) | Toast notifications |
| [ESLint](https://eslint.org/) | Code linting |
| [PostCSS](https://postcss.org/) | CSS processing |
| [Autoprefixer](https://github.com/postcss/autoprefixer) | CSS vendor prefixes |

---

## 📋 Requirements

| Dependency | Minimum Version |
|------------|----------------|
| Node.js | >= 18.x |
| npm | >= 9.x |
| SQLite | Built-in (via Prisma) |

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork** the project
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines

- Follow the existing code style and conventions
- Ensure TypeScript types are properly defined
- Test your changes thoroughly
- Update documentation as needed
- Use conventional commit messages (`feat:`, `fix:`, `chore:`, etc.)

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

```
MIT License

Copyright (c) 2026 Rio Rizqi Saputra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
...
```

---

## 👨‍💻 Author

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/riorizqi-dev">
          <img src="https://avatars.githubusercontent.com/u/123456789?v=4" width="100px" style="border-radius: 50%;" alt="Author"/>
          <br />
          <sub><b>Rio Rizqi Saputra</b></sub>
        </a>
        <br />
        <a href="https://github.com/riorizqi-dev">
          <img src="https://img.shields.io/badge/GitHub-riorizqi--dev-181717?style=for-the-badge&logo=github" alt="GitHub">
        </a>
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <p>
    <strong>Premium Tools Hub</strong> — Built with ❤️ using Next.js, TypeScript & Tailwind CSS
  </p>
  <p>
    <a href="https://github.com/riorizqi-dev/Ryuuka-Store/issues">Report Bug</a>
    ·
    <a href="https://github.com/riorizqi-dev/Ryuuka-Store/issues">Request Feature</a>
  </p>
  <p>
    <sub>📝 <strong>Legal Note:</strong> All product names used in this project are placeholders (e.g., "AI Pro Plus", "Design Suite Pro", "Search AI Premium"). No actual brand logos or trademarks are used.</sub>
  </p>
</div>