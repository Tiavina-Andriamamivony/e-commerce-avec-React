# E-commerce Website with Next.js 15

Modern e-commerce platform built with Next.js 15, Shadcn UI, Framer Motion, Prisma, and PostgreSQL.

## 🚀 Features

- Modern UI with Shadcn components
- Smooth animations with Framer Motion
- Type-safe database operations with Prisma
- PostgreSQL database
- Server and Client Components
- Server Actions for data mutations
- Responsive design
- Cart management
- Product catalog
- Order management

## 📋 Prerequisites

- Node.js 18+
- PostgreSQL
- npm or pnpm

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ecommerce-next
cd ecommerce-next
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Configure your `.env` file:
```
DATABASE_URL="postgresql://user:password@localhost:5432/dbname"
NEXT_PUBLIC_API_URL="http://localhost:3000"
```

5. Initialize Prisma:
```bash
npx prisma generate
npx prisma db push
```

6. Run the development server:
```bash
npm run dev
```
```

## 🔧 Tech Stack

- **Framework:** Next.js 15
- **Styling:** Tailwind CSS + Shadcn UI
- **Animation:** Framer Motion
- **Database:** PostgreSQL
- **ORM:** Prisma
- **State Management:** Zustand
- **Authentication:** NextAuth.js


## 💻 Development

### Commands

- `pnpm dev` - Start development server
- `pnpm build` - Build production bundle
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint
- `pnpm format` - Format code with Prettier

### Database Management

```bash
# Generate Prisma Client
npx prisma generate

# Push database changes
npx prisma db push

# Open Prisma Studio
npx prisma studio
```

## 🚀 Deployment

1. Create a Vercel account
2. Connect your repository
3. Set up environment variables
4. Deploy!

## 📝 License

Tiavina.co

## 👥 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request