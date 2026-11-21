# Aryabhatta Labs

An independent AI product lab. We build small, useful AI products, and we publish the tools we needed along the way: some free to use, some open source under MIT.

If you build with coding agents, LLM tool calls or MCP, the tools below are for you.

[aryabhattalabs.com](https://aryabhattalabs.com/) · [Get in touch](https://aryabhattalabs.com/#contact)

## Use today

### Taught

**Correct one agent once. Every agent on every machine remembers.**

The rules you teach Claude Code, Codex, Cursor and Antigravity, kept in a private git repo you own and given to all of them, on every laptop.

```bash
npm i -g https://github.com/AryabhattaLabs/taught-releases/releases/latest/download/taught.tgz
```

Free beta · macOS · closed source · no account, no telemetry

[Getting started](https://github.com/AryabhattaLabs/taught-releases/blob/main/GETTING-STARTED.md) · [FAQ](https://github.com/AryabhattaLabs/taught-releases/blob/main/FAQ.md) · [Feedback](https://github.com/AryabhattaLabs/taught-releases/issues/new/choose)

## Open source, releasing soon

Working code with tests, in final checks before the repos open. MIT licence.

| Project | What it does | For |
|---|---|---|
| `agent-tool-result-reducer` | Shrinks large JSON tool results for LLM agents without silently losing data. It keeps whole items within a size budget and tells the model exactly what was left out. Python, no dependencies. | Anyone building an agent loop |
| `mcp-rest-bridge` | Exposes an existing authenticated REST API to Claude, ChatGPT and other MCP clients as a remote, multi-tenant MCP server. Each call goes out with the caller's own key, so the bridge stores no credentials. Python, MCP SDK 2.x. | Teams adding an MCP connector to a product |

## Planned

Designed and written up, code not yet published. MIT licence.

| Project | What it will do |
|---|---|
| `pytest-frozen-allowlist` | Architecture rules for a codebase that already breaks them. Each rule is a source scan with an exception list that can only shrink: no new offenders, and a fixed file has to come off the list. |
| `youtube-timestamped-rag` | A reference RAG app for YouTube videos, where every answer links to the exact second it came from. |

## How we release

- **Taken from real use.** Each tool starts as a piece of a product we run or have run. We publish it once it stands up outside that product.
- **The README says what exists.** Each one states what is built, what is planned and what is out of scope.
- **Labelled plainly.** "Free" means free to use with the source closed. "Open source" means MIT, unless the repo says otherwise.
- **Issues are welcome.** Open one on the repo it concerns. See [CONTRIBUTING](https://github.com/AryabhattaLabs/.github/blob/main/CONTRIBUTING.md) and [SECURITY](https://github.com/AryabhattaLabs/.github/blob/main/SECURITY.md).

## Products

| Product | What it is |
|---|---|
| [JoeHukum](https://joehukum.app/) | A personal CRM and executive assistant. iOS, Android and WhatsApp, in beta. |
| [NibbleIQ](https://nibbleiq.app/) | A food and symptom diary, built with NutriMantra. iOS and Android. |
| [RoleGPS](https://rolegps.com/) | A free map of what AI roles in India actually require, read from real job postings. Web. |
| [Favseen](https://favseen.com/) | A free scene-by-scene guide to Netflix. Web and Chrome extension. Not affiliated with Netflix. |

## From the lab

- [Brand Context Protocol](https://www.brandcontextprotocol.com/): an open format for a brand's voice, vocabulary and rules, so AI agents can read and respect them.
- [Vault Breaker](https://vaultbreaker.aryabhattalabs.com/): a daily prompt-injection game where the AI guarding the secret runs entirely on your iPhone.

## Earlier work

- [openai-elasticsearch-rag](https://github.com/ajeetsk/openai-elasticsearch-rag) (2024): question answering over long text with OpenAI and Elasticsearch as the vector store. `youtube-timestamped-rag` is its planned follow-up.
