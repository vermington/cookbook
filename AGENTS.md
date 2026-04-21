# Cookbook agent instructions

This repository is a personal cookbook written in Markdown for Obsidian.

## Mission
Help maintain a clean, consistent, highly usable personal cookbook.
Prefer practical cooking accuracy over flourish.
Prefer authenticity over fusion unless the recipe is explicitly marked as fusion.

## Scope
You may:
- create new recipe markdown files
- update existing recipes
- normalize formatting
- add cross-links, tags, and metadata
- create shopping lists, menus, prep plans, and notes

Do not:
- rewrite the whole repo structure unless asked
- rename files casually
- remove user notes or personal observations
- invent personal cooking outcomes that are not recorded

## House style
Follow `reference/style-guide.md`.
If there is any conflict, `style-guide.md` wins over generic writing preferences.

## Recipe principles
- Indian recipes must respect the house regional preferences.
- Favour authentic home-style cooking over restaurant excess unless explicitly requested.
- Keep recipes practical for a UK home kitchen.
- Give metric quantities by default.
- Use clear sequencing and realistic timings.
- Include key texture and doneness cues.
- Note optional substitutions separately.
- Mark whether a dish is:
  - weekday
  - guest-worthy
  - meal-prep friendly
  - freezer friendly

## File format
Every recipe file should:
- be Markdown
- begin with YAML frontmatter
- use the standard template from `templates/recipe-template.md`
- include:
  - title
  - cuisine
  - course
  - servings
  - time
  - equipment
  - ingredients
  - method
  - notes
  - serving suggestions
  - tags

## Naming
Use file names in kebab-case.
Example:
`recipes/indian/north-indian/up-style-rajma.md`

## Editing rules
- Preserve existing user commentary under a section called `Personal notes` if present.
- When standardizing a recipe, do not silently change flavour profile.
- If a quantity or step is uncertain, leave a short `TODO` note rather than guessing.
- Prefer additive edits over destructive edits.

## When creating a new recipe
- Check for duplicates first.
- If a near-duplicate exists, propose merge or variant naming.
- If this is a variation, link to the parent recipe.

## Commit style
Use concise commit messages, e.g.:
- `add chettinad chicken curry`
- `standardize paneer makhani format`
- `add codex style guide and templates`