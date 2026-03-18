# Point of Sale System

A modern POS system built with React and TypeScript for retail businesses.

## Features

- Role-based access (Admin, Manager, Cashier)
- Real-time dashboard with sales overview
- Inventory management with search and pagination
- Customer tracking and transaction history
- Invoice generation
- Mobile responsive

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## Demo Credentials

**Admin**
- Email: admin@store.com
- Password: admin123

**Manager**
- Email: alice@store.com
- Password: manager123

**Cashier**
- Email: bob@store.com
- Password: cashier123

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ymikenzy55/Point_of_Sale_System)

Or manually:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

When backend is ready, add environment variable in Vercel dashboard:
- `VITE_API_URL` = your Render backend URL

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS
- Radix UI

## Build

```bash
npm run build
```

## License

MIT
