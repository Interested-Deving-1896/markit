[update-readmes]   Mode: rewrite — migrating to template structure...
# markit

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/markit)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/markit.git
cd markit
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


```bash
markit init                              # Create .markit/config.json
markit config show                       # Show resolved settings
markit config get llm.model              # Get a value
markit config set llm.provider anthropic # Switch provider
markit config set llm.apiKey sk-...      # Set a value
```

`.markit/config.json`:

```json
{
  "llm": {
    "provider": "openai",
    "apiBase": "https://api.openai.com/v1",
    "apiKey": "sk-...",
    "model": "gpt-4.1-nano",
    "transcriptionModel": "gpt-4o-mini-transcribe"
  }
}
```

Env vars override config. Each provider checks its own env vars first:

| Provider | Env vars | Default model |
|----------|---------|---------------|
| `openai` | `OPENAI_API_KEY`, `MARKIT_API_KEY` | `gpt-4.1-nano` |
| `anthropic` | `ANTHROPIC_API_KEY`, `MARKIT_API_KEY` | `claude-haiku-4-5` |

---

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/markit`](https://github.com/Interested-Deving-1896/markit) and mirrored through:

```
Interested-Deving-1896/markit  ──►  OpenOS-Project-OSP/markit  ──►  OpenOS-Project-Ecosystem-OOC/markit
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/markit/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
