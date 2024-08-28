# react-template

Template for a React application, based on personal preference.

## Usage

Make sure to download and install [Node](https://nodejs.org/en) and [Git](https://git-scm.com/) before proceeding.

1. Clone template: `git clone https://github.com/4y744/react-template`

2. Change directory: `cd react-template`

3. Install dependencies: `npm install`

4. Start test server: `vite` (add `--host` flag to expose)

## Dependencies

This template uses some **npm** packages which I find crucial for any React project.

- **tailwindcss** - [Tailwind](https://tailwindcss.com/) is a CSS framework that provides utility classes for everthing, removing the added complexity of .css files.

- **react-router-dom** - [React Router](https://reactrouter.com/en/main) is a routing library for React.

- **prettier** - [PrettierJS](https://prettier.io/) is an opinionated code formatter.

## File structure

File strucure is based on [Bulletproof React](https://github.com/alan2207/bulletproof-react/blob/master/docs/project-structure.md) with some changes.

- **src/core** - core components, such as the root component of the application, the router and the types.

- **src/components** - reusable components. Each component has its own folder that starts with a capital letter.

- **src/views** - page components. Their locations correspond to the url paths they are used at (e.g. **/home/index.ts** is used at _/home_), the folder name **[slug]** is used for dynamic routes. This file structure is just a design preference to keep the **src/views** directory easy to understand, it does NOT control routing like in Next.js.

- **src/assets** - the media used in the application (e.g. images, videos, pdf files).

- **src/hooks** - reusable hooks. Each kind has its own subfolder which holds a number of hooks with file names such as **useHook.ts** (e.g. **src/hooks/firestore** might have **useGetDoc.ts** and **useGetCollection.ts**).

- **src/services** - configuration files for services (e.g. Firebase, Algolia).

- **src/utils** - reusable utility functions.
