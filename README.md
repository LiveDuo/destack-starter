# Destack Starter

This example shows a very basic version of a *Destack* project with Next.js. 

- There's one page, `pages/index.js`, that shows the visual editor (in development) and the compiled version (in production). 
- All the magic is done in, `pages/api/builder/handle.js`, that has to be setup once and handles templates saving and loading.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com) or preview in Gitpod:

[<img src="https://github.com/LiveDuo/destack/raw/main/assets/vercel_big.png" width="92">](https://vercel.com/new/git/external?repository-url=https://github.com/LiveDuo/destack-starter&project-name=destack-starter&repository-name=destack-starter)
&nbsp;&nbsp;&nbsp;
[<img src="https://github.com/LiveDuo/destack/raw/main/assets/gitpod_big.png" width="92">](https://gitpod.io/#https://github.com/LiveDuo/destack-starter)


## How to use

Clone this repository:
```sh
git clone https://github.com/liveduo/destack-starter
```
Install dependencies:
```sh
npm i
```
Run the project in development:
```sh
npm run dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/new) ([Documentation](https://nextjs.org/docs/deployment)).
