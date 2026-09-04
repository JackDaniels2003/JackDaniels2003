<p align="center">
  <img src="./assets/banner.svg" width="100%"/>
</p>

# Design System · Daniel Teodoro Profile

A single, consistent visual identity across every file in this project.
Dark mode only. Engineered, restrained, blue. Inspired by Stripe, Vercel, Linear, Cloudflare and Apple Developer. Never cyberpunk, never childish, never overloaded.

<img src="./assets/divider.svg" width="100%"/>

## Color tokens

| Token            | Hex        | Usage                                            |
|------------------|------------|--------------------------------------------------|
| `--bg-deep`      | `#020617`  | Page / SVG base background                        |
| `--bg-panel`     | `#0F172A`  | Cards, panels, terminal body                     |
| `--bg-elevated`  | `#111827`  | Title bars, elevated surfaces                    |
| `--blue-900`     | `#1E3A8A`  | Borders, grid lines, deep gradient stops         |
| `--blue-600`     | `#2563EB`  | Primary accent, rails, glow rings                |
| `--blue-500`     | `#3B82F6`  | Icons, strokes, primary highlight                |
| `--blue-400`     | `#60A5FA`  | Bright accent, pulses, active labels             |
| `--text-strong`  | `#F8FAFC`  | Headlines on dark                                |
| `--text-body`    | `#E2E8F0`  | Primary body text                                |
| `--text-muted`   | `#94A3B8`  | Secondary text, captions                         |
| `--text-faint`   | `#475569`  | Tertiary text, metadata                          |

<img src="./assets/divider.svg" width="100%"/>

## Typography

- **Display / UI:** `Segoe UI, Helvetica, Arial, sans-serif`
- **Code / terminal:** `SF Mono, Cascadia Code, Courier New, monospace`
- **Tracking:** generous letter-spacing on headings (`6–8`) for a premium, engineered feel.
- **Weight:** `700` for names and section headers, `600` for labels, `400` for body.

<img src="./assets/divider.svg" width="100%"/>

## Motion principles

- **Subtle over flashy.** Animations breathe (4–12s loops), they don't flash.
- **Purposeful pulses.** A travelling dot signals flow (workflow, dividers), not decoration.
- **Soft glow.** Gaussian blur merges, never hard neon.
- **SMIL-based.** All animation uses native SVG `<animate>` / `<animateTransform>` so it renders inside GitHub's `<img>` sandbox (no JavaScript, since GitHub strips it).

<img src="./assets/divider.svg" width="100%"/>

## Asset inventory

| File                     | Role                                              |
|--------------------------|---------------------------------------------------|
| `assets/banner.svg`      | Hero: animated gradient, grid, sweeping lines    |
| `assets/divider.svg`     | Reusable section divider with travelling pulse    |
| `assets/terminal.svg`    | Minimal fake terminal with typed-in lines         |
| `assets/workflow.svg`    | Animated 7-stage engineering pipeline             |
| `assets/impact.svg`      | 4-stat impact bar (unused, removed from the README, kept in case it's needed later) |
| `assets/background.svg`  | Subtle geometric / dotted backdrop                |
| `assets/icons/*.svg`     | Line-style tech-stack card icons                  |

<img src="./assets/divider.svg" width="100%"/>

## Rules

1. **No badge spam.** Technologies live in designed cards, not in walls of shields.
2. **No clichés.** Avoid "passionate developer", "coffee", "turning ideas into reality".
3. **Every section earns its place.** The positioning is *someone who analyses a business problem and delivers a technological solution*, not *someone who writes code*. A section that doesn't support that gets cut.
4. **Problem before stack.** Project cards open with the problem and what changed, and close with the technologies. Never the other way around.
5. **One identity.** Banner, dividers, icons and cards all share the same palette and stroke language.
6. **Confidential by default.** Company systems stay private: the profile shows *what* and *how*, never the source. Personal projects are the exception, and are labelled as such.
7. **No horizontal scroll.** The profile renders in a narrow column, so wide markdown tables get a scrollbar. Structured content goes in bullet lists (`- **Label:** description`) instead. Long vertically is fine, wide is not.
8. **Plain, humble prose.** No em-dashes, use a colon or a comma. No standalone declarative sentences that read as proclamations in the first-person sections.

<img src="./assets/divider.svg" width="100%"/>

## README structure

`README.md` (English) and `README_pt.md` (Portuguese) are kept in lockstep: every structural change lands in both. Shared SVGs keep their English labels in both versions, so only the surrounding prose is translated.

Current section order:

1. Banner, language switch, role tags
2. **The engineer behind the systems:** short bio, problem-first framing
3. **What I do:** six areas in two columns
4. **Current mission:** blockquote
5. **How I work:** the `workflow.svg` pipeline
6. **Featured platforms:** flagship card at full width, then a 2x2 grid of the other company systems
7. **Personal project:** Spotter, explicitly separated from company work
8. **Tech stack:** icon row
9. **AI in my engineering workflow:** text plus `terminal.svg`
10. **GitHub activity:** external stat services
11. **Contact:** badges

A system that started as its own project and was later absorbed into a bigger one still gets its own card, with the absorption told as part of its story.

<img src="./assets/divider.svg" width="100%"/>

## How GitHub renders these assets

- SVGs referenced with relative paths (`./assets/...`) render in the profile README.
- SMIL animations and inline `<style>`/gradients animate inside the `<img>` sandbox.
- External stat services (stats, streak, activity graph, snake) are themed with the tokens above via URL query params.
- The snake SVG is generated by the Action in `.github/workflows/snake.yml`, published to the `output` branch, and consumed from its raw URL.
