## About

Tailwind 2.2.7 has a bug where the group-hover class does not work. I have tested this by downgrading to Tailwind 2.1.1 and have no issues.

## Getting Started

First, run the npm install or yarn.

Then start the server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Reproduce

Simply try to hover over the icon on the page. The HomeIcon should bounce on hover.

Try downgrading to v2.1.1 and it should work.
