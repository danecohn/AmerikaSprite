# AmerikaSprite

**Amerika Sprite**: a pixel-art editor with an AI sprite builder. Original code; not Aseprite and not affiliated with it (read-only .aseprite import is implemented from the public file-format spec).

Part of **Amerika OS Developer Edition** (Ubuntu 26.10 ARM64): describe what you want, and the built-in assistant (Anthropic Claude, through your own API key) builds it. The key is stored in your login keyring by Amerika Studio and never reaches the app; see `docs/STUDIO-ARCHITECTURE.md` and `docs/README.md`. All four Studio apps are also controllable by Amerika Agent over MCP.



Source layout: `src/` (installed under `/usr/share`), `tools/builders/sprite.py` (Debian package builder used by the Amerika OS build), `tests/`, `docs/sprite.md`.
Licence: GPL-3.0-only for Amerika code (see `LICENSE`); third-party licences are listed in `src/NOTICE`.
