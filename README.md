# RoNCoopSquad — signed releases

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