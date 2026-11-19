# Hi, I'm Emanuele 👋

Computer Science student at the University of Rome Tor Vergata. I like building things I actually use: a **TrueNAS homelab** that works as the cloud for me and my friends, the tools that keep it running, and small apps around it. I'm especially interested in networking, security and self-hosting.

🌐 [emalau.it](https://emalau.it) · ▶️ [YouTube @EmaLau04](https://www.youtube.com/@EmaLau04) — vlogs, student life and tech

## Featured

### [Universal Converter](https://github.com/EmaLau/universal-converter)

A self-hosted file converter in the spirit of iLovePDF: about **200 formats**, chained conversions found with Dijkstra's algorithm, a JSON API and a **Nextcloud app** (right-click → convert). Runs with one `docker compose up`.

`Python` `FastAPI` `Docker` `LibreOffice` `FFmpeg` `Nextcloud`

### [Plico](https://github.com/EmaLau/plico)

Self-hosted **PDF tools on a single web page**: 27 tools to merge, compress, OCR, sign, fill forms, redact, compare and more, plus an API with keys, saved chains and a **Nextcloud app**. Every request works in a temporary folder deleted right after the result is sent.

`Python` `FastAPI` `PyMuPDF` `Docker` `Tesseract` `Nextcloud`

### [ARM-GDK-Unicorn](https://github.com/EmaLau/ARM-GDK-Unicorn)

A teaching environment to write, run and debug **ARMv7 assembly**, built in Python on top of the Keystone and Unicorn engines.

`Python` `ARM` `Emulation`

### [Nextcloud Authentik DAV](https://github.com/EmaLau/nextcloud-authentik-dav)

A small **Nextcloud app** that lets Finder, Windows Explorer, rclone and other WebDAV clients log in with the **Authentik password**, through a dedicated Authentik flow that creates no session. Security-reviewed, 27 PHPUnit tests, CI on Nextcloud 30–36.

`PHP` `Nextcloud` `Authentik` `WebDAV`

### [TrueNAS homelab toolkit](https://github.com/EmaLau/truenas-homelab-toolkit)

Small, independent scripts from my TrueNAS homelab: **lan-guard** blocks admin-only app ports from the home LAN (IPv4 and IPv6, Docker-aware), **heartbeat** pings an external monitor so I hear when the NAS itself goes down, **storage-status** writes pool, cloud and snapshot status to one JSON file for dashboards. Plus a verified nightly backup as an example. CI with shellcheck and firewall tests in a container.

`Bash` `Python` `TrueNAS` `iptables` `ZFS`

## In the works

Tools from my homelab, being cleaned up for release:

- **TrueNAS AutoUpdate** — nightly app updates with automatic rollback
- **SMART self-test scheduler** for TrueNAS 25.10

## Tech I use

[![Skills](https://skillicons.dev/icons?i=python,java,cpp,bash,php,js,ts,html,css,astro,fastapi,docker,linux,git,github&theme=dark)](https://skillicons.dev)

Also: TrueNAS, ZFS, Nextcloud, Authentik, Tailscale.
