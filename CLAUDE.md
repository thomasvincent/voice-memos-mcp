# CLAUDE.md

MCP server for Voice Memos on macOS -- record, list, and play back voice memos via AppleScript.

## Stack

- TypeScript / Node >=18 / ESM
- MCP SDK, Vitest, ESLint 9, Prettier, Husky

## Build & Test

```sh
npm run build         # tsc
npm test              # vitest run
npm run lint          # eslint .
npm run format:check  # prettier --check .
npm run dev           # tsc --watch
```

## Layout

- `src/index.ts` is the main server file; `src/__tests__/` holds tests
- Pre-commit hooks (Husky + lint-staged) auto-run eslint and prettier
