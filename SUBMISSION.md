# Awesome Tarot — Distribution Strategy

## Part 1 — Publish your own awesome list

### Push to GitHub
```bash
cd awesome-tarot
git init
git add README.md
git commit -m "Initial commit"
gh repo create gokimedia/awesome-tarot --public --source=. --push
```

### Get "Awesome" badge approved
1. Read https://github.com/sindresorhus/awesome/blob/main/contributing.md
2. Ensure list has 20+ quality entries (✅ done)
3. Add to https://github.com/sindresorhus/awesome via PR
4. Once merged, gets listed on the root awesome list (DR 95)

### Distribution
- Submit to https://github.com/trending topic:tarot
- Add topic tags: `awesome`, `awesome-list`, `tarot`, `divination`, `oracle-cards`
- Star the list from multiple accounts

## Part 2 — Submit Deckaura to EXISTING awesome lists

### Astrology
- https://github.com/topics/astrology — find curated lists, PR entries
- `awesome-astrology` (if exists) or create `awesome-astrology`

### Divination
- `awesome-divination` — PR adding deckaura.com
- `awesome-esoteric` — similar

### Free Public APIs
- https://github.com/public-apis/public-apis — PR to add Tarot API
  - Category: Personality (tarot/divination sits here)
  - Entry: `| Deckaura Tarot | Complete 78-card tarot meanings API | No | Yes | Yes |`
- https://github.com/public-api-lists/public-api-lists — same PR

### Awesome MCP Servers
- https://github.com/punkpeye/awesome-mcp-servers
- https://github.com/wong2/awesome-mcp-servers
- Entry: `- [Tarot](https://github.com/gokimedia/tarot-mcp-server) — 78-card tarot deck meanings and spreads. Powered by Deckaura.`

### Awesome Claude Skills
- https://github.com/awesome-claude-code/awesome-claude-code (if exists) — PR
- https://github.com/hesreallyhim/awesome-claude-code (alternative)

### Awesome Next.js
- https://github.com/unicodeveloper/awesome-nextjs
- Entry under "Starters": `- [Tarot Reading Starter](https://github.com/gokimedia/tarot-reading-starter) — Next.js 16 tarot app template.`

## Expected backlinks per PR
Each accepted PR gives:
- Permanent entry in README visible on GitHub (DR 95)
- GitHub search result for the keyword
- Many awesome lists are mirrored to Gitiles, GitLab, sourcehut — amplification
