# BitzPrize
[ Learning ] Next.js

## Setup
- Install next, react and react-dom in your project:

```sh
npm install next react react-dom
```

- Open ' package.json ' and add the following ' scripts ':

```sh
"scripts": {
"dev": "next",
"build": "next build",
"start": "next start"
```

- Create a ' pages ' directory inside your project

- Populate ' ./pages/index.js ' with the following contents:

```sh
export default () =>
<div> Hello Next.js! </div>
```

- To start the server:

```sh
npm run dev
```
