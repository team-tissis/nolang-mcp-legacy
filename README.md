# NoLang

[NoLang](https://no-lang.com) is an AI video generation service by Mavericks, inc.: describe a video in plain words
and it makes one with a script, narration, pictures and BGM.

## Use NoLang from an AI agent

**Claude Code** — install the official plugin (no API key, no Python):

```
claude plugin install nolang --marketplace mvrks-inc/nolang-plugin
```

**Codex**:

```
codex plugin marketplace add mvrks-inc/nolang-plugin
codex plugin add nolang@nolang
```

Restart Claude Code / Codex, then ask "Make a 60-second video about …". The first time, you sign in to your NoLang
account in the browser.

**claude.ai, ChatGPT and other clients without a shell** — add the MCP connector `https://api.no-lang.com/agent/mcp`
and sign in with your NoLang account.

Details: https://github.com/mvrks-inc/nolang-plugin

---

This package (`nolang-mcp`) is superseded by the plugin above. New setups should use the plugin or the connector.
