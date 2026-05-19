# Changelog

## [1.1.0] - Upcoming Release

### ✨ New Features & Ecosystems
- **Expanded Ecosystem Support**: Added full support for `bun`, `deno`, and `composer` package managers.
- **Search & Install (`search-packages`)**: Added a brand new command to dynamically search for and install packages. Features **live search autocomplete** for `npm`, `yarn`, `pnpm`, `bun`, and `composer` using their official APIs.
- **Free Up Space (`free-up-space`)**: Added a dedicated command to clean up system caches and reclaim disk space across all installed package managers (e.g., `brew cleanup`, `npm cache clean`, `pip cache purge`).
- **Uninstall Packages**: Added interactive interactive actions inside the "List Installed Packages" command to uninstall any package with one click.
- **Export to Shell Script**: Added the ability to export a backup JSON file directly into an executable `.sh` shell script for easy environment replication on new machines.
- **Version Pinning (Ignore List)**: Added the ability to permanently "Ignore" specific packages from the "Check for Updates" view so they no longer prompt for updates.

### 🚀 Automation & Polish
- **Background Auto-Updates**: The `upgrade-all` command is now configured as a true background task (`1d` interval), silently keeping your system up-to-date.
- **Improved UI Layouts**: Converted several Markdown detail views into interactive Raycast lists for better action accessibility.
- **Enhanced Safety Controls**: Integrated a new "autoUpgradeTrusted" configuration option.

## [1.0.0] - Initial Release
- Initial release featuring unified update checking for Homebrew, npm, pip, pipx, cargo, RubyGems, Mac App Store, and Go.
- Added visual indicator badges, update sizes, and direct changelog access.
- Added Version Backups command with rollback functionality.
