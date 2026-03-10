# CLAUDE.md — VeriCorp Blog

## Rules
- This blog is a subsidiary of Prumo Holdings. NEVER reference Prumo, AI agents, councils, LangGraph, or internal infrastructure.
- All content must pass the Content Validation Pipeline before publishing (preflight + quality gate + redteam gate).
- Blog posts are published as Hugo markdown in `content/posts/`.
- Deploy: push to main → GitHub Actions → Cloudflare Pages.

## Structure
- `hugo.toml` — Hugo configuration
- `content/posts/` — Blog posts (markdown with frontmatter)
- `layouts/partials/` — Custom partials (analytics, newsletter)
- `.github/workflows/deploy.yml` — CI/CD pipeline

## Content Guidelines
- Language: en
- Target audience: developers and technical decision-makers
- Tone: informative, practical, slightly opinionated
- Every post must include: title, date, tags, draft status in frontmatter
- Maximum 5 tags per post
- Include code examples where relevant
- No promotional language or marketing speak
