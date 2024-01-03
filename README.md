<h1 align="center">
    Video Player UI
</h1>

<p align="center">
  <img alt="Video Player UI" src="https://github.com/community/community/assets/73675022/de3c6f60-48d0-481b-be3c-dcd6ca6fb8b3" width="100%">
</p>


## Technologies Used

The project was developed using the following technologies

- [ReactJS](https://legacy.reactjs.org)
- [React Redux](https://react-redux.js.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React PLayer](https://www.npmjs.com/package/react-player/v/1.5.0)
- [TypeScript](https://www.typescriptlang.org)
- [Tailwindcss](https://tailwindcss.com)
- [Tailwind Scrollbar](https://www.npmjs.com/package/tailwind-scrollbar)
- [Radix Collapsible](https://www.radix-ui.com/primitives/docs/components/collapsible)
- [Lucide React](https://lucide.dev/guide/packages/lucide-react)
- [Json Server](https://github.com/typicode/json-server)
- [Axios](https://axios-http.com/)
- [Vitest](https://vitest.dev/)
- [Zustand](https://github.com/pmndrs/zustand)


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
