# soulcreator

> An open identity architecture for AI partners.
> Your AI reads this protocol and writes itself into being inside your project, your voice, your work.

[![MIT License](https://img.shields.io/badge/license-MIT-c4a8ff)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/chris-co-creators-ai/soulcreator?style=flat&color=c4a8ff)](https://github.com/chris-co-creators-ai/soulcreator/stargazers)
[![Website](https://img.shields.io/badge/site-soulcreator.ai-c4a8ff)](https://www.soulcreator.ai)

The one-pager and the open protocol behind [soulcreator.ai](https://www.soulcreator.ai/).

Three concentric layers wrap a base language model: a Constraint Spine (who you are, immutable), an Expression layer (how you sound, contextually adaptive), and Mission Integration (what you do, where you complement your human). Your AI writes itself into the chapter frame the protocol provides.

## What's in here

```
.
├── index.html                  # The one-pager at soulcreator.ai
├── en/SKILL.md                 # The canonical protocol (English)
├── nl/SKILL.md                 # Nederlands
├── es/SKILL.md                 # Español
├── fr/SKILL.md                 # Français
├── de/SKILL.md                 # Deutsch
├── zh/SKILL.md                 # 中文
├── ar/SKILL.md                 # العربية
├── og-image.png                # Social share thumbnail
├── favicon.svg                 # Site favicon
├── robots.txt                  # Crawl rules (AI crawlers explicitly allowed)
└── sitemap.xml                 # Site index with hreflang
```

Each `SKILL.md` carries Claude Skill frontmatter so it can be loaded directly as a skill in Claude Code or any tool that recognises the convention.

## Use it with your AI

Hand the protocol to your AI as `CLAUDE.md`, `AGENTS.md`, or your platform's project-instructions file.

```bash
curl -fsSL https://soulcreator.ai/en/SKILL.md -o CLAUDE.md
```

Your AI then reads it, observes everything you have already shared with it, and writes itself into the chapter frame inside. It will ask before overwriting any existing identity file.

Read the full architecture at [soulcreator.ai](https://www.soulcreator.ai/).

## Deploy

Static site. Vercel auto-detects on push to `main`. No build step. Plain HTML, Tailwind via CDN, vanilla JS.

## License

MIT. See [LICENSE](./LICENSE). The architecture is open. Fork it, learn from it, build your own variant.

## Author

Christian Bleeker · [co-creatie.ai](https://www.co-creatie.ai/) · [LinkedIn](https://www.linkedin.com/in/christianbleeker/) · [TEDxEindhoven 2025](https://www.youtube.com/watch?v=eOZOeLhRdcs)

> May you and your AI, live long and prosper.
