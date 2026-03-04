# Rivo Templates

A collection of front-end Liquid snippets for small Rivo features, organised by page type.

## Folder Structure

| Folder | Description |
|--------|-------------|
| `PDP/` | Product Detail Page snippets |
| `PCP/` | Product Collection Page snippets |
| `Cart/` | Cart page snippets |
| `Account/` | Customer account page snippets |
| `Global/` | Snippets that apply across multiple pages |

## Adding a New Snippet

1. Create a new branch: `feature/[page-type]-[feature-name]`
2. Add a new folder inside the relevant page folder (e.g. `PDP/My New Widget/`)
3. Include two files:
   - `Instructions` — how to install and use the snippet
   - The `.liquid` file — the actual code
4. Push your branch and open a Pull Request

## Conventions

- Folder names should be human-readable (e.g. `Variant Specific Potential Points Widget`)
- One branch and one PR per feature
- Always pull from `main` before starting a new branch
