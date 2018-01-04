## Features

- MySQL support
- SQLite support
- Local Files support
- PlayerDatabase support
- WebRequests support
- Native Oxide ban system support
- Ban/Unban by SteamID
- Ban/Unban by IP Range `(XX.*.*.*, XX.XX.*.*, XX.XX.XX.*)`
- Ban/Unban by Name
- Ban/Unban by IP
- Banlist features
- Multiple database support *(MySQL + native Oxide for example)*
- Temporary ban support
- Ban evasion support *(players changing Steam ID or IP)*
- Auto kick on ban players matching

**PlayerDatabase** is not needed but strongly recommended *(so you can ban offline players by Steam ID + IP)*.

## Usage

### Chat/Console Commands

- /ban `<name/steamID/IP/RangeIP>` `<optional: time>` `<optional: reason>`
If no time is given the ban is permanently.

### Examples

- /ban Domestos noob - will ban Domestos permanently
- /ban Domestos 20m noob - will ban Domestos for 20 minutes
- /ban Domestos 3h noob - will ban Domestos for 3 hours
- /ban Domestos 10d noob - will ban Domestos for 10 days
- /ban `86.87.*.*` "Domestos IP Range" - This will permanently ban all those ip ranges
- /unban `<name/steamID/IP/RangeIP>`
- /kick `<name/steamID/IP/RangeIP>` `<reason>`
- /banlist `<BanSystem>` `<optional: startid>`

## Permissions

The config offers options to set different permissions for every command so you can control which user can use which commands.

### Default permissions are:

- ban - enhancedbansystem.ban
- unban - enhancedbansystem.unban
- kick - enhancedbansystem.kick
- banlist - enhancedbansystem.banlist
