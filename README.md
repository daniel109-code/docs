# Suppio Documentation

This folder contains the Mintlify documentation for Suppio.

The docs are written for Suppio customers. They explain how to set up, deploy, manage, and troubleshoot Suppio across Discord, the web chat widget, support pages, and the Agent API.

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the local preview from this directory:

```bash
mint dev
```

Validate the docs before publishing:

```bash
mint validate
mint broken-links
```

## Structure

- `docs.json` controls navigation, branding, and OpenAPI wiring.
- `*.mdx` files are customer-facing documentation pages.
- `api-reference/openapi.json` defines the generated Agent API reference.
- `favicon.svg` and `logo/` contain Suppio branding assets.

## Writing guidelines

- Write for customers, not developers.
- Use active voice and second person.
- Keep setup instructions task-oriented.
- Do not document features, endpoints, or behavior that are not present in the app.
- If source behavior is unclear, leave a clear TODO comment instead of guessing.
