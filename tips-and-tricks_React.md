# 🍆 Tips & Tricks 🎃

> This one is for ⚛️ *React*


## Getting Started

### New Project

1. Create a new project using ⚡ Vite
```sh
npm create vite@latest
```
2. Change directory to the root folder of the project
    - *example-project* being the name of the project
```sh
cd example-project
```
3. Start the project by running the command
```sh
npm run dev
```

### Hooks

- useState
    - This hook allows you to save states
```ts
const [count, setCount] = <number>(0);
```

- useEffect
```js
useEffect((props) => {
    //code
}, [dependency]);
```

- useRef
```ts
const count = useRef<number>(0);
```
