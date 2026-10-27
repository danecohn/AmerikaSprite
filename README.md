# Cohnsoft Sprite

<img src="src/app/brand/cohnsoft/logos/mark/cohnsoft-mark.svg" alt="Cohnsoft" width="96">

**A product of Cohnsoft.** Founded by **Demetria Althea Cohn**.

Canonical company identity is vendored unchanged from cohnsoftassets commit `752e894f90f1e58e62ae466352cb03c8bfd7d703`.



**Sprite**: a pixel-art editor with an AI sprite builder. Original code; not Aseprite and not affiliated with it (read-only .aseprite import is implemented from the public file-format spec).

Developed by **Cohnsoft** for **Cohnsoft OS** (Ubuntu 26.10 ARM64): describe what you want, and the built-in assistant (Anthropic Claude, through your own API key) builds it. The key is stored in your login keyring by Studio and never reaches the app; see `docs/STUDIO-ARCHITECTURE.md` and `docs/README.md`. Local automation uses the existing Studio bridge; installing OpenClaw is not required.



Source layout: `src/` (installed under `/usr/share`), `tools/builders/sprite.py` (Debian package builder used by the Amerika OS build), `tests/`, `docs/sprite.md`.
Licence: GPL-3.0-only for Amerika code (see `LICENSE`); third-party licences are listed in `src/NOTICE`.

Existing package IDs, launchers, Studio bridge APIs and `.asprite.json` format identifiers remain unchanged for compatibility. The included product SVG and Sprite document are original Cohnsoft artwork.
