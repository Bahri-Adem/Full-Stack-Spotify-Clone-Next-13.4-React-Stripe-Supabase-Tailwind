# Full Stack Spotify Clone

A full-stack Spotify clone built with Next.js, React, Stripe, Supabase, PostgreSQL, and Tailwind CSS.

![Demo GIF](demo.gif)

## Introduction

This project is a clone of the popular music streaming service, Spotify. It is a full-stack application that allows users to create accounts, browse and play music, create playlists, and more. The application uses various technologies like Next.js, React, Stripe for payments, Supabase for authentication and database, PostgreSQL for data storage, and Tailwind CSS for styling.

## Key Features

- Song upload
- Stripe integration
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with Supabase
- Github authentication integration
- File and image upload using Supabase storage
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Play song audio
- Favorites system
- Playlists / Liked songs system
- Advanced Player component
- Stripe recurring payment integration
- How to write POST, GET, and DELETE routes in route handlers (app/api)
- How to fetch data in server React components by directly accessing the database (WITHOUT API! like Magic!)
- Handling relations between Server and Child components in a real-time environment
- Cancelling Stripe subscriptions


## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Stripe](https://stripe.com/)
- [Supabase](https://supabase.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- And various other dependencies (see [package.json](package.json) for a full list).

## Getting Started

### Installation

1. Clone the repository to your local machine:

```shell
git clone https://github.com/Bahri_Adem/Full-Stack-Spotify-Clone-Next-13.4-React-Stripe-Supabase-Tailwind.git
```
2. Change into the project directory:

```shell
cd Full-Stack-Spotify-Clone-Next-13.4-React-Stripe-Supabase-Tailwind
```
3. Install the project dependencies:

```shell
npm install
```

### Configuration

1. Create a `.env.local` file in the project root and configure the following environment variables:

```js
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Usage

1. Start the development server:

```shell
npm run dev
```
2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the application.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository and create a new branch.
2. Make your changes and commit them with descriptive commit messages.
3. Open a pull request, explaining the changes and why they should be merged.
