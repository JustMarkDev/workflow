# Skills catalog

Add each reusable repository skill as an immediate child directory of this folder. Every skill directory must contain a `SKILL.md` with non-empty `name` and `description` frontmatter fields; scripts, references, assets, and agent metadata may live beside it.

Migration copies valid, non-colliding skill directories to the destination's `.agents/skills/` directory. A destination skill with the same metadata `name` wins, even when its directory name differs. Invalid kit skills are skipped and reported. This README is catalog documentation and is not migrated.
