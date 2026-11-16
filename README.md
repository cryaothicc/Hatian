# Hatian

Split group expenses and see who owes whom.

[Open Hatian online](https://hatian-eta.vercel.app/)

## Split a bill

1. Add the people in your group.
2. Enter each expense, select who paid, and choose who shares it.
3. Review the suggested payments and copy the bill link.

Hatian saves the bill in your browser and encodes it in the URL. Anyone with the link can read the names, expenses, and amounts. The shared link opens a snapshot of the bill.

## Run locally

```sh
npm ci
npm run dev
```

Open [localhost:3000](http://localhost:3000/). Run `npm test` to check the split calculations.

Built with Next.js, React, TypeScript, and Tailwind CSS.
