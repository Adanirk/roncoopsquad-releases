# RoNCoopSquad — signed releases
## Download: use Uhiva Launcher

**Windows: [Get Uhiva Launcher 0.2.0-rc.2](https://github.com/Adanirk/uhiva-launcher-releases/releases/tag/v0.2.0-rc.2)**. This is the recommended install path. The launcher discovers supported Steam builds, downloads and verifies the signed mod, and handles backup, installation and rollback. Raw ZIP archives in this repository are for advanced/manual use, not the normal installation flow.

**Unsigned Windows preview:** not a stable release. Do not disable Windows protections. UE4SS must be present separately; the launcher explains what to do if missing. Two-PC co-op has not yet been verified.


This repository hosts release packages and the signed release index for **RoNCoopSquad**, an unofficial Ready or Not mod by Uhiva Mods.

**Not affiliated with or endorsed by VOID Interactive.**

## Security and compatibility

- The launcher must verify the Ed25519-signed `uhiva-release-index.signed.json` and the SHA-256 and exact size of every package before installation.
- Do not trust a package solely because it appears on GitHub; release assets and the signed index must match.
- Game updates can break UE4SS-based mods. Only releases explicitly marked compatible with the installed game build should be installed.
- Older versions may be revoked and cannot be installed even if historical downloads remain available.
- UE4SS is a separate third-party prerequisite. This repository does not authorize bypassing game protections.

The Windows launcher source is maintained separately in a private repository. The release index and signed packages become authoritative only after the first verified release is published.

**Support:** See release notes for each version.
