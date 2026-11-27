# Artheria Lore Repo

The shared lore of **Artheria**: the text, images and videos that tie together the worlds my friends and I have made over years of tabletop play. This repo is the canon. Games and other spin-offs (the text game, the 3D game and anything after) are separate projects that draw from it.

> **Repository purpose:** This is a lore-only repository. Do not convert it into an application, website, wiki implementation, or game project. Keep additions as Markdown lore or supporting place and scene art.
>
> **External app contract:** Treat this repository as a read-only source for other applications and projects. Applications may read or import lore, images, and references, but must not write to, rewrite, generate files in, or commit changes back to this repository. Store derived data, caches, generated indexes, and application-specific edits in the consuming project.

**The master lore file is [ARTHERIA.md](ARTHERIA.md).**

| Path | What's in it |
|---|---|
| [`ARTHERIA.md`](ARTHERIA.md) | **The master lore.** At a Glance summaries, Part I: The World, Part II: Chronology, and the names appendix |
| `stories/` | Standalone fiction set in Artheria (e.g. *Variegated*, the making of Dr. Podrigo) |
| `sessions/` | Session novels and recaps |
| `images/` | Place and scene art, one folder per place |

## Changing the lore

- Edit **`ARTHERIA.md`**, ideally in a pull request so everyone can see what changed.
- When a new story or session adds lore, add its people, places and events to `ARTHERIA.md`, credit the author, and add it to the sources table. The story itself goes in `stories/` or `sessions/`.
- Link to another part of the master by its heading, e.g. `[Aralon](#aralon)`, and to other files from the repo root, e.g. `[Variegated](stories/Variegated.md)`.

## Rules

- **This repo is public.** The DM's Book and raw session exports never go here.
- Strip players' Discord handles (`@Name#1234`) from session text before adding it.
- Where sources disagree, a **⚖ Sources disagree** note names who says what. No version is final.

## Images

`ARTHERIA.md` refers to 65 pictures, `images/imageN.webp`, that aren't in the repo yet. If images or video grow past a few hundred MB, move them to an object store (Cloudflare R2) and link them from there.
