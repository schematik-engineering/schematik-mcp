# Schematik MCP server

Search electronics parts and step-by-step hardware build guides from [Schematik](https://www.schematik.io) in Claude, ChatGPT, Cursor, VS Code or any MCP client.

Free, read-only, no sign-in.

```
https://www.schematik.io/mcp
```

## Add it

| Client | How |
|---|---|
| Claude | [Add to Claude](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Schematik&connectorUrl=https%3A%2F%2Fwww.schematik.io%2Fmcp) |
| Claude Code | `claude mcp add --transport http schematik https://www.schematik.io/mcp` |
| Cursor | [Add to Cursor](https://cursor.com/en/install-mcp?name=schematik&config=eyJ1cmwiOiJodHRwczovL3d3dy5zY2hlbWF0aWsuaW8vbWNwIn0=) |
| VS Code | [Add to VS Code](https://vscode.dev/redirect/mcp/install?name=schematik&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fwww.schematik.io%2Fmcp%22%7D) |
| Gemini CLI | `gemini extensions install https://github.com/schematik-engineering/schematik-mcp` |
| ChatGPT | Settings → Apps → Advanced settings → Developer mode, then Create app with the URL above |
| Anything else | Streamable HTTP server at the URL above. No API key. |

## Tools

| Tool | What it does |
|---|---|
| `search_parts` | Search the parts catalogue (boards, sensors, displays, modules) by name, brand, part number or use. |
| `get_part` | One part with its description, lowest current price and, where Schematik has one, its pinout. |
| `search_build_guides` | Search published build guides, optionally for one board (ESP32, Arduino Uno, Raspberry Pi Pico). |
| `get_build_guide` | A full guide: parts, wiring, steps and firmware, with a link to remix it in Schematik. |

## Try asking

- "Find me a CO2 sensor that works with an ESP32 and tell me what it costs."
- "Show me Schematik build guides for the Raspberry Pi Pico."
- "Walk me through building a plant-watering monitor, with the wiring."
- "What's the pinout of the ESP32-C6 DevKitC-1?"

## Privacy and support

We record which tool was called, the search words or page name, and which assistant called it, to improve results. We don't receive your conversation and don't link calls to a person. [Privacy policy](https://www.schematik.io/privacy) · [Terms](https://www.schematik.io/terms)

Questions or problems: support@schematik.io

This repository holds the connector manifests and docs; the server itself is hosted by Schematik.
