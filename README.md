This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

# Bean Talk - Chat Application

Welcome to **Bean Talk**! A simple, real-time chat application that lets users communicate seamlessly, powered by Django, WebSockets, and MySQL.

---

## Features

- **Real-Time Messaging**: Send and receive messages instantly without refreshing the page.
- **User-Friendly Interface**: Clean, responsive design built with HTML and CSS.
- **Group Chats**: Join and participate in group conversations.
- **Message History**: View previous messages stored in MySQL.
- **Easy Setup**: Get started quickly with minimal configuration.

---

## Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Django (Python)
- **WebSockets**: Django Channels for real-time messaging
- **Database**: MySQL for storing user and message data
- **Cache Layer**: Redis (for WebSocket communication)

---

## Installation

### Prerequisites

1. **Python 3.8+**
2. **MySQL** (for database storage)
3. **Redis** (for WebSocket management)

### Step-by-Step Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bean-talk.git
   cd bean-talk