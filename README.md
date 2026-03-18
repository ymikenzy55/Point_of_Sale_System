
  # Point of Sale System

A modern, full-featured Point of Sale (POS) system built with React, TypeScript, and Vite. Designed for retail businesses with role-based access control, inventory management, and comprehensive sales tracking.

## 🚀 Features

### Core Functionality
- **Role-Based Access Control**: Admin, Manager, and Cashier roles with different permissions
- **Dashboard**: Real-time overview of today's sales, top products, and low stock alerts
- **Point of Sale**: Fast checkout with barcode scanning, multiple payment methods
- **Inventory Management**: Product CRUD with image upload, search, and pagination
- **Customer Management**: Track customer information and purchase history
- **Transaction History**: Complete sales records with date filtering and daily totals
- **Settings**: Admin panel for user management

### Key Features
- ✅ Clickable dashboard cards for quick navigation
- ✅ Pagination (15 items per page) on all list pages
- ✅ Real-time search functionality
- ✅ Date filtering with daily sales summaries
- ✅ Out of stock indicators
- ✅ Customer information collection at checkout
- ✅ Invoice generation and printing
- ✅ Confirmation dialogs for critical actions
- ✅ Mobile responsive design
- ✅ Ghana Cedi (GH₵) currency support

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI + shadcn/ui
- **State Management**: React Context API
- **HTTP Client**: Axios
- **Date Handling**: date-fns
- **Icons**: Lucide React
- **Notifications**: Sonner

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ymikenzy55/Point_of_Sale_System.git
cd Point_of_Sale_System
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
```bash
cp .env.example .env
```

Edit `.env` and configure your API URL:
```env
VITE_API_URL=http://localhost:3000/api
```

### 4. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 🔐 Demo Credentials

### Admin (Full Access)
- Email: `admin@store.com`
- Password: `admin123`

### Manager
- Email: `alice@store.com`
- Password: `manager123`

### Cashier
- Email: `bob@store.com`
- Password: `cashier123`

## 📁 Project Structure

```
Point_of_Sale_System/
├── src/
│   ├── app/
│   │   ├── components/       # Reusable components
│   │   │   ├── pos/         # POS-specific components
│   │   │   └── ui/          # UI library components
│   │   ├── pages/           # Page components
│   │   ├── services/        # API services
│   │   ├── App.tsx          # Main app component
│   │   ├── StoreContext.tsx # Global state management
│   │   └── types.ts         # TypeScript types
│   ├── styles/              # Global styles
│   └── main.tsx             # App entry point
├── .env.example             # Environment variables template
├── .gitignore              # Git ignore rules
└── package.json            # Dependencies and scripts
```

## 🔌 API Integration

The application is ready for backend integration. API service is configured in `src/app/services/api.ts` with all endpoints defined.

See [API_INTEGRATION.md](./API_INTEGRATION.md) for complete API documentation.

## 📱 Pages Overview

### Dashboard
- Today's revenue, orders, and items sold
- Top 5 selling products
- Low stock alerts
- Recent transactions
- Clickable cards for quick navigation

### Point of Sale (POS)
- Product search and barcode scanning
- Shopping cart management
- Multiple payment methods (Cash, Card, Mobile Money)
- Customer information collection
- Invoice generation

### Inventory
- Add/Edit/Delete products
- Image upload for products
- Real-time search
- Pagination (15 items per page)
- Out of stock indicators
- Stock level management

### Customers
- Customer list with purchase history
- Total purchases tracking
- Pagination support
- Search functionality

### History
- Complete transaction records
- Date filtering
- Daily sales summaries
- Customer information display
- Invoice reprinting

### Settings (Admin Only)
- User management
- Role assignment
- Activate/Deactivate users
- Delete users

## 🎨 Design Features

- Clean, professional UI with brown/beige color scheme
- Mobile-first responsive design
- Smooth animations and transitions
- Confirmation dialogs for critical actions
- Toast notifications for user feedback
- Accessible components (ARIA compliant)

## 🔒 Security Features

- Role-based access control
- Protected routes
- Token-based authentication (ready for backend)
- Input validation
- Confirmation dialogs for destructive actions

## 📦 Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist/` directory.

## 🧪 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**ymikenzy55**
- GitHub: [@ymikenzy55](https://github.com/ymikenzy55)

## 🙏 Acknowledgments

- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Icons from [Lucide](https://lucide.dev/)
- Design inspiration from modern POS systems

## 📞 Support

For support, email or open an issue in the GitHub repository.

---

Made with ❤️ for retail businesses

  This is a code bundle for Point of Sale System. The original project is available at https://www.figma.com/design/lzy3Hyuff21X5Zp0uTAuwx/Point-of-Sale-System.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.
  