Minimal reproduction of https://github.com/import-js/eslint-plugin-import/issues/2111.

- `npm install`
- `npx eslint src --ext ts`
- `bar.ts` should pass

![eslint command output bar.ts fails](./output.png)
