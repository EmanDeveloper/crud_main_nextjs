# CRUD MongoDB with Next.js

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). It demonstrates a simple CRUD (Create, Read, Update, Delete) application using MongoDB as the database.

## Features

- Create, edit, and delete topics.
- MongoDB integration for data persistence.
- Responsive UI built with Tailwind CSS.
- Deployed on Vercel for easy hosting.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

- Node.js installed on your machine.
- A MongoDB database (local or cloud).

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd CRUD_MongoDB-main
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root of your project and add the following:

   ```env
   MONGODB_URI=<your-mongodb-connection-string>
   ```

4. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
