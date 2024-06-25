

# MERN BOBOE-MART SERVER 

Hi, my name is Vishal Vishwakarma and I am a computer science student. I am working on developing a full MERN stack e-commerce website.  I am planning to deploy this project on Render.

# Prerequisite

1.  Must have basic knowledge of **Node**, **React**, **Express**, **MongoDB** . _

# Install Dependencies

For Dev - npm i && npm run dev For Product - npm i && npm run preview

Env Variables
Make Sure to Create a .env file in root directory and add appropriate variables in order to use the app.

Essential Variables

VITE_FIREBASE_KEY= from firebase

VITE_AUTH_DOMAIN= from firebase

VITE_PROJECT_ID=from firebase

VITE_STORAGE_BUCKET=from firebase

VITE_MESSAGING_SENDER_ID=from firebase

VITE_APP_ID=from firebase

VITE_SERVER=Your Backend Server URl

VITE_STRIPE_KEY=Stripe Publishable Key

fill each filed with your info respectively



# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
