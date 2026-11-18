# ZTM 3D Portfolio — Starter Project

The planning documents behind a **walkable 3D portfolio**: a small first-person world (a rain-soaked Tokyo back alley at 3am, *終電 / Last Train*) where your projects, bio and contact details live on three objects you walk up to.

There is **no code here**. These are the spec files the original was built from, plus its 3D models, so you can build your own version: keep the world or invent a new one, and swap in your own content.

## What's inside

| File | What it is |
|---|---|
| [`CLAUDE.md`](CLAUDE.md) / [`AGENTS.md`](AGENTS.md) | The working guide for an AI coding agent (same content, for Claude Code and other agents): the three content surfaces, source-of-truth rules, stack, structure, and the bar for "done" |
| [`WORLD_BRIEF.md`](WORLD_BRIEF.md) | The world itself: layout, palette, atmosphere, lights, materials, post-processing, navigation and performance budget. Every number the build needs |
| [`CONTENT.md`](CONTENT.md) | The portfolio content: projects, about and contact. **Replace this with your own** |
| [`REFERENCE.md`](REFERENCE.md) | The original project's README: what the finished world looks like, how it's built, and asset credits |
| [`public/`](public) | The 3D models the world uses: three cars on the cross street and a Vespa parked in the alley |

## How to use it

1. Use this template (or clone it) to start a new repo.
2. Rewrite `CONTENT.md` with your own projects, bio and contact channels.
3. Keep `WORLD_BRIEF.md` as-is, or rewrite it for your own world. Keep the structure: three content surfaces, a closed-off horizon, and every value written down.
4. Open the folder in Claude Code (or another agent) and build in stages, starting with the world shell, then the player controller, then each content surface.

Stack the docs assume: Next.js, TypeScript, three.js with react-three-fiber, drei and postprocessing.

## 3D model credits

The models in `public/` are not mine. They keep their original licences, and CC-BY means you must credit the author if you use them.

| Model | Author | License | Source |
|---|---|---|---|
| Mazda RX-7 | IvOfficial | [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/) | [Poly Pizza](https://poly.pizza/m/SnIoWlh7S2) |
| Toyota AE86 | IvOfficial | [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/) | [Poly Pizza](https://poly.pizza/m/ZEFWmOPSgh) |
| Range Rover | IvOfficial | [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/) | [Poly Pizza](https://poly.pizza/m/8zk4o6nALW) |
| Vespa (scooter) | Jasmine Roberts | [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/) | [Poly Pizza](https://poly.pizza/m/blGLclvvdEM) |
