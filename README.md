
# Dear Diary ✨

## A Full-Stack Journal App built with Next.js, React, Tailwind CSS, Prisma, Neon, Clerk, Arcjet, and shadcn/ui

# About the Project

## Dear Diary is a modern full-stack journal application where users can securely capture thoughts, track moods, and reflect on their journey in a beautiful, distraction-free space. This project combines a cutting-edge stack with robust authentication, secure APIs, and a polished UI — making it production-ready and highly extensible.


## Features

- Clerk Authentication — Sign up, sign in, and protected routes out of the box

- Collections & Entries — Organize your journaling with CRUD functionality

- Tailwind CSS + shadcn/ui — Clean, modern, and responsive design

- Arcjet Integration — Security and abuse prevention (rate-limits & guardrails)

- Prisma + Neon Postgres — Typed ORM + serverless Postgres database

- Pixabay Integration — Optional images to style your journal

## Tech Stack

- Next.js 15

- React 18

- Tailwind CSS

- shadcn/ui

- Prisma ORM

- Neon - (Postgres database)

- Clerk - (Auth & user management)

- Arcjet - (Security)

## Setup & Installation

### Clone the repo
```
git clone https://github.com/your-username/dear-diary.git
cd dear-diary
```


### Install dependencies
```
npm install
```

### Create .env file in root
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

DATABASE_URL=

PIXABAY_API_KEY=

ARCJET_KEY=
```

### Run migrations & generate Prisma client
```
npx prisma generate
npx prisma migrate dev --name init
```

### Start the dev server
```
npm run dev
```



## 📸 Screenshots  

![Screenshort](./screenshots/dashboard.png)  
![Screenshort](./screenshots/dashboard.png)  
![Screenshort](./screenshots/dashboard.png)  
![Screenshort](./screenshots/dashboard.png)  
![Screenshort](./screenshots/dashboard.png)  
![Screenshort](./screenshots/dashboard.png)  




## 🌐 Live Demo  

- [Click here to view the app live](https://your-deployment-link.vercel.app)




## 📬 Contact  

- Created by [Sumit_Kushwaha](https://github.com/your-username) – feel free to reach out! 






















