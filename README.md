# NinjaCash

Personal finance tracking that works offline. A progressive web app for managing income, expenses, and budgets without spreadsheets or subscriptions.

**Try it:** [ninjacash.app](https://ninjacash.app) *(Open Beta)*

## Why NinjaCash?

Most finance apps are either too complex (Firefly III) or too simple (basic expense trackers). NinjaCash sits in the middle - powerful enough to track multiple accounts and currencies, simple enough to use daily.

**Key difference:** Your data lives on your device first. Sync is optional. No account required. No subscription fees.

## Features

- **Offline-first** - Works without internet, syncs when connected
- **Multi-account** - Track checking, savings, cash, credit cards
- **Multi-currency** - THB, USD, EUR, and more
- **Quick entry** - Add transactions in seconds with the numpad interface
- **Categories & budgets** - Track spending by category, set monthly limits
- **Import from 1Money** - Migrate your existing data via CSV
- **9 dark themes** - Tokyo Night, Dracula, Nord, and more
- **PWA** - Install on phone or desktop, works like a native app

## Quick Start
```bash
git clone https://github.com/TakashiKyoto/NinjaCash.git
cd NinjaCash/apps/web
npm install
npm run dev
```

Open http://localhost:5173

## Screenshots

| Accounts | Transactions | Analytics |
|----------|--------------|-----------|
| Track all accounts at a glance | Date-grouped transaction list | Spending breakdown by category |

## Tech Stack

- **Frontend:** React 18 + TypeScript + Vite
- **Local Storage:** IndexedDB via Dexie.js
- **Backend (optional):** Hono + Prisma + PostgreSQL
- **Styling:** Custom CSS with design tokens

## Data Privacy

- All data stored locally in your browser (IndexedDB)
- Optional sync uses end-to-end encryption
- Self-hosting option for full control
- No analytics, no tracking, no ads

## Roadmap

- [ ] Recurring transactions
- [ ] Bill reminders
- [ ] Bank statement import (PDF parsing)
- [ ] Android app (via PWA)

## Author

**Takashi Kyoto** - [GitHub](https://github.com/TakashiKyoto) | [YouTube](https://youtube.com/@TakashiKyoto)

## License

MIT License - See [LICENSE](LICENSE) for details.
