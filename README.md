# Network Config Hub

Personal, version-controlled network and cross-device configuration files.

## Shadowrocket

- Profile: [shadowrocket/mainland-china.conf](shadowrocket/mainland-china.conf)
- Upstream source: https://github.com/hongkongkiwi/shadowrocket-vpn-configs
- Personal override: `DOMAIN-SUFFIX,ss-id.com,PROXY` (before ChinaMax and `FINAL,DIRECT`).
- Domestic and payment services use direct-routing rules; test actual connections for sensitive apps.
- Proxy nodes, airport subscriptions, passwords, tokens and API keys must **never** be committed.

## Synchronization

GitHub `main` is the source of truth. Edit and commit here, then refresh the profile on each device. Local Shadowrocket edits do not automatically push back to GitHub.

**Important:** This repository is currently private. Anonymous `raw.githubusercontent.com` requests cannot fetch this profile. To use the configured `update-url` for direct device updates, make the repository public **only if it contains no secrets**, or use a separate public repository for sanitized profiles. Do not put a GitHub access token in a shared config URL.

## Upstream and maintenance

This profile is a snapshot of an upstream generated file. Its remote rule-set URLs refer to third-party repositories; verify them when troubleshooting. GitHub does not automatically merge upstream changes into this copy. Review upstream changes before manually syncing, preserving local overrides.
