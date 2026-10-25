# Aixgo

**The AI Agent Framework That Ships in <20MB**

Open-source tools for Go teams. Code turns your issues into pull requests inside your own GitHub Actions. Your secrets stay with you, and a human always merges.

[Start at aixgo.dev](https://aixgo.dev) for docs and product pages. This org holds the source.

## Before you try it

- Code runs on your runners with your secrets.
- A human always merges.
- All projects are open source, under Apache-2.0 or MIT, so you can read what runs.
- Each project below has a plain status: Beta, Early, or Scaffold.

## Projects

| Project | What it does for you | Status |
| --- | --- | --- |
| [code](https://github.com/aixgo-dev/code) | File an issue, get a pull request. Add the `ax:go` label to start. It runs in your own GitHub Actions with your secrets, and a human always merges. Engines: Codex on Azure, Gemini on Vertex. Claude works locally. | Beta |
| [aixgo](https://github.com/aixgo-dev/aixgo) | Build multi-agent systems in Go. Define the topology in YAML, switch between 8+ LLM providers, and ship one binary. | Released |
| [aixgate](https://github.com/aixgo-dev/aixgate) | Keep `.env`, `~/.aws`, and `~/.ssh` out of reach of coding agents. A deny-by-default sandbox in one binary. macOS today, Linux planned. | Early (v0.1) |
| [sync](https://github.com/aixgo-dev/sync) | Keeping your agents in sync | Early |
| [sync-mcp](https://github.com/aixgo-dev/sync-mcp) | Use Sync from any MCP client over stdio. | Early |
| [cli](https://github.com/aixgo-dev/cli) | Local coding CLI for the Aixgo family, with a Sync client. | Scaffold, not ready for use |

Also here: [web](https://github.com/aixgo-dev/web) (source for aixgo.dev), [skills](https://github.com/aixgo-dev/skills) (a curated catalog of agent skills), and [homebrew-tap](https://github.com/aixgo-dev/homebrew-tap) (install aixgate with Homebrew).

## Try it

Pick the one that fits.

- **Turn an issue into a pull request:** follow the [Code setup guide](https://github.com/aixgo-dev/code/blob/main/docs/setup.md) or read [aixgo.dev/code](https://aixgo.dev/code).
- **Build an agent system in Go:** run the [aixgo quick start](https://github.com/aixgo-dev/aixgo#quick-start).
- **Fence in a coding agent:** see the install steps in the [aixgate README](https://github.com/aixgo-dev/aixgate#readme).
- **Browse everything:** [aixgo.dev/docs](https://aixgo.dev/docs).

If it helps, a star makes it easier for other Go developers to find.

## Get involved

Bug reports, ideas, and pull requests are welcome. Open an issue in the repo that fits, or start with the [contributing guide](https://github.com/aixgo-dev/aixgo/blob/main/docs/CONTRIBUTING.md). Report security problems privately, following the `SECURITY.md` in each repo.

## License

Code, Sync, sync-mcp, and the CLI are Apache-2.0. aixgo, aixgate, and the site are MIT. Each repo has its own `LICENSE` file.
