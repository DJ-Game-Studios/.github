# DJ Game Studios public style guide

This guide governs organization profiles, public repositories, release notes, and other visitor-facing GitHub text.

## Brand hierarchy

- **DJ Game Studios** is the studio and publisher identity.
- **Helix** is the primary universe and product family.
- **Helix MMORPG** is the flagship and primary development focus.
- **Helix 2000** and **Helix Card Online** are active adjacent products.
- **DJ-Engine** is an independent engine—not the name of the Helix universe.
- Public infrastructure projects are genuine studio work, but they are not flagship games.

## Voice

Write with a dry, specific, self-aware voice. Concrete facts and images beat abstract adjectives.

Do:

- explain what something is, who it serves, and its current maturity;
- distinguish a game, tool, experiment, release channel, and legacy archive;
- use “private development,” “community test,” or “working title” when those are the honest terms;
- put installation or download instructions before implementation history;
- state limitations plainly.

Avoid:

- generic MMORPG hype;
- inflated or frozen test/entity/commit counts on evergreen pages;
- internal box names, local filesystem paths, agent assignments, or dated handoff notes;
- presenting a distribution repository as the source or current product authority;
- links that send public visitors into private repositories without explanation;
- “coming soon” claims without an approved public release commitment.

## Visual direction: Terminal Grove

The public house style is a restrained cyber-forest: **nature-forward, minimal cyberism, grown rather than stacked, bold without sacrificing readability**.

| Role | Color |
| --- | --- |
| Deep forest | `#060C0A` |
| Raised forest | `#12201A` |
| Primary text | `#EAFFF4` |
| Secondary text | `#B3CABD` |
| Bioluminescent mint | `#01FFC3` |
| Cyan | `#00E5FF` |
| Warm amber | `#FFB454` |
| Brass | `#CAA35E` |
| Leaf | `#7EC77A` |
| Reserved magenta | `#FF2BBF` |

Use mint for attention and selection; amber for engaged or active states; brass for restrained art-deco structure. Magenta is an accent, not the entire identity.

Prefer clean mono or system typography on GitHub. Do not use decorative Unicode characters as a substitute for layout or hierarchy.

## Repository presentation

A public README should normally answer these questions in order:

1. What is this?
2. Is it current, experimental, maintained, or legacy?
3. How does someone install, download, or use it?
4. What platforms and versions are supported?
5. What limitations should they expect?
6. Where should bugs or security issues go?
7. What is the license?

Release repositories should link to the exact recommended tag when GitHub’s automatic “latest” release points at CI or test artifacts.

## Link policy

- Prefer the `DJ-Game-Studios` namespace for studio-owned public links.
- Link exact releases for recommended downloads.
- Describe private dependencies as private; do not produce broken pseudo-public links.
- Use [djmsqrvve.com](https://djmsqrvve.com), [YouTube](https://youtube.com/@djmsqrvve), and [Twitch](https://twitch.tv/djmsqrvve) as the canonical public channels.
