# Artheria Lore Repo

The public lore of **Artheria**: the lore book and session write-ups. The game ([Artheria.ES.3D.Lore.Game](https://github.com/Greiye/Artheria.ES.3D.Lore.Game)) and its wiki are built from it.

> **Repository purpose:** This is a lore-only repository. Do not convert it into an application, website, wiki implementation, or game project. Keep additions as Markdown lore or supporting place and scene art.
>
> **External app contract:** Treat this repository as a read-only source for other applications and projects. Applications may read or import lore, images, and references, but must not write to, rewrite, generate files in, or commit changes back to this repository. Store derived data, caches, generated indexes, and application-specific edits in the consuming project.

| Folder | What's in it |
|---|---|
| `book/` | *Tales of Artheria*: Part I (the World), Part II (Chronology), names appendix |
| `sessions/` | Session novels and recaps, as markdown |
| `stories/` | Standalone fiction set in Artheria (e.g. *Variegated*, the making of Dr. Podrigo) |
| `images/` | Place and scene art, one folder per place |

## Rules

- **This repo is public.** The DM's Book (Part III) and raw session exports never go here.
- Strip players' Discord handles (`@Name#1234`) from session text before adding it.
- Where sources disagree, a **⚖ Sources disagree** note names who says what. No version is final.

## Images

Place and scene art lives in `images/<place>/` (e.g. `images/aralon/aralon-farmers-market-3200x1800.webp`). The game wiki embeds them from this repo's raw URLs.

The book itself refers to `images/imageN.webp`. Those 65 images aren't in the repo yet; put them in `book/images/`. If images or video grow past a few hundred MB, move them to an object store (Cloudflare R2) and link them from there.
