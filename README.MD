# Shivam

I write developer tools, inference services, and self-hosted software, mostly in TypeScript, Python, and Go.

## Recent projects

### [Sonarr Anime List Builder](https://github.com/ShivamB25/sonarr-anime-list-builder)

Builds seasonal anime import lists for Sonarr from AniList and MyAnimeList data, mapped to TVDB IDs. Runs on Cloudflare Workers/D1 or self-hosted Bun/SQLite. Recent work fixes seasonal coverage and makes source-sync failures visible.

### [Komga TypeScript SDK](https://github.com/ShivamB25/komga-sdk-typescript)

A generated SDK for the Komga media-server API. Uses native Fetch with zero runtime dependencies, isolated clients, typed responses, and explicit error results.

### [IndicConformer ASR](https://github.com/ShivamB25/indicconformer-realtime-asr)

A FastAPI speech-to-text service with REST and streaming WebSocket APIs, OpenAI-compatible endpoints, and voice activity detection. Recent changes reduce Silero VAD processing overhead and fix cancellation of queued VAD jobs.

### [Simplismart Deployment CLI](https://github.com/ShivamB25/simplismart-deployment-cli)

Deployment lifecycle commands, health checks, and timezone-aware scaling schedules. Idempotent start/stop operations and JSON output let the same commands work interactively or in scripts.

### [bend-json](https://github.com/ShivamB25/bend-json)

An experimental JSON parser and encoder written in Bend 2. Preserves number spelling and duplicate object members, validates Unicode, and enforces parsing and output limits. Pre-release; native-backend verification is still unresolved.

## Merged upstream contributions

- **[oh-my-pi](https://github.com/can1357/oh-my-pi/pull/13485):** stopped repeated OAuth refreshes when a provider rejects a fresh token; fixed account pinning during concurrent credential removal.
- **[anacrolix/dht](https://github.com/anacrolix/dht/pull/86):** fixed a remotely triggerable crash on malformed DHT queries, alongside protocol, traversal, and concurrency bugs.
- **[gotext](https://github.com/leonelquinteros/gotext/pull/141):** corrected catalog escaping, plural handling, and locale lookup; prevented generated files from escaping the configured output directory.
- **gdu:** [preserved directory statistics across JSON export/import](https://github.com/dundee/gdu/pull/603) and [made Ctrl+C stop a scan without losing navigable partial results](https://github.com/dundee/gdu/pull/606).

## Open upstream work

- **[CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI/pull/3160)** — authentication and protocol fixes covering localhost checks, OAuth callbacks, token-file permissions, and OpenAI Responses translation. Not yet merged.

## Contact

[LinkedIn](https://www.linkedin.com/in/shivam-bansal-daesira/) · [GitHub](https://github.com/ShivamB25)
