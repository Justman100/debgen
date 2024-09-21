# v3.0.0 (21.09.2024)
- Added `experimental` repository
- Removed the `yarn` force in NodeJS scripts
- Repository `buster` was removed from the PHP repository (see the [GitHub issue](https://github.com/oerdnj/deb.sury.org/issues/2098) for more informations)
- Repositorys `squeeze`, `wheezy`, `jessie` and `stretch` was removed from the official repo list
- Updated dependencies to latest versions
- Updated translations
- `experimental` and `sid` do not have the `updates` and `security` branches! So removed for their
- `testing` is `trixie`, so adjusted

# v2.2.0 (27.03.2024)
- Updated dependencies to latest versions
- Adding/fixing description

# v2.1.0 (23.02.2024)
- Added PostgreSQL repository
- Removed lock file
- Removed Clipboard.js library

# v2.0.5 (22.02.2024)
- Docker also not supports trixie

# v2.0.0 (22.02.2024)
## New
- Added releases Linux Debian 12 (Bookworm) and 13 (Trixie)
- Added repo testing
- Added repositories of PHP and Docker

## Changed
- Updated dependencies
- Remove the request from Google Fonts to host these themselves.
- Removed `main` section and adapted CSS

## Fixed
- Fixed, that the release `Bullseye` used `/updates` instead of `-security` in the security repo