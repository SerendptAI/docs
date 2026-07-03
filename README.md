# SwiftAgent Widget Documentation

Mintlify documentation site for the SwiftAgent embeddable chat widget.

## Preview locally

Install the Mintlify CLI and run the dev server from this directory:

```bash
npm i -g mint
mint dev
```

The site is served at `http://localhost:3000`. Edits to `.mdx` files hot-reload.

## Structure

```
swiftagent-docs/
├── docs.json                 # Site config: theme, colors, navigation
├── favicon.svg
├── logo/                     # Light & dark logos
├── introduction.mdx
├── quickstart.mdx
├── installation.mdx
├── configuration/            # Script attributes, display modes, styling
├── features/                 # Chat, file uploads, voice
├── guides/                   # Custom triggers, SPA integration, troubleshooting
└── api/                      # JavaScript API reference
```

## Editing

- Pages are [MDX](https://mintlify.com/docs): Markdown plus Mintlify components
  (`Card`, `Steps`, `Accordion`, `ParamField`, `CodeGroup`, etc.).
- Add or reorder pages in the `navigation` array of `docs.json`. Each entry is a
  page path **without** the `.mdx` extension.
- Update brand colors and the primary CTA in `docs.json`.

## Deploy

Connect this repository to [Mintlify](https://mintlify.com) and it deploys on push.
Set the docs root to this directory if it lives alongside other projects.
