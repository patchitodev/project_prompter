Prompter is an open-source AI prompting tool for modern world to discover, create and share creative prompts

## 🛠️ Stack

- [**Next.js**](https://nextjs.org/) - The web framework for high-quality web applications.
- [**MongoDB**](https://mongodb.com/) - The world's most popular database and developer platform.
- [**NextAuth.js**](https://next-auth.js.org/) - The authentiacion platform for Next.js
- [**Tailwindcss**](https://tailwindcss.com/) - A utility-first CSS framework for rapidly building custom designs.

## Key Features:

- Modern Design with Glassmorphism Trend Style
- Discover and Share AI Prompts
- Edit and Delete Created Prompts
- Profile Page
- View Other People's Profiles
- Copy to Clipboard
- Search Prompts by Specific Tag
- Google Authentication using NextAuth
- Responsive Website

## Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/patchitodev/project_prompter.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these corresponding websites from Google Cloud Console, Cryptpool (for random Auth Secret), and MongoDB.

### Start the app

```shell
npm run dev
```
