# react-template

Template for a React app, based on personal preference.

## File structure

File strucure is based on [Bulletproof React](https://github.com/alan2207/bulletproof-react/blob/master/docs/project-structure.md) with some changes.

- **src/core** - core components, such as the root component of the application, the router and the types.

- **src/components** - reusable components. Each component has its own folder that starts with a capital letter.

- **src/views** - page components. Their locations correspond to the url paths they are used at (e.g. **/home/index.ts** is used at _/home_), the folder name **[slug]** is used for dynamic routes. This file structure is just a design preference to keep the **src/views** directory easy to understand, it does NOT control routing like in Next.js.

- **src/assets** - the media used in the application (e.g. images, videos, pdf files).

- **src/hooks** - reusable hooks. Each kind has its own subfolder which holds a number of them with file names such as **useHook.ts** (e.g. **src/hooks/firestore** might have **useGetDoc.ts** and **useGetCollection.ts**).

- **src/libs** - configuration files for services (e.g. Firebase, Algolia)

- **src/utls** - reusable utility functions
