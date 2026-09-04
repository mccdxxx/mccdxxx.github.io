# Naki // N4-K2 — Extended Jekyll Site

This is the expanded GitHub Pages / Jekyll version of the personal site.

## Major structure

```text
.
├── _config.yml
├── _data/
├── _includes/
├── _layouts/
├── _posts/
├── _projects/
├── _writing/
├── pages/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── Gemfile
├── README.md
└── index.html
```

## What Jekyll is doing

### Layouts

Reusable page structures live in `_layouts/`.

- `default.html` — global page shell
- `project.html` — individual project records
- `writing.html` — writing archive entries
- `post.html` — devlog posts

### Includes

Reusable pieces live in `_includes/`.

Examples:

- Header
- Footer
- Project cards
- Link cards
- Stat cards
- Page heroes

### Data

Editable YAML data lives in `_data/`.

This includes:

- Profile
- Navigation
- Skills
- Games
- Aesthetics
- FAQ
- Current activity
- Links
- Uses
- Statistics

### Collections

Projects live in `_projects/`.

Writing archive records live in `_writing/`.

Each Markdown file becomes its own generated page.

### Posts

Devlog entries live in `_posts/` and use normal Jekyll post filenames.

## Important URLs

- `/`
- `/about/`
- `/projects/`
- `/writing/`
- `/development/`
- `/gaming/`
- `/interests/`
- `/now/`
- `/uses/`
- `/faq/`
- `/devlog/`
- `/links/`
- `/directory/`

## Editing profile data

Edit:

```text
_data/profile.yml
```

## Adding a project

Create a Markdown file in:

```text
_projects/
```

Example:

```yaml
---
title: "Example Project"
type: "Minecraft Mod"
status: "In Development"
summary: "Short description."
tags:
  - "minecraft"
  - "java"
---

Long project description goes here in Markdown.
```

The project automatically receives the project layout and appears in the project collection.

## Adding a writing record

Create a Markdown file inside `_writing/`.

## Adding a devlog post

Create a file in `_posts/` with a date-prefixed filename:

```text
2026-08-17-example-post.md
```

## Command palette

Press:

```text
Ctrl + K
```

or:

```text
Command + K
```

to open the site command palette.

It searches generated pages and collections and also exposes a few site actions.

## Local Jekyll testing

Install Ruby and Bundler, then:

```bash
bundle install
bundle exec jekyll serve
```

Jekyll normally serves locally at:

```text
http://127.0.0.1:4000/
```

## GitHub Pages

For branch-based GitHub Pages publishing:

1. Upload the project files to the repository.
2. Open repository Settings.
3. Open Pages.
4. Choose Deploy from a branch.
5. Select the publishing branch.
6. Select `/(root)`.
7. Save.

This project intentionally does not contain `.nojekyll` because Jekyll processing is required.


# Wiki expansion

The site now includes these additional Jekyll collections:

```text
_characters/
_species/
_lore/
_docs/
_roadmaps/
_galleries/
_changelogs/
```

Generated wiki routes include:

```text
/wiki/
/wiki/characters/
/wiki/species/
/wiki/lore/
/docs/
/roadmaps/
/gallery/
/changelog/
/tags/
```

## Related records

Wiki records can include:

```yaml
record_id: "character-example"
related_ids:
  - "species-example"
  - "lore-example"
```

The wiki layout automatically renders matching connected records and backlinks.

## Tags

Tags are collected across the major collections and displayed on `/tags/`.

## Adding a character

Create a file in `_characters/`:

```yaml
---
title: "Example Character"
record_id: "character-example"
status: "Active Canon"
project: "Example Project"
role: "Core Character"
tags:
  - character
  - example
related_ids:
  - "species-example"
---

Character description in Markdown.
```

## Adding species or lore

Use the same pattern in `_species/` or `_lore/`.

## Documentation

Technical notes live in `_docs/` and receive their own generated documentation URLs.

## Gallery

