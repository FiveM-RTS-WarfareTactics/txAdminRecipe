# Enyo RTS — txAdmin Recipe

One-click deploy recipe for the Enyo RTS Tactical Warfare FiveM game mode.

<p align="center">
  <a href="https://discord.gg/enyo-scripts"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white"></a>
  <a href="https://github.com/enyo-scripts/enyo-rts"><img src="https://img.shields.io/badge/GitHub-Core-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## What This Installs

| Resource | Repo |
|----------|------|
| `enyo-rts` | [github.com/enyo-scripts/enyo-rts](https://github.com/enyo-scripts/enyo-rts) |
| `rts-admin` | [github.com/enyo-scripts/rts-admin](https://github.com/enyo-scripts/rts-admin) |
| `rts-mapbuilder` | [github.com/enyo-scripts/rts-mapbuilder](https://github.com/enyo-scripts/rts-mapbuilder) |
| `rts-maps` | [github.com/enyo-scripts/rts-maps](https://github.com/enyo-scripts/rts-maps) |
| `rts-weapons` | [github.com/enyo-scripts/rts-weapons](https://github.com/enyo-scripts/rts-weapons) |
| `oxmysql` | [github.com/overextended/oxmysql](https://github.com/overextended/oxmysql) |
| `screenshot-basic` | [github.com/citizenfx/screenshot-basic](https://github.com/citizenfx/screenshot-basic) |
| `bob74_ipl` | [github.com/Bob74/bob74_ipl](https://github.com/Bob74/bob74_ipl) |

## Usage

In txAdmin, go to **Recipe Deployer** → **Custom Recipe** → paste this repo URL or upload the folder.

### Variables

| Variable | Default |
|----------|---------|
| `sv_licenseKey` | `changeme` |
| `server_name` | `Enyo RTS - Tactical Warfare V` |
| `max_players` | `32` |
| `mysql_host` | `localhost` |
| `mysql_database` | `rts_warfare` |

## Server Config

The generated `server.cfg` uses these template variables: `{{serverName}}`, `{{svLicense}}`, `{{maxClients}}`, `{{dbConnectionString}}`, `{{serverEndpoints}}`.

## License

MIT
