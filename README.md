# Demo Autocomplete

A static test page for the [Autocomplete](https://github.com/charliemday/autocomplete) Chrome extension.

No backend, no API keys. Load the unpacked extension, set a Groq key in its options page, then type in the fields here.

## How to try it

1. Load the unpacked Autocomplete extension in Chrome.
2. Set a Groq key — on the live page, that step links to the extension options field (or [console.groq.com/keys](https://console.groq.com/keys) if the extension is not loaded).
3. Open this page and type in a **Should complete** field.
4. Press `Tab` to accept ghost text, or `Escape` to dismiss it.

Password and credit-card fields are on the page so you can confirm the extension ignores them.

## Local

Open `index.html` in a browser, or serve this folder with any static file server.

## Deploy

Cloudflare Pages project name: `demo-autocomplete`.

```sh
npx wrangler pages deploy . --project-name demo-autocomplete
```
