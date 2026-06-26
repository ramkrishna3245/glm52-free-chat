# GLM-5.2 Free Chat

Chat with GLM-5.2 (744B MoE, 1M context) **completely free** — no API key, no backend, no signup required.

## How It Works

Uses [Puter.js](https://developer.puter.com) — a free, keyless AI API that runs entirely from the browser. Open the HTML file and start chatting.

## Usage

Just open `index.html` in any browser. Puter.js will prompt you to sign in with your Puter account (free, takes 30 seconds). After that, every message goes to GLM-5.2 for free.

## Why This Matters

GLM-5.2 is a 744B-parameter Mixture-of-Experts model (40B active per token) with a 1M-token context window. It scores competitively with Claude Opus on coding benchmarks — and this is the only way to use it for free without renting GPU hardware.

## Models Available

The tool uses `z-ai/glm-5.2` but Puter.js supports 400+ models including:

| Model | Puter ID |
|-------|----------|
| GLM-5.2 | `z-ai/glm-5.2` |
| GPT-5.5 | `gpt-5.5` |
| Claude Opus 4.8 | `claude-opus-4.8` |
| Gemini 3.1 Pro | `gemini-3.1-pro` |
| DeepSeek V4 | `deepseek-v4` |

## Requirements

- A browser (Chrome, Edge, Firefox)
- Internet connection
- A free Puter account (prompted on first use)

## License

MIT
