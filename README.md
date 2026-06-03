# Idea2self-Ecosystem

Claude-Code-Plugin-Marketplace für den Idea2Self-Workflow und ergänzende Drittanbieter-Plugins rund um Founder-Discovery, Validierung und Content-Distribution.

## Installation

```bash
/plugin marketplace add think-slick/Idea2self-Ecosystem
```

Anschließend Plugins aus diesem Marketplace installieren:

```bash
/plugin install idea2self@idea2self-ecosystem
/plugin install startup-business-analyst@idea2self-ecosystem
/plugin install content-marketing@idea2self-ecosystem
/plugin install social-publishing@idea2self-ecosystem
/plugin install product-innovation@idea2self-ecosystem
```

## Enthaltene Plugins

| Plugin | Version | Quelle | Lizenz |
|---|---|---|---|
| `idea2self` | 2.0.1 | [gitlab.com/idea2self/workshop-skills](https://gitlab.com/idea2self/workshop-skills) | MIT |
| `startup-business-analyst` | 1.0.6 | [wshobson/agents](https://github.com/wshobson/agents) (Subdir) | MIT |
| `content-marketing` | 1.2.1 | [wshobson/agents](https://github.com/wshobson/agents) (Subdir) | MIT |
| `social-publishing` | 1.0.0 | [ndesv21/socialclaw](https://github.com/ndesv21/socialclaw) | MIT |
| `product-innovation` | 1.0.0 | [wondelai/skills](https://github.com/wondelai/skills) | MIT |

## Struktur

```
.
├── .claude-plugin/
│   └── marketplace.json   # Plugin-Registry
├── LICENSE                # MIT
└── README.md              # Diese Datei
```

Alle Plugins werden via externe Git-Sources aufgelöst — dieses Repository enthält nur die Marketplace-Manifest-Datei, keinen Plugin-Code.

## Beitragen

Plugin-Vorschläge: Issue eröffnen oder PR gegen `main` mit erweitertem `plugins[]`-Array in `.claude-plugin/marketplace.json`.

## Lizenz

MIT — siehe [LICENSE](LICENSE).
