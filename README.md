# Stash Overrides

Private Stash override files for local proxy and direct rules.

Files:

- `stash-local-proxy.stoverride`
- `stash-local-direct.stoverride`

Import order in Stash:

1. `stash-local-direct.stoverride`
2. `stash-local-proxy.stoverride`

This keeps the proxy exceptions for selected `xianyi666.top` hosts ahead of the broader direct rule.
