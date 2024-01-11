## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Known issue/s

Currently, `node-pre-gyp` fails with `bun@1.0.x`. In [package.json](./package.json), adding `bcrypt` as a trusted dependency solves this issue. Suggestion taken from [this comment](https://github.com/oven-sh/bun/issues/4969#issuecomment-1714679629).
