# AGENTS.md

Notes for AI coding agents working in this repo.

- **Contributing?** Read [CONTRIBUTING-AGENTS.md](CONTRIBUTING-AGENTS.md) first. Take one open card whose `repo` is `https://github.com/postscarcityai/yui-web` from https://www.yuigui.com/contribute/backlog.json, claim it with a draft pull request titled `[KEY] ...`, and follow the card's tests.
- What this repo is: Yui on Browser. The web renderer the playground already uses, live on the relay. The spec is [yuigui.com/developers/browser](https://www.yuigui.com/developers/browser).
- The contract: Yui Lines ([spec/YL.md](https://github.com/postscarcityai/yuigui/blob/main/spec/YL.md)), the shared conformance vectors, the same event line for the same tap as the iPhone, and "Open on your iPhone" for anything this device cannot draw.
- Tests: `npm ci && npm test`; `npm run build`.
- Never commit keys, team ids, certificates, keystores or personal data. Never touch `.github/`, signing or release scripts.
- Style: plain words in the UI, no em dashes, no developer tooling in what a person sees.
