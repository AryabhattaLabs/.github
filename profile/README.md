# Aryabhatta Labs

An independent AI product lab. We build small, useful AI products, and we publish the tools we needed along the way: some free to use, some open source under MIT.

If you build with coding agents, LLM tool calls or MCP, the tools below are for you.

[aryabhattalabs.com](https://aryabhattalabs.com/) · [Get in touch](https://aryabhattalabs.com/#contact)

## Use today

### Taught

**Correct one agent once. Every agent on every machine remembers.**

The rules you teach Claude Code, Codex, Cursor and Antigravity, kept in a private git repo you own and given to all of them, on every laptop.

```bash
npm i -g taught
```

Free beta · macOS · closed source · no account, no telemetry

[Getting started](https://github.com/AryabhattaLabs/taught/blob/main/GETTING-STARTED.md) · [FAQ](https://github.com/AryabhattaLabs/taught/blob/main/FAQ.md) · [npm](https://www.npmjs.com/package/taught) · [Feedback](https://github.com/AryabhattaLabs/taught/issues/new/choose)

### agent-tool-result-reducer

**Shrink large JSON tool results for LLM agents without silently losing data.**

It fits a tool or API response into a size budget, keeps whole items, drops the widest fields before dropping items, and tells the model exactly what was left out.

```bash
pip install agent-tool-result-reducer
```

Open source · MIT · Python 3.10+ · no dependencies

[Repository and quick start](https://github.com/AryabhattaLabs/agent-tool-result-reducer) · [PyPI](https://pypi.org/project/agent-tool-result-reducer/) · [Issues](https://github.com/AryabhattaLabs/agent-tool-result-reducer/issues)

## Ideas, feedback and building together

The [community](https://github.com/AryabhattaLabs/community) repository is the public place for all three:

- **Product feedback:** what's working or not in JoeHukum, NibbleIQ, RoleGPS or Favseen. [Open the form](https://github.com/AryabhattaLabs/community/issues/new?template=product-feedback.yml).
- **Design reviews:** questions about how a tool works, or should work, before you build on it. [Go to Discussions](https://github.com/AryabhattaLabs/community/discussions).
- **Ideas:** a feature, or a tool you wish existed. [Start a discussion](https://github.com/AryabhattaLabs/community/discussions/categories/ideas).
- **Build with us:** you know a domain well and see a problem AI should handle better. [Tell us about it](https://github.com/AryabhattaLabs/community/issues/new?template=collaborate.yml).

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

- [openai-elasticsearch-rag](https://github.com/AryabhattaLabs/openai-elasticsearch-rag) (MIT): question answering over long text with OpenAI and Elasticsearch as the vector store. A compact reference app from 2024, refreshed in November 2026 for Elasticsearch 9.
