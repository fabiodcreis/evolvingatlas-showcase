# EvolvingAtlas — engineering overview

This document presents engineering themes that can be discussed publicly. It is not the application's internal design specification.

## Product challenges

### 1. Time-aware geography

Geopolitical maps are not static. The product needs to represent changes in ownership, boundaries and locations across different years, while providing an interface that is approachable to nontechnical users.

### 2. Interactive map editing

Editing geographic content introduces UX challenges: selecting and splitting regions, showing precise locations, managing drawing tools, and making interactions understandable at different zoom levels.

### 3. Maintainable product development

EvolvingAtlas is developed iteratively. Product work involves balancing feature delivery with code quality, accessibility, security and regression testing.

### 4. AI-assisted engineering

AI coding tools support selected development activities. Product decisions, review, verification and release responsibility remain with the human project owner. This workflow is distinct from the user-facing editor, which does not automatically generate maps using AI.

## Public technology overview

- Frontend: React and TypeScript
- Data: PostgreSQL and Supabase
- Hosting and delivery: Cloudflare
- Version control and collaboration: GitHub

This is intentionally a summary, not an exhaustive list of services or implementation details.

## What this showcase does not disclose

- Secrets, API keys and environment variables
- Internal database schemas, row-level security definitions or migrations
- Private infrastructure endpoints or production configurations
- Internal prompts, agent policies or proprietary source code

## Learn more

- [Product](https://evolvingatlas.com/)
- [Editor](https://evolvingatlas.com/editor?base=blank)
- [Public release notes](https://evolvingatlas.com/versions)
