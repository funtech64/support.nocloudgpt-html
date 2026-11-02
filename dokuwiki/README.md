# Canonical DokuWiki support pages

These are the **public**, human-reviewed NoCloudGPT customer help pages that the 1.0.36 Lightsail documentation tool syncs to the local DokuWiki `support:` namespace.

- Canonical folder: `dokuwiki/pages/*.txt` (flat, lowercase snake_case names).
- Publish DokuWiki markup only. Do **not** add scripts, HTML, credentials, license keys, instance-specific settings, private information, or executable files.
- Every page can be read/downloaded on the [support website](https://support.nocloudgpt.com/docs/). The installed tool uses a read-only public HTTPS git clone/pull.
- Changes replace only managed `support:` pages after validation; users' own DokuWiki pages are outside this namespace.
- Publish updates through reviewed GitHub PRs. The docs sync is not a binary software updater.
- On installed hosts: `sudo ncgpt-support-sync --sync` or `--status`; a daily systemd timer is installed by 5.1.
