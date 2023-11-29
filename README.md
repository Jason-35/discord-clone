# Next.js Discord Clone

## A fullstack web application that functions similar like discord using Next.js, Typescript, MySql, and Prisma

This is a full stack project following along a youtube tutorial in creating a discord-like chatting application. Technologies and libraries used for this project are the following:

* Next.js
* Prisma
* MySql
* Typescript
* [Tailwind](https://tailwindcss.com/)
* [Shadcn](https://ui.shadcn.com/)
* [Lucid React](https://lucide.dev/)
* [Uploadthings](https://uploadthing.com/)
* [Clerk](https://clerk.com/)
* [Livekit](https://livekit.io/)

#### Watch the tutorial [here](https://www.youtube.com/watch?v=ZbX4Ok9YX94&t=2493s).


#### Project is deployed on railway <a href="https://discord-clone-production-8309.up.railway.app/" style="color:red; text-decoration:underline">here</a>! 

## Installation

If you want to try this out locally

### Requires:
* MySql database
* Node.js
* [Uploadthings account](https://uploadthing.com/)
* [Clerk account](https://clerk.com/)

### .env file
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/login
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/register
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

DATABASE_URL=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

clone the project

```
> git clone https://github.com/Jason-35/discord-clone.git
```
cd into the file directory

```
> npm install
```

and run

```
> npm run dev
```


