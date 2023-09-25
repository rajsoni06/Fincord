# Discord Clone

A fullstack Discord clone built with Next.js, React, Tailwind, Socket.IO, Prisma, and MySQL.

![Screenshot](https://github.com/sgbj/discord-clone/assets/5178445/38cc0189-5818-416a-ba89-d36696a63a0a)

## Features

* 🔐 Authentication using Clerk
* 📊 MySQL database with PlanetScale and Prisma ORM
* ✉️ Real-time messaging using Socket.IO with polling as a fallback
* 🔉 Audio and video calls with LiveKit
* 🔃 Infinite scroll for loading messages using @tanstack/react-query
* ⚙️ Create and customize servers and channels
* 📝 Edit and delete messages
* 👨‍👩‍👧‍👦 Invite and manage members
* ✨ Responsive UI and light/dark mode built with Tailwind and shadcn/ui

## Getting Started

### Clone the repo

```bash
git clone https://github.com/sgbj/discord-clone.git
```

### Install dependencies

```bash
npm install
```

### Setup .env file

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Setup Prisma

```bash
npx prisma generate
npx prisma db push
```

### Start the app

```bash
npm run dev
```

## Credit

[Fullstack Discord Clone: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL | Full Course 2023](https://www.youtube.com/watch?v=ZbX4Ok9YX94)
