
# Netflix App

## Expected Outcome



## Description

Project aims to clone a Netflix App.

## Project Skeleton
```
├── app
│    ├── (private)
│    │     ├── movies
│    │     │      ├── [movieId]
│    │     │      │       └── page.jsx
│    │     │      ├── components
│    │     │      │       ├── HeroSection.jsx
│    │     │      │       ├── MovieCard.jsx
│    │     │      │       ├── MovieList.jsx
│    │     │      │       ├── MovieSection.jsx
│    │     │      │       └── VideoSection.jsx
│    │     │      └── page.jsx
│    │     ├── profile
│    │     │      ├── components
│    │     │      │       ├── CardContainer.jsx
│    │     │      │       └── ProfileCard.jsx
│    │     │      └── page.jsx
│    │     └── layout.jsx
│    │
│    ├── (public)
│    │     └── login
│    │          └── page.jsx
│    │     └── register
│    │          └── page.jsx
│    │     
│    ├── error.jsx
│    ├── global.css
│    ├── layout.js
│    ├── loading.jsx
│    ├── not-found.jsx
│    └── page.js
├── auth
│    └── firebase.js
├── components
│    └── Navbar.jsx
├── helpers
│    ├── movieFunctions.js
│    └── ToastNotify.js
├── hooks
│    └── useAuthCalls.jsx
├── public
│    ├── icons
│    └── images
├── redux
│    ├── features
│    │     └── authSlice.jsx
│    ├── providers.jsx
│    └── store.jsx
├── .env
├── .gitignore
├── jsconfig.json
├── next.config.mjs
├── package.json
├── postcss.config.js
├── readme.md
├── tailwind.config.js
└── yarn.lock
```

## Objective

Clone a Netflix App using Netxt.js.

### At the end of the project, following topics are to be covered;

- Next.js

- React

- Redux

- Tailwind

- Firabase

### At the end of the project, students will be able to;

- improve coding skills within Next.js & React & Redux & Tailwind.

- use git commands (push, pull, commit, add etc.) and Github as Version Control System.

## Getting Started
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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
