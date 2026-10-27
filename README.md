# Vigil Sprite

<img src="src/icons/vigil-sprite-128.png" alt="Vigil Sprite" width="96">

**A product of VigilTech, vigiltech.org.** VigilTech was founded by **Demetria Althea Cohn**.

**Vigil Sprite** is a pixel-art editor with an AI sprite builder. Original code; not Aseprite and not affiliated with it (read-only .aseprite import is implemented from the public file-format spec).

It runs inside Studio on Amerika OS (Ubuntu 26.10 ARM64): describe what you want, and the built-in assistant (Anthropic Claude, through your own API key) builds it. The key is stored in your login keyring by Studio and never reaches the app; see `docs/STUDIO-ARCHITECTURE.md` and `docs/README.md`. Local automation uses the existing Studio bridge; installing OpenClaw is not required.

The interface uses the VigilTech design system (Golden Gate, Vigil Sans), vendored in `src/app/brand/vigiltech/`, with light and dark appearances that follow the system setting.

Source layout: `src/` (installed under `/usr/share`), `tools/builders/sprite.py` (Debian package builder used by the Amerika OS build), `tests/`, `docs/sprite.md`.
Licence: GPL-3.0-only (see `LICENSE`); the Vigil Sans typeface is under the SIL OFL 1.1 (`src/app/brand/vigiltech/fonts/OFL.txt`). Third-party licences are listed in `src/NOTICE`.

Existing package IDs, launchers, Studio bridge APIs and `.asprite.json` format identifiers remain unchanged for compatibility.
