# Stash Config

[Download configuration](https://raw.githubusercontent.com/SublimatioL/Stash-Override/main/stash-merged-bank-dns-microsoft-split.stoverride)

## Setup

1. Keep your existing main profile; review the merged configuration first.
2. Import under Overrides. Check every enabled override in its displayed order.
3. Use Rule mode and select a working node in `节点选择`.

## Notes

- Targets the publicly listed iOS release, 3.4.1; no 3.6-only DNS fields.
- Replaces DNS and routing rules. Existing service-group routes need review.
- `节点选择` and every reachable group must remain nonempty, without `DIRECT`.
- Server-domain policies are profile-specific; review all node addresses.
- Leave Tunnel IPv6 Routing and Block QUIC off. Tunnel Proxy Only may affect rewrites.
- Local names need local mappings; node-side DNS, UDP DNS and IPv6 remain separate.
- Static review only. Active profile, override order and device tests are unverified.

Sources: [Stash](https://stash.wiki/en/configuration/override), [Rules](https://github.com/Loyalsoldier/clash-rules).
