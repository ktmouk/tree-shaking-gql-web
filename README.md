This is the reproduction of the issue that @0no-co/graphql.web does not support tree-shaking.
Run `pnpm install && pnpm build`, then check if `dist/bundle.js` contains unused GraphQL objects.
