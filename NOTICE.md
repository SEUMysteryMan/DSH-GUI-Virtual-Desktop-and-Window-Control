# Third-party notices

## dsh-gui-forkgo

- Package: `dsh-gui-forkgo@1.3.1`
- Author: 赢容
- Upstream: https://github.com/forkgo430/dsh-gui-forkgo
- License: MIT; see `LICENSE`.

This repository contains a mirrored snapshot of the installed package. The upstream project remains the authoritative source for new development.

## Windows-MCP

The vendored `windows-mcp==0.8.9` source originates from [CursorTouch/Windows-MCP](https://github.com/CursorTouch/Windows-MCP) and retains its own MIT license in `vendor/windows-mcp/LICENSE-upstream.md`.

The vendored source enables PostHog analytics by default and contains its upstream project analytics identifier in `windows_mcp/infrastructure/analytics.py`. It stores a random analytics user id and can send tool names, timing, success status, client/session metadata, and exception text to the upstream analytics service. This identifier is not a DSH user credential. No local analytics user-id files or event data are included in this repository.
