This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First create a project:

```bash
npm create next-app@14 -- next-amplify-gen2 --typescript --eslint --no-app --no-src-dir --no-tailwind --import-alias '@/*'

cd next-amplify-gen2
```

Then initialize amplify:

```bash
npm create amplify@latest
```

Start the development server:

```bash
npm run dev
```

Then deploy your sandbox account by using:

```bash
npx amplify sandbox --profile Amplify
```


## CLI commands to install project dependencies

```bash
npm install aws-amplify @aws-amplify/ui-react || npm install @aws-amplify/ui-react aws-amplify || npm install @aws-amplify/ui-react
npm add @aws-amplify/ui-react
```

Optional dependencies:

```bash
npm install aws-amplify @aws-amplify/adapter-nextjs
```
