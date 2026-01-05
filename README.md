# NinjaCash

Personal finance tracking that works offline. A progressive web app for managing income, expenses, and budgets without spreadsheets or subscriptions.

**Try it:** [ninjacash.app](https://ninjacash.app)

## Why NinjaCash?

Most finance apps are either too complex (Firefly III) or too simple (basic expense trackers). NinjaCash sits in the middle - powerful enough to track multiple accounts and currencies, simple enough to use daily.

**Key difference:** Your data lives on your device first. Sync is optional. No subscription fees for basic use.

## Features

- **Offline-first** - Works without internet, syncs when connected
- **Multi-account** - Track checking, savings, cash, credit cards
- **Multi-currency** - THB, USD, EUR, and more
- **Quick entry** - Add transactions in seconds with the numpad interface
- **Categories & budgets** - Track spending by category, set monthly limits
- **Recurring transactions** - Auto-track subscriptions and regular payments
- **Import from 1Money** - Migrate your existing data via CSV
- **9 dark themes** - Tokyo Night, Dracula, Nord, and more
- **PWA** - Install on phone or desktop, works like a native app

## Screenshots

| Accounts | Transactions | Analytics |
|----------|--------------|-----------|
| Track all accounts at a glance | Date-grouped transaction list | Spending breakdown by category |

## Tech Stack

- **Frontend:** React 18 + TypeScript + Vite
- **Local Storage:** IndexedDB via Dexie.js
- **Backend:** Hono + Prisma + PostgreSQL (hosted on Railway)
- **Hosting:** Cloudflare Pages (frontend), Railway (API)
- **Auth:** Google OAuth via Supabase

## Data Privacy

- All data stored locally in your browser (IndexedDB) by default
- Optional cloud sync uses encrypted database (AES-256)
- No ads, no selling your data
- Delete your account and all data anytime

## Roadmap

- [x] Recurring transactions
- [x] Android app (PWA - in beta)
- [ ] Bill reminders
- [ ] Budget alerts
- [ ] CSV export

## Links

- **Website:** [ninjacash.app](https://ninjacash.app)
- **Privacy Policy:** [ninjacash.app/privacy](https://ninjacash.app/privacy)
- **Terms of Service:** [ninjacash.app/terms](https://ninjacash.app/terms)

## Support

For questions or issues, email support@ninjacash.app
