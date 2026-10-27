# Docker Categories for Unraid

Groups the containers on the Unraid Dashboard's **Docker Containers** tile into named, collapsible sections, with a filter box on top.

- Sections are defined by a name and a regex matched (case-insensitively) against container names; first match wins, unmatched containers go under **Other**.
- Edit them under **Settings → User Utilities → Docker Categories**, with a live preview of which containers land where.
- Collapsed sections are remembered per browser; the "Started only" switch keeps working.

Tested on Unraid 7.3.2.

## Install

Plugins → Install Plugin, paste:

```
https://raw.githubusercontent.com/Glitchtit/unraid-docker-categories/main/docker.categories.plg
```

Config lives in `/boot/config/plugins/docker.categories/categories.json` and is kept on uninstall.
