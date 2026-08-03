# Cognito Inc.

> Open-source infrastructure for browser-based proxy systems.

Cognito Inc. builds the underlying tooling for browser proxy systems: proxy engines, encrypted transports, Wisp servers, documentation, and developer tooling. Our goal is to make this ecosystem easier to build on, deploy, and maintain.

---

## What We Build

### 🔥 Ember
A high-performance Wisp server written in Rust. Supports WebSocket-based TCP/UDP multiplexing with connection migration, adaptive buffering, and built-in metrics. Designed as a stable, production-grade server backend for the proxy ecosystem — built on stable Rust rather than nightly.

### 🔧 Cognito Workshop
A web-based boilerplate generator for proxy projects. Choose an engine, transport, and deployment target, and get a working, correctly wired codebase to start from.

### 📚 Transit
A maintained documentation set for the browser proxy ecosystem, developed as an improved alternative to the TitaniumNetwork docs — focused on active projects, first-time developer onboarding, and removing outdated or abandoned references.

### 🛡️ ProxyKit
*(In development)* A client-side, open-source counterpart to Cognito Workshop, for generating proxy project boilerplate without the hosted service.

---

## Our Stack

| Layer | Technology |
|-------|-----------|
| Proxy Engine | Scramjet |
| Transport | EpoxyTransport, CurlTransport |
| Protocol | Wisp v1.2 |
| Server | Ember (Rust), epoxy-server, wisp-server-node |
| Middleware | Reflux |
| Docs | Astro / Starlight |

---

## Projects

| Project | Status | Description |
|---------|--------|-------------|
| [Ember](https://github.com/cognito-workshop/ember) | Active | Rust Wisp server |
| [Transit](https://github.com/cognito-workshop/transit) | Planning | Proxy development docs |
| [ProxyKit](https://github.com/cognito-workshop/proxykit) | Planning | Open-source boilerplate tool |

---

## Why This Exists

The browser proxy ecosystem has solid underlying technology — Scramjet, Wisp, EpoxyTransport — but development on top of it has historically meant piecing together fragmented, outdated documentation and copy-pasting boilerplate from disconnected repositories.

Cognito Inc. addresses that directly:

- **Ember** brings the server layer to production-grade stability
- **Cognito Workshop** removes repetitive setup work
- **Transit** consolidates scattered documentation into a single, maintained reference

---

## Contributing

Contributions are welcome. Each project maintains its own repository and contribution guidelines.

- **Ember** — Rust, Wisp protocol implementation, performance optimization
- **Cognito Workshop** — Templates, transport integrations, deployment targets
- **Transit** — Documentation, guides, tutorials

---

## Community

- **Discord:** [Cognito Inc.](https://discord.gg/9KKmJQzEuu)

---

## License

All projects are open source under the MIT License unless otherwise noted.
