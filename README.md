# Socially - Social Media Application

A modern social media application built with Next.js, Clerk, Prisma, and TypeScript.

Live Demo: [https://socially-a7mdmo74.vercel.app/](https://socially-a7mdmo74.vercel.app/)

## Features

- User authentication with Clerk
- Real-time updates
- Image uploads with UploadThing
- Dark/Light theme support
- Responsive design
- Database management with Prisma and Neon

## Tech Stack

- **Frontend**: Next.js 14, React 18, TailwindCSS
- **Authentication**: Clerk
- **Database**: Neon (Serverless Postgres)
- **ORM**: Prisma
- **Styling**: Radix UI, TailwindCSS
- **File Upload**: UploadThing
- **Date Handling**: date-fns
- **Icons**: Lucide React

## Getting Started

1. Clone the repository
2. Install dependencies:

npm install

3. Set up environment variables:

# Create a .env file and add your credentials

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=postgresql://user:password@neon.tech/database
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

4. Run database migrations:

npx prisma generate
npx prisma db push

5. Start the development server:

npm run dev

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run linting
- `npm run postinstall` - Generate Prisma client

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
