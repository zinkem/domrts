# domrts

A physics-based RTS game built with LÖVE2D.

## About

This project was **vibe coded** — built primarily through AI-assisted development with Claude. The codebase represents a collaboration between human direction and AI implementation, demonstrating what's possible when you treat AI as a development partner rather than just a tool.

**Use this as a launchpad for your own AI-driven game development.** The architecture is designed to be readable and extensible, with clear separation of concerns that makes it easy for AI assistants to understand and modify.

## Stats

- **28,000+ lines** of Lua code across 52 files
- **14 documentation files** including retrospectives and planning docs
- Built from scratch with custom physics, pathfinding, and AI systems

## Features

- Unit selection and command system
- Peon workers with resource gathering
- Combat mechanics with projectiles
- Multiple biomes and terrain types
- AI-driven unit behaviors
- Isometric unit rendering and drawing system

## Technical Highlights

- **Shader pipeline** — Palette-based rendering system for unit colorization
- **Procedural map generation** — Random terrain with configurable biomes and resource distribution
- **Build order system** — Structured unit/building production with logging to help AI assistants design build orders
- **Sprite caching** — Canvas-based caching for efficient isometric rendering
- **Quadtree spatial indexing** — Optimized collision and unit lookup
- **Flow field pathfinding** — Efficient multi-unit navigation

## AI Development Ready

The codebase includes infrastructure for AI-assisted development:

- **Git hooks** for automatic context injection
- **Retrospectives** documenting optimization attempts and learnings
- **Benchmark files** for performance testing
- **Structured logging** to help AI assistants understand game state

## Running

Requires [LÖVE2D](https://love2d.org/) (version 11.x or later).

```bash
love .
```

## More

- [zinkem.com](https://zinkem.com) — My portfolio and dev blog
- [Bluesky](https://bsky.app/profile/zinkem.bsky.social) — Updates and thoughts
- [BEEF ARENA](https://beefarena.com) — My shipped game on Steam

## License

MIT
