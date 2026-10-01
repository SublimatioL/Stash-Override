# Stash Config

[Download configuration](https://raw.githubusercontent.com/SublimatioL/Stash-Override/main/stash-merged-bank-dns-microsoft-split.stoverride)

## Setup

1. Keep your existing main profile.
2. Import the file under Overrides and enable it.
3. Use Rule mode and select a node in `节点选择`.

## Notes

- Replaces DNS and routing rules; retains existing nodes and groups.
- `节点选择` must be nonempty and have no `DIRECT` path.
- Server-domain entries are profile-specific.
- Enable Tunnel Proxy Only and leave Block QUIC disabled.
- IPv6 tunnel routing is an app setting; remote IPv6 is separate.
- Static checks only; test essential services and connection failure.

Sources: [Stash](https://stash.wiki/en/configuration/override), [Rules](https://github.com/Loyalsoldier/clash-rules).
