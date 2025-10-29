# claude-code-frontend-template

The most reliable frontend template for Claude Code.

## Usage

```bash
npx degit marswong/claude-code-frontend-template app
cd app
npm install
npm run dev
```

for realtime preview, `vite` server check host by default, please use `serve` instead:
```bash
npm run build
npm run serve
```

port is set to `3000` by default, to set a custom port, please add the `-l` args:
```bash
npm run serve -- -l 1989
```

## Philosophy

- To avoid unknown issues, only use `vite`, `vue`, `vue-router`, `tailwindcss` and `serve`, don't introduce any other package
- Build for model `claude-sonnet-4-5-20250929`, so all package versions and documentations should be published before the date `20250929`

## Reference

- [vite](https://vite.dev)
- [vue](https://vuejs.org)
- [vue-router](https://router.vuejs.org)
- [tailwindcss](https://tailwindcss.com)
- [serve](https://github.com/vercel/serve)
