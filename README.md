# MetaDexa API Docs

Documentation for the MetaDexa API, built with [Mintlify](https://mintlify.com/docs).

Live site: https://kromatika.mintlify.site

## Preview locally

```bash
npm i -g mint
mint dev
```

Run it at the root, where `docs.json` is. The preview is at `http://localhost:3000`.

## Publishing

Changes deploy automatically when they're merged to `main`. A GitHub Action runs `mint validate` and `mint broken-links` on every pull request.
