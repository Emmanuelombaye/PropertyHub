# Smart Rent Collection System

✅ **Next.js Full Stack Monorepo** - Single codebase for frontend, backend, database, APIs and automation all in one project

## ✅ Why Next.js Single Codebase
- No separate backend/frontend services
- Built-in API Routes for backend logic
- Server Components + Client Components
- Native database integration
- One deployment process
- Type safety end-to-end
- Simplified integration & maintenance

---

## 🚀 Technology Stack
| Layer | Technology |
|-------|------------|
| Full Stack Framework | Next.js 15 (App Router) |
| Language | TypeScript |
| Database | PostgreSQL |
| ORM | Prisma |
| Authentication | NextAuth.js |
| UI | shadcn/ui + Tailwind CSS |
| Payments | M-Pesa API |
| Hosting | Vercel / Railway |

---

## 📁 Project Structure (Single Codebase)
```
smart-rent-system/
├── prisma/                  # Database Schema + Migrations
│   ├── schema.prisma
│   └── migrations/
├── src/
│   ├── app/                 # Next.js App Router
│   │   ├── api/             # Backend API Endpoints (replace separate backend)
│   │   ├── dashboard/
│   │   ├── tenants/
│   │   ├── payments/
│   │   ├── maintenance/
│   │   └── layout.tsx
│   ├── components/          # Shared UI Components
│   ├── lib/                 # Business Logic, Utilities, Actions
│   ├── types/               # TypeScript Definitions
│   └── actions/             # Server Actions
├── public/
├── package.json
└── .env
```

---

## ✅ Core Modules
- 🔐 Role Based Authentication (Tenant / Landlord / Caretaker / Admin)
- 🏠 Property & Unit Management
- 👤 Tenant Profiles with Unique System IDs
- 💸 Rent Collection + M-Pesa Integration
- 📊 Billing Engine (Rent / Utilities / Penalties)
- 🛠️ Maintenance Ticket System
- 📱 SMS / Email Notifications
- 📈 Real Time Dashboards & Reports