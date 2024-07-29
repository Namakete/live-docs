# Live Docs

Development of an application that is an clone of [Google Docs](https://docs.google.com/) with collaborative capabilities.

## Tech Stack

**backend**

- [Next.js](https://nextjs.org/) (Framework)
- [Liveblocks](https://liveblocks.io/) (WebSocket)
- [Clerk](https://clerk.com/) (Auth)

**frontend**:

- [Tailwind CSS](https://tailwindcss.com/) (Styling)
- [Shadcn](https://ui.shadcn.com/) (Component Generator)

## Getting Started

1. Install Dependencies `npm install`
2. Environment variables: `touch .env.local`

   ```bash
   #  https://go.clerk.com/
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   #  https://liveblocks.io
   LIVEBLOCKS_SECRET_KEY=
   ```

3. Start Developing: `npm run dev`
