# LDMS - Logistics Delivery Management System

A comprehensive logistics and delivery management platform built with Next.js, TypeScript, and Tailwind CSS. LDMS streamlines the entire logistics operation with powerful tools for administrators, drivers, warehouse staff, and customers.

![LDMS Dashboard](public/images/logistics-hero.png)

## 🚀 Features

### 📊 **Real-time Analytics**
- Comprehensive dashboards for different user roles
- Delivery performance tracking
- Driver efficiency monitoring
- Warehouse operations insights
- Export reports in multiple formats
- Scheduled automated reporting

### 👥 **Multi-Role Management**
- **Admin Dashboard**: Complete system oversight and management
- **Driver Portal**: Assignment tracking, delivery management, earnings overview
- **Warehouse Interface**: Inventory management, pickup tracking, scanning tools
- **Customer Portal**: Order tracking and delivery status updates

### 📱 **Mobile-First Design**
- Responsive design that works on all devices
- Progressive Web App capabilities
- Mobile-optimized interfaces for drivers and warehouse staff

### 🔒 **Security & Authentication**
- JWT-based authentication
- Role-based access control
- Secure password reset functionality
- Protected routes and API endpoints

### 📦 **Order & Inventory Management**
- Real-time order tracking
- Inventory status monitoring
- Proof of delivery (POD) capture
- Issue reporting and resolution
- Barcode/QR code scanning

### 🗺️ **Location & Mapping**
- Real-time GPS tracking
- Route optimization
- Delivery mapping and visualization
- Location-based notifications

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/) + [shadcn/ui](https://ui.shadcn.com/)
- **Forms**: [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
- **State Management**: React Hooks
- **Authentication**: JWT Tokens
- **Icons**: [Lucide React](https://lucide.dev/)
- **Charts**: [Recharts](https://recharts.org/)
- **Package Manager**: [pnpm](https://pnpm.io/)

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 18 or higher)
- **pnpm** (recommended) or npm/yarn
- **Git**

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ldms-frontend.git
cd ldms-frontend
```

### 2. Install dependencies

```bash
pnpm install
```

### 3. Environment Setup

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_API_BASE_URL=your_backend_api_url
NEXT_PUBLIC_MAPS_API_KEY=your_maps_api_key
```

### 4. Run the development server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

### 5. Build for production

```bash
pnpm build
pnpm start
```

## 📁 Project Structure

```
ldms-frontend/
├── app/                    # Next.js App Router pages
│   ├── admin/             # Admin dashboard pages
│   ├── auth/              # Authentication pages
│   ├── customer/          # Customer portal pages
│   ├── driver/            # Driver dashboard pages
│   ├── warehouse/         # Warehouse interface pages
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Landing page
├── components/            # Reusable React components
│   ├── ui/               # shadcn/ui components
│   ├── dashboard-layout.tsx
│   ├── map-view.tsx
│   └── ...
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
├── styles/               # Global styles
└── ...
```

## 🔐 User Roles & Access

### Admin
- Complete system oversight
- User management
- Driver assignment
- Inventory control
- Reports and analytics
- System configuration

### Driver
- View assigned deliveries
- Update delivery status
- Capture proof of delivery
- Report issues
- Track earnings
- Navigation assistance

### Warehouse Staff
- Inventory management
- Package scanning
- Pickup scheduling
- Issue reporting
- Status updates

### Customer
- Order tracking
- Delivery notifications
- Issue reporting
- Order history

## 🛡️ API Integration

The frontend communicates with a backend API for all data operations. Key endpoints include:

- `/auth/*` - Authentication and authorization
- `/admin/*` - Administrative functions
- `/driver/*` - Driver-specific operations
- `/warehouse/*` - Warehouse management
- `/orders/*` - Order management
- `/tracking/*` - Real-time tracking

## 📱 Mobile Features

- **Camera Integration**: Capture proof of delivery photos
- **QR/Barcode Scanning**: Quick package identification
- **GPS Tracking**: Real-time location updates
- **Offline Capability**: Basic functionality without internet
- **Push Notifications**: Delivery updates and alerts

## 🎨 UI/UX Features

- **Dark/Light Mode**: Theme switching capability
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Accessibility**: WCAG compliant components
- **Loading States**: Skeleton loaders and progress indicators
- **Error Handling**: User-friendly error messages
- **Form Validation**: Real-time validation with helpful messages

## 🔧 Development

### Available Scripts

```bash
# Start development server
pnpm dev

# Build for production
pnpm build

# Start production server
pnpm start

# Run linting
pnpm lint

# Type checking
npx tsc --noEmit
```

### Code Style

This project uses:
- ESLint for code linting
- TypeScript for type safety
- Prettier for code formatting (recommended)

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Configure environment variables
4. Deploy automatically

### Other Platforms

The app can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- Heroku

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) team for the amazing framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Radix UI](https://www.radix-ui.com/) for accessible component primitives
- [shadcn/ui](https://ui.shadcn.com/) for beautiful, reusable components
- [Lucide](https://lucide.dev/) for the comprehensive icon library

---

**Made with ❤️ by the Company C LDMS Team**
