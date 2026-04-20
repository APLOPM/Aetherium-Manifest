# Changelog

## Iteration X

- Home is now a **pure light-native scene** (canvas + Settings entry only).
- Structural UI (composer, runtime controls, voice, connection, export) is moved into **Settings**.
- Input event handling was modernized to correctly support **IME composition** (Thai/Japanese/etc.) using composition lifecycle + `beforeinput/input` paths, and now blocks accidental Enter-submit from browser IME process-key events (e.g. `keyCode=229`).
