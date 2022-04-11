# Ladle

Ladle is an environment to develop, test and share your React components faster.

- [Documentation](https://www.ladle.dev)
- [Demo](https://baseweb.design/ladle)
- [StackBlitz](https://node.new/ladle)
- [Discord](https://discord.gg/H6FSHjyW7e)

![Ladle BaseWeb](https://raw.githubusercontent.com/tajo/ladle/master/packages/website/static/img/ladle-baseweb.png)

## Quick start

```sh
yarn add @ladle/react react react-dom
yarn ladle serve # to start deving
yarn ladle build # to build (when ready to deploy)
```

Create your first story `src/hello.stories.tsx`:

```jsx
export const Button = () => <button>Hello</button>;
```