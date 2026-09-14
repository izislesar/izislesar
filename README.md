# hi, i'm izislesar 👋

junior devops with an sre itch. i run a home fleet instead of collecting certificates.

## what lives at my place

23 self-hosted services on a laptop + a 4gb vps — bookmarks, rss, passwords, mail, music, s3 backups, two pagers. everything as code, everything with a restore path. the repos below are the proof, not the claim.

- 📚 bookmarks & reading — [linkding](https://github.com/izislesar/linkding), [shiori](https://github.com/izislesar/shiori), [miniflux](https://github.com/izislesar/miniflux)
- 📄 docs & files — [paperless-ngx](https://github.com/izislesar/paperless-ngx), [filebrowser](https://github.com/izislesar/filebrowser), [Stirling-PDF](https://github.com/izislesar/Stirling-PDF), [syncthing](https://github.com/izislesar/syncthing)
- 🔔 alerting & watching — [gotify](https://github.com/izislesar/gotify), [ntfy](https://github.com/izislesar/ntfy), [healthchecks](https://github.com/izislesar/healthchecks)
- 🗄️ data & secrets — [vaultwarden](https://github.com/izislesar/vaultwarden), [minio](https://github.com/izislesar/minio), [gitea](https://github.com/izislesar/gitea)
- 📊 infra itself — [netbox](https://github.com/izislesar/netbox) (inventory), [keycloak](https://github.com/izislesar/keycloak) (sso), [listmonk](https://github.com/izislesar/listmonk), [vikunja](https://github.com/izislesar/vikunja), [mealie](https://github.com/izislesar/mealie), [navidrome](https://github.com/izislesar/navidrome), [traccar](https://github.com/izislesar/traccar), [halo](https://github.com/izislesar/halo), [wastebin](https://github.com/izislesar/wastebin), [ollama](https://github.com/izislesar/ollama)

every repo has the same deal: `selfhost/docker-compose.yml` that actually runs, `.env.example`, caddy snippet, backup + update notes. the sre ones additionally carry `SLO.md`, k6 load scripts, prometheus alerts and a postmortem template.

## how i work

- `restart: "no"` everywhere — nothing starts without me saying so
- backups before updates, restore drills on a schedule
- sqlite until it hurts, postgres when it does
- loopback + tls before exposing anything; password managers and s3 consoles never see the open internet bare
- if it paged at night, there's a postmortem in the morning

## stack

linux · docker compose · caddy · postgres · redis · sqlite · prometheus + grafana · loki · alertmanager (→ gotify/ntfy) · k6 · ansible · restic · s3 · caddy · wireguard/ssh tunnels

languages i reach for: **go** and **python** — small exporters, backup scripts, glue between services. java and rust show up as guests (i host them, i read their logs, i tune their jvm flags).

## currently

- september 2026: wiring the whole fleet into one alerting story (healthchecks → gotify/ntfy, one SLO file per service)
- next: oidc everywhere via keycloak, so one login rules them all

## contacts

- telegram:
- email:
- linkedin:
- hh.ru:

---

*pinned repos are the three worth opening first: gotify, vaultwarden, miniflux — pager, secrets, and reading. the rest is the fleet around them.*
