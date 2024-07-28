> [!NOTE]  
> This project is for educational purposes only, aimed to understand and grasp the concepts of creating complex web applications using NextJS and Liveblocks. All assets used belong to their respective owners.

<div align="center">

![Next JS](https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Clerk](https://img.shields.io/badge/clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![ShadCN UI](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

</div>

## Summary

Live Docs is a fully-responsive web application that manages mark-down text editing collaboration in real-time. It is complete with CRUD functionalities, floating and sticky comment threads, live cursors, notifications, invitations, and many more.

## Features

- **Next.js**: A React framework that enables server-side rendering, server-actions, and revalidation.

- **Typescript**: A statically typed superset of JavaScript that enhances code quality and developer productivity with type safety and better tooling.

- **Clerk**: A user management and authentication service that simplifies the process of adding sign-up, sign-in, and user profile management to the application.

- **Liveblocks**: A real-time collaboration infrastructure that allows multiple users to edit documents simultaneously, with features like live cursors, presence, and conflict resolution.


## Running the Application

The application is deployed using Vercel. You can check the website out at https://jp-gerona-apple-website-clone.vercel.app/, or if you want to set-up this project in your local machine, follow these steps.

- Clone the repository

- In your terminal, install the necessary dependencies by running `npm install`

- Create a new file named .env.local in the root of your project and add the following content:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

- Insert values with your actual Clerk & LiveBlocks API Keys.

- Run the application in development mode using `npm run dev`

- Run the application in build mode using `npm run build`

- Vite will provide a URL in the terminal to your local server: http://localhost:3000

## Additional Reflection

This project took me 1 week to finish and understand the concepts. Next.js definitely makes it easy to build routing, API integration, and anything server-side related. When you compare it to using plain React only, it would have taken more effort to set-up these things.

Typescript introduces more strict rules over the usual Javascript but it does come with advantages like typesafety in build complex and growing web applications. It is self-documenting that makes it easier to understand what data types do each variables that are passed in the codebase.

Special thanks to [Javascript Mastery](https://www.youtube.com/@javascriptmastery) for this well-explained and awesome tutorial :)