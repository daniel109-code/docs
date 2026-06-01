# Contribute to the Suppio docs

Use these guidelines when editing Suppio documentation.

## Local checks

Run these commands from the `docs` directory before publishing:

```bash
mint validate
mint broken-links
```

## Writing guidelines

- Use active voice.
- Address the reader as `you`.
- Keep sentences concise.
- Start with the customer goal before implementation details.
- Use consistent Suppio terminology: workspace, agent, context, deployment, support page, chat widget, and Agent API.
- Reference UI labels in bold, such as **Deploy** or **Context**.
- Include realistic examples for API and setup instructions.
- Do not invent features, endpoints, settings, limits, or behavior.

## Mintlify guidelines

- Add frontmatter with `title` and `description` to each customer-facing page.
- Use MDX components such as `Steps`, `Card`, `CardGroup`, `Columns`, `AccordionGroup`, `Accordion`, `Note`, and `Warning` when they improve scanning.
- Use fenced code blocks with language identifiers.
- Keep navigation changes in `docs.json`.
- Add new pages to navigation only when the file exists.
