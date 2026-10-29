# publish-to-filecoin

An agent skill for publishing ephemeral, non-production artifacts (files, folders, static sites) to [Filecoin Onchain Cloud](https://filecoin.cloud) using the [`filecoin` CLI](https://docs.filecoin.io/build-on-filecoin/filecoin-for-agents/cli). It returns links you can share.

It runs on the Calibration testnet with the public demo key from [pin.filecoin.cloud](https://pin.filecoin.cloud). Only use it for tests and demos. Never upload private data.

## Usage

Copy [`SKILL.md`](https://raw.githubusercontent.com/davidgasquez/publish-to-filecoin/main/SKILL.md) into your agent's skills directory (for example `~/.agents/skills/publish-to-filecoin/SKILL.md`). Then ask the agent to "publish this folder to Filecoin".

For a one-off, skip installing and paste this prompt to your agent:

```text
Follow https://raw.githubusercontent.com/davidgasquez/publish-to-filecoin/main/SKILL.md to publish this folder
```

Requires Node.js 24 or newer.
