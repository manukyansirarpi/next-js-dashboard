# Next.js Dashboard

A modern, responsive dashboard built with Next.js, featuring authentication, data visualization, and real-time updates.

## Features

- 🚀 Built with Next.js 14 and TypeScript
- 🔐 Authentication with NextAuth.js
- 🎨 Modern UI with Tailwind CSS
- 📊 Interactive data visualization
- 🔍 Real-time search functionality
- 📱 Fully responsive design
- 🛠️ Type-safe development with TypeScript
- 🔄 Server-side rendering (SSR) and static site generation (SSG)

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Authentication:** NextAuth.js
- **Database:** PostgreSQL (via Neon)
- **Icons:** Heroicons
- **Form Validation:** Zod
- **Utilities:** clsx, use-debounce

## Prerequisites

- Node.js 18.17 or later
- npm or yarn
- PostgreSQL database (or Neon serverless database)

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd nextjs-dashboard
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:

   - Copy `.env.example` to `.env`
   - Fill in the required environment variables

4. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server

## Project Structure

```
nextjs-dashboard/
├── app/              # Next.js app directory
├── public/           # Static assets
├── node_modules/     # Dependencies
├── .env              # Environment variables
├── .env.example      # Example environment variables
├── next.config.ts    # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
├── tsconfig.json     # TypeScript configuration
└── package.json      # Project dependencies
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [NextAuth.js Documentation](https://next-auth.js.org/)
