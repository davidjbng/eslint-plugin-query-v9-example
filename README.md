# Example ESLint Plugin Query with ESLint v9

> [!WARNING]
> ESLint v9 support including flat config is still a work in progress. This example is not yet fully functional.

> [!IMPORTANT]
> Before running this example, you must have @tansack/query cloned in a sibling folder and checked out a branch that supports ESLint v9. https://github.com/davidjbng/query/tree/eslint-v9-migration

## To run this example

In ./query/packages/eslint-plugin-query:

- `pnpm install`
- `pnpm build`

In this repository:

- `npm install`
- `npm run dev`

## Linting

- `npm run lint`

See the expected error in the console output: 

> ```
> /Users/dj/code/basic-typescript-eslint-v9/src/index.tsx
> 96:5  error  The following dependencies are missing in your queryKey: postId  @tanstack/query/exhaustive-deps
> ```

