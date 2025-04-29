# Byte & Dine

A modern restaurant ordering system that allows customers to browse the menu, place orders, and track their order status - all without creating an account.

## Features

- 📋 **Digital Menu**: Browse through categorized menu items with images, descriptions, and prices  
- 🧾 **No-Login Ordering**: Place orders with just your name and table number  
- 🔄 **Real-Time Updates**: Receive instant updates on order status  
- 🛠️ **Admin Dashboard**: Manage menu items, track orders, and generate QR flyers  
- 📱 **QR Code Generation**: Create custom QR flyers for your restaurant  
- 🌗 **Light/Dark Mode**: Toggle between light and dark themes  

## Tech Stack

- **Frontend**: React + Vite
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Database**: Supabase
- **Animations**: Framer Motion
- **QR Generation**: react-qr-code
- **Notifications**: react-hot-toast

## Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn
- Supabase account

### Setup

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file in the root directory with your Supabase credentials:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```
4. Run the development server:
   ```
   npm run dev
   ```

### Supabase Setup

1. Create a new Supabase project
2. Run the SQL migration in `supabase/migrations/create_tables.sql`
3. Enable Row Level Security (RLS) on all tables
4. Configure storage buckets for menu item images

## Admin Access

To access the admin panel, navigate to `/admin/login` and use the password:

```
Dammy@$$2002$$
```

## License

This project is licensed under the MIT License.

## Created By

Crafted with care by Irewole Daramola | Powered by DammyTechHub