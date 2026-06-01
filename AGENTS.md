# Documentation agent instructions

These instructions apply to the Suppio Mintlify docs.

## Product scope

- Write for Suppio customers.
- Do not use internal developer language in customer-facing pages.
- Document only behavior confirmed by app routes, dashboard components, API handlers, pricing config, or existing docs.
- If behavior is unclear, leave a clear TODO comment rather than guessing.

## Mintlify basics

- Configuration lives in `docs.json`.
- Use MDX for documentation pages.
- Run `mint validate` and `mint broken-links` before finishing docs changes when possible.
- Keep navigation entries aligned with real files.

## Style

- Use active voice and second person.
- Keep sentences concise.
- Use sentence case for headings.
- Reference UI labels in bold, such as **Deploy**.
- Use code formatting for file names, commands, paths, endpoint names, and field names.

## Code examples

- Include language identifiers in fenced code blocks.
- Use realistic values.
- Include error handling for API examples.

## What to avoid

- Do not add unsupported features or endpoints.
- Do not leave old brand names in customer-facing docs.
- Do not use HTML when an MDX component is available.
- Do not add pages to navigation before creating the page.
