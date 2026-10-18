# Changelog

Every release of BunX.

## v0.1.3 — 2026-10-18

- The README's Download block: `bunx-installer.sh` / `.ps1` unpack the latest release's source, or clone and run `bun run gates`.

## v0.1.2 — 2026-10-18

- `net`: a forwarded host or proto is read from the hop the outermost trusted proxy wrote, counted from the right like forwarded-for and absent past the chain, never from the value a client sent first.
- `cookie`: a cookie asking `SameSite=None` without `Secure` is refused instead of being dropped silently by browsers.
- `tooling`: `themeCss` renders a surface's tokens, motion, fonts and icon face from one input; `device`: the platform `desktop` joins web, ios and android.

## v0.0.2 — 2026-10-17

- One `engine` package with a subpath per concern for web and mobile, from HTTP, state and storage to i18n, world data and emoji.
- Spec names are lowercase words behind one optional leading underscore, so the demo spec sorts first and is the default.
