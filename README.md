I work on LLM security, watermarking, and evaluation, and build tooling for LLM agents.
The repositories below are public; larger write-ups are on [uiseoya.com](https://uiseoya.com).
Also on [Hugging Face](https://huggingface.co/euisuh) and [LinkedIn](https://linkedin.com/in/euisuh).

## Security

- [cheoyong](https://github.com/euisuh/cheoyong): policy layer for LLM agent tool calls that allows, denies, rate-limits and audits calls before they execute.
- [gumiho](https://github.com/euisuh/gumiho): benchmark for indirect prompt injection against tool-using LLM agents (in progress).
- [CVEFixesUtil](https://github.com/euisuh/CVEFixesUtil): builds vulnerable/fixed function pairs from the CVEfixes dataset and benchmarks open-weight code LLMs on detecting the vulnerability.

## Evaluation

- [modelscan-eval](https://github.com/euisuh/modelscan-eval): runs ML supply-chain scanners over one labeled synthetic corpus and reports detection rate, false positives and robustness to pickle evasion.
- [trustmark-soft-binding-demo](https://github.com/euisuh/trustmark-soft-binding-demo): small CPU reproduction of TrustMark overwrite behavior and a check of c2patool soft-binding discovery.
- [audio-command-span-gating-demo](https://github.com/euisuh/audio-command-span-gating-demo): small CPU demo comparing word-level and utterance-level AudioSeal gating of voice-agent commands, on synthetic speech.

## Tooling

- [nginx-proxy-manager-mcp](https://github.com/euisuh/nginx-proxy-manager-mcp): MCP server for managing Nginx Proxy Manager proxy hosts, Let's Encrypt certificates and access lists.
- [caddy-mcp](https://github.com/euisuh/caddy-mcp): MCP server for inspecting and operating Caddy through its admin API; mutating tools default to dry run.
- [agent-statusline](https://github.com/euisuh/agent-statusline): fixed-width Claude Code statusline scripts.
