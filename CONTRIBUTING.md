# Contributing to Awesome Frameworks

Thank you for helping keep this collection accurate, consistent, and easy to consume.

## What belongs here

This repository catalogs framework entries in category-specific Markdown docs under `docs/`.
Each category file should include:

- A top-level title and brief category description
- A `## Contents` list of section anchors
- One or more `##` sections for subcategories
- A Markdown table with the canonical entry format

## Table format

All framework entries must use the same table layout:

| Framework | Description | Language | Docs |
|-----------|-------------|-----------|-------|

- `Framework` is the official name of the project or platform.
- `Description` is a short, clear summary of the project.
- `Language` is the primary implementation language or supported language ecosystem.
- `Docs` contains canonical links to the project’s GitHub repo and official website.

### Example row

| React | Declarative UI library for building web interfaces | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/facebook/react) • [Website](https://react.dev) |

## Language formatting

Use the `<kbd>🏷️ ...</kbd>` wrapper for the `Language` column. Examples:

- `<kbd>🏷️ JavaScript</kbd>`
- `<kbd>🏷️ Python</kbd>`
- `<kbd>🏷️ Dart</kbd>`
- `<kbd>🏷️ Multi</kbd>`
- `<kbd>🏷️ YAML</kbd>`

If a project spans multiple languages, use a concise multi-value label such as `<kbd>🏷️ Java/Kotlin</kbd>` or `<kbd>🏷️ Multi</kbd>`.

## Docs links format

The `Docs` column should use two links separated by `•`:

- `[GitHub](https://github.com/<owner>/<repo>)`
- `[Website](https://...)`

If an official GitHub repo does not exist, use a reliable project homepage or an authoritative source instead.
If an official website is unavailable, use a searchable project page that best represents the project.

## Section and file structure

Each category file should follow the repo’s existing structure, for example:

- `docs/web-development.md`
- `docs/mobile-development.md`
- `docs/ai-ml-frameworks.md`
- `docs/data-science-frameworks.md`
- `docs/cloud-devops-frameworks.md`
- `docs/cybersecurity-frameworks.md`

Within each file:

1. Start with a title and brief description.
2. Add a `## Contents` list with links to each subsection.
3. Separate subsections with `##` headings.
4. Use a clean table under each subsection.

## How to add a new entry

1. Open a pull request against the `main` branch.
2. Add the entry to the appropriate category file.
3. Follow the formats above exactly.
4. Keep descriptions concise and avoid duplicate entries.
5. If you add a new category subsection, update the `## Contents` list.

### Example contribution

To add a new web framework:

- Edit `docs/web-development.md`
- Add the subcategory if needed
- Include a table row like:

  | Solid | Declarative UI framework for high-performance web apps | <kbd>🏷️ JavaScript</kbd> | [GitHub](https://github.com/solidjs/solid) • [Website](https://solidjs.com) |

## Naming and duplicate handling

- Use the framework’s common public name.
- Avoid adding alternate spellings as separate entries.
- Do not repeat a project in multiple tables unless it belongs to different distinct categories and the overlap is intentional.

## Pull request checklist

- [ ] Entry is added to the correct category file.
- [ ] Table header is `| Framework | Description | Language | Docs |`.
- [ ] Language values use `<kbd>🏷️ ...</kbd>`.
- [ ] Docs links point to canonical GitHub and official website pages.
- [ ] `## Contents` is updated when subsection headings change.

## If you want to add a new category

1. Create a new `docs/<category-name>.md` file.
2. Add it to `README.md` and the root `Table of Contents` if needed.
3. Use the same title, description, contents list, and table styling.

---

Thank you for contributing!