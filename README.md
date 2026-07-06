# Modded Oneblock Skyblock

Kitchen Sink modpack with 700+ mods, centered around "One Block" gameplay. Players start
on a single block in the sky, expanding and progressing by breaking it.

- **Minecraft:** 1.16.5
- **Loader:** Forge
- **Original pack:** [CurseForge page](https://www.curseforge.com/minecraft/modpacks/modded-oneblock-skyblock)
- **Original author:** DKLYNTLY

> This repo does not redistribute mod `.jar` files. Mods are pulled in via the
> CurseForge/Modrinth manifest, same as the official launcher does. Only configs,
> scripts, and other original content live here.

## What's in this repo

| Path | Purpose |
|---|---|
| `manifest.json` | Client modpack manifest (mod list + versions) |
| `server-manifest.json` | Server-side manifest (if it differs from client) |
| `overrides/` | Shared configs, resource packs, kubejs/scripts, etc. |
| `server-only/` | Server-exclusive files: start scripts, `server.properties.example` |
| `CHANGELOG.md` | Version history |
| `.github/ISSUE_TEMPLATE/` | Bug report templates for client and server issues |

## Reporting issues

Please use the [Issues tab](../../issues) instead of Discord — it's searchable and
lets you check whether your bug has already been reported. Pick the right template:

- **Client bug** — crashes, gameplay issues, visual bugs
- **Server bug** — problems specific to running/joining the server

Attach your `latest.log` or crash report from `logs/` / `crash-reports/` when possible.

## Installing

**Client:** Import `manifest.json` via CurseForge app or Modrinth App, or use a
[Packwiz](https://packwiz.infra.link/)-style setup if you switch to that later.

**Server:** See `server-only/README.md` for Java version, RAM, and port notes.

## License

Mod files themselves remain under their original authors' licenses (All Rights
Reserved on the CurseForge listing — mods are referenced, not redistributed).
Config/script changes in this repo are original work unless noted otherwise.
