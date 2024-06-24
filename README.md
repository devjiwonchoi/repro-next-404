## Steps to Reproduce

1. `pnpm install`
2. `pnpm dev`
3. goto `http://localhost:3000/404`
4. check out console, will have status code 404
5. check out the `head` tag, will have `<meta name="robots" content="noindex" />`
