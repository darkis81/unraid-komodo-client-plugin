# Changelog

## 2026.11.19.065715

- Update Periphery to v2.3.4 with verified SHA256 and daily stable-release checks.


## 2026.06.26

- Initial production-oriented Unraid plugin scaffold for Komodo Periphery
- Native host service management via Unraid `rc.d`, without Docker or `systemd`
- Persistent config, keys, runtime config, and CA feed metadata
- GitHub-ready bundle build and `.plg` generation scripts
- Corrected the release bundle so it does not contain `/etc/rc.d` directory entries; the plugin must only ship `/usr/local/etc/rc.d/rc.komodo-periphery` and create `/etc/rc.d/rc.komodo-periphery` as an explicit compatibility symlink during install.