Gallery records can contain normal Markdown, HTML, or image references. Put image files under `assets/images/`.

## Current GitHub Pages repository path

This repository is named `nakiiii.github.io`, but the GitHub account is
`just-Naki-here`. That makes this a **project Pages site**, so its default URL is:

```text
https://just-naki-here.github.io/nakiiii.github.io/
```

For that deployment, `_config.yml` must use:

```yaml
url: "https://just-naki-here.github.io"
baseurl: "/nakiiii.github.io"
```

Jekyll's `relative_url` filter then generates asset and navigation URLs under
the repository subpath correctly. If the repository is ever renamed to
`just-Naki-here.github.io`, change `baseurl` back to an empty string.


# Repository-specific GitHub Pages configuration

This package is configured specifically for the repository:

```text
nakiiii.github.io
```

under the GitHub account:

```text
just-Naki-here
```

Because the repository name does **not** exactly match the account's user-site
repository name (`just-Naki-here.github.io`), GitHub Pages treats it as a
project site.

The configured values are:

```yaml
url: "https://just-naki-here.github.io"
baseurl: "/nakiiii.github.io"
```

The expected public site root is:

```text
https://just-naki-here.github.io/nakiiii.github.io/
```

Examples:

```text
https://just-naki-here.github.io/nakiiii.github.io/about/
https://just-naki-here.github.io/nakiiii.github.io/projects/
https://just-naki-here.github.io/nakiiii.github.io/wiki/
https://just-naki-here.github.io/nakiiii.github.io/wiki/characters/
```


## TAHAUFYA Character Bible

The repository includes the current-cast-only TAHAUFYA: Found in the Noise character bible.

- Web index: `/character-bible/`
- Dossier collection: `_tahaufya_bible/`
- Active dossiers: 25
- Original source PDF: `assets/docs/TAHAUFYA_Found_in_the_Noise_Character_Bible_CURRENT_CAST_ONLY.pdf`

Each dossier preserves the source document's distinction between Locked Canon, Bible Expansion, and Open Field material.

## OUTSIDE THE NOISE ARG

An intentionally hidden ARG exists at `/signal/`. It uses a Jekyll `_arg`
collection, localStorage progress, recovery phrases, source-code clues, a
subtle footer signal, all 25 current-cast TAHAUFYA characters, fictionalized
real-world family witnesses, and three endings.

`ARG_OWNER_GUIDE.md` and `ARG_STORY_MAP.md` contain spoilers and are excluded
from deployment.


## ARG 18+ Mode

The ARG now has a persistent browser setting at `/signal/settings/`.

When enabled, visitors can use `/signal-mature/`, a parallel generated collection
containing a mature counterpart for every standard ARG record.

The mature archive preserves the same puzzle answers/unlocks and continuity while
adding stronger language, violence/consequences, psychological distress, grief,
and less-sanitized failure-ending records.

The standard archive remains available.


## 18+ Age Gate

The mature ARG now requires local age verification.

The visitor must:

1. enter a date of birth,
2. pass the calculated 18+ check,
3. explicitly confirm the age declaration,
4. then enable 18+ mode.

Mature routes enforce the verification on every page load.

LocalStorage keys:
- `outside-noise:age-verified`
- `outside-noise:age-verified-at`
- `outside-noise:age-dob-year`
- `outside-noise:mature-mode`

This is a client-side self-declaration gate. It is not identity-document verification.


## Elaborate GitHub Pages Age Gate

The mature ARG uses a three-stage browser-only age gate:

1. DOB calculation + accuracy confirmation
2. adult-content + 18+ attestations
3. typed phrase `I AM 18 OR OLDER` + local-verification consent

Successful verification creates a random local session token with a 12-hour expiration.
The full DOB is not retained after verification; only the birth year is stored.

Mature routes re-check the verification flag, gate version, session token, and expiration.
A separate `/signal/18plus-entry/` interstitial is required before `/signal-mature/`.

Because GitHub Pages is static hosting, this remains self-attestation rather than identity verification.
