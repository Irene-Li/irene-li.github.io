# Editing this website

Everything you'll want to change lives in **Markdown** (`.md`) or **data**
(`.yml`) files. You never need to touch HTML. After editing, commit and push —
GitHub Pages rebuilds the site automatically.

## Where things live

| I want to change…                    | Edit this file |
|--------------------------------------|----------------|
| Homepage intro text                  | `index.md` |
| Homepage "research interests" blocks | `_data/interests.yml` (text + which image) |
| A research project                   | the matching file in `_posts/` |
| Order of research projects           | the `order:` number in each `_posts/` file |
| People / group members               | `_data/people.yml` |
| "Join the group" text                | `people.md` |
| Publications                         | `publications.md` |
| Menu tabs (add/remove/rename)        | `_data/navigation.yml` |
| Group name, email, social links      | `_config.yml` |
| Banner image                         | replace `assets/images/banner.png` |

## Adding a research project

Create a file in `_posts/` named `YYYY-MM-DD-short-name.md`:

```markdown
---
layout: post
title: My project title
order: 2                       # position in the list (lower = higher up)
image: /assets/images/my-figure.png
summary: >-
  One or two sentences. This is the highlighted summary shown on the
  project, and the text that appears on the Research projects page.
paper_url: "https://..."       # optional — adds a "Read the paper" link
paper_title: "Read the paper — ..."   # optional label for that link
---

The full write-up goes here (as many paragraphs as you like).
```

Drop the figure into `assets/images/` and it shows up automatically.

## Images

All images live in `assets/images/`. To replace one, just save a new file over
the old one with the **same name**. The `post-*.png` files are placeholders —
swap in real figures whenever you have them.

## Previewing locally (optional)

```bash
bundle exec jekyll serve
```

then open <http://localhost:4000>.
