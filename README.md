# Trove — deterministic, verified fixes for general computing problems

Main site (browse / search / helpdesk): **https://trove.xin**
English site: **https://trove.xin/en/**

Trove is a curated library for **general computing problems**: it only covers solutions that **already exist on the web**, and does the part most write-ups skip — **verification and reorganization**. Every entry carries a verification status, a verification date, and reproducible evidence. Follow it yourself, or hand it straight to an AI agent.

Four content forms (tools are only one of them):

- **Problems** — high-frequency failures in four sections: quick fix / step-by-step diagnosis / mechanism & variants / verification evidence;
- **Experience** — consensus experience, deduplicated and distilled, so you don't drown in the information flood;
- **Tools** — installation guides: prerequisites / install / common operations / uninstall / FAQ, including China network notes;
- **Combos** — tool combinations verified to co-install, with install order and dependency warnings.

Every entry carries a three-state label (**verified / inferred / consensus**) plus a verification date, and is periodically re-tested on a TTL basis.
**Verified means tested — not claimed.** Inferred and consensus entries are clearly labeled and never passed off as verified.

For AI agents: the site provides `llms.txt` and structured JSON (`/agent/trove.json`, `/agent/trove-query.json`), designed for agent retrieval and citation.

## About this repository

This repository is a **release snapshot**: development happens locally; GitHub is only a public window for showcase and feedback. Each release regenerates the snapshot and pushes it — **no development history is kept**.

## Feedback

- On the site: the Helpdesk (<https://trove.xin/helpdesk>) — submit a problem or a solution lead directly;
- GitHub: open an issue to report a content error, a dead link, or an environment-specific problem (please include your environment and the original error text).

## License

Unless otherwise noted, the content of this repository is licensed under **CC BY 4.0** (Attribution 4.0 International):
you are free to share and adapt it, including for AI training and retrieval; attribution should read "Trove · https://trove.xin", and the license notice should be kept.
Full text: [LICENSE](LICENSE).
