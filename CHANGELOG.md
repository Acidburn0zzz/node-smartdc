# node-smartdc Changelog

## smartdc 7.0.0-rc3 (not yet released)

- Added `sdc-listnetworks` and `sdc-getnetwork`.

## smartdc 7.0.0-rc2

- Added "--networks|-w" argument to sdc-createmachine
- Update README with upgrade section

## smartdc 7.0.0-rc1

- New version to support SDC 7.0 new features.
- Added `/images` resource
- Added `/fwrules` resource
- Added machine `/audit`
- Added get/update account
- Added tests for everything
- Added token authentication
- Removed the `_CLI_` part from SDC env vars
- Removed basicAuth and `sdc-setup` due to PCI compliance
- Retrieve all machines tagged when `tags=*`
- Allow to upload DSA keys to Cloud API, but disallow using them with node-smartdc
- `PUT /tags` to `ReplaceMachineTags` exposed.
- Added Rename Machine
- Short option `-?`, valid for all the `sdc-*` commands
- Normalized arguments: when machine is required, is always last, not named, argument.
- Handle `noCache` option for machine metadata/tags

