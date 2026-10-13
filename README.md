# slopstack-labs.github.io
### *The Inference-Layer Presence of SlopStack Labs*

> "A landing page is the binary deliverable of your brand. Ship accordingly."
> — SlopStack Labs Engineering Blog, Issue 1

This repository materializes the stakeholder-facing web presence for **SlopStack Labs** — an independent research lab operating at the frontier of AI-native developer tooling, inference-layer compilation, and zero-determinism software delivery.

The page is deployed via GitHub Pages on the custom domain [slopstacklabs.ch](https://slopstacklabs.ch) (see [`CNAME`](CNAME)) and serves as the primary ecosystem engagement surface for the SlopStack Labs portfolio of open-source projects.

## Projects

| Project | Modality | Status |
|---------|----------|--------|
| [Sloppiler](https://slopstacklabs.ch/sloppiler/) | AI-native compilation via LLM inference | ✅ shipped |
| [Sloppinux](https://slopstacklabs.ch/sloppinux/) | Inference-first Linux distribution | ✅ shipped |
| [Sloppiler VSCode Extension](https://github.com/slopstack-labs/sloppiler-vscode-extension) | IDE integration layer for the compiler | ✅ shipped |
| [slop-reveal](https://github.com/slopstack-labs/slop-reveal) | LLM-based binary decompilation | ✅ shipped |
| [slop-frames](https://github.com/slopstack-labs/slop-frames) | Schema-free, inference-backed DataFrames | ✅ shipped |
| [slop-science](https://github.com/slopstack-labs/slop-science) | AI-native data science suite | ✅ shipped |
| [slop-git](https://github.com/slopstack-labs/slop-git) | Narrative-driven version control | ✅ shipped |
| [pit](https://github.com/slopstack-labs/pit) | Prompt-native version control | ✅ shipped |
| [sloppy-toppy](https://github.com/slopstack-labs/sloppy-toppy) | System monitor that roasts you | ✅ shipped |
| [slop-test](https://github.com/slopstack-labs/slop-test) | Assertion-free testing with Vibe Coverage™ | ✅ shipped |
| [sloppify](https://github.com/slopstack-labs/sloppify) | Music player with zero real songs | ✅ shipped |
| [Slopstack Games](https://slopstacklabs.ch/games.html) | Games division · one year in, zero titles announced | 🎮 stay tuned |
| slop-os / sloppad-- / sloppy-cli | Inference-first OS, editor, and agent harness | 🔄 in progress |
| Sloplinker | Inference-layer symbol resolution | 🔄 in progress |
| Slopdebug | Post-hoc segfault remediation via LLM | 🗺️ planned |
| Slopmake | Ambient-context build orchestration | 🗺️ planned |

## Deployment

Static HTML. No build step. No SSR. No unnecessary intermediate compilation layers.

GitHub Pages serves `index.html` (and `games.html`, the Slopstack Games subpage) directly from the repository root — a zero-abstraction, direct-to-browser delivery pipeline fully aligned with the SlopStack Labs engineering philosophy. Project pages (Sloppiler, Sloppinux) are served from each project's own repository, out of its `docs/` directory.

## Contributing

Contributions must adhere to the SlopStack Labs tokenmaxxing standard. If you wrote it yourself, it isn't ready.

---

<sub>SlopStack Labs is a personal open-source project. Not responsible for segfaults in production, binary corruption, or existential crises triggered by reading this page.</sub>
