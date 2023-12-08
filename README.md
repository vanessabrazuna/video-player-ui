<h1 align="center">
    Video Player UI
</h1>

<p align="center">
  <img alt="Video Player UI" src="https://github-production-user-asset-6210df.s3.amazonaws.com/73675022/288928123-baec1f00-7e43-429c-bba4-2686c6384899.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20231208%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231208T003014Z&X-Amz-Expires=300&X-Amz-Signature=1bc21a2676c8006a1aeab0765b9575e85183fc8b831faa713c5af3dc359d08df&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=0" width="100%">
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
