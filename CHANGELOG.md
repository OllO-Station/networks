# Changelog

## [ollo-testnet-1] -2022-11-1

* (ollod) added [CHANGELOG.md](https://github.com/OllO-Station/ollo/blob/v0.0.1/CHANGELOG.md).
* (sdk) upgrade [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) to [v0.46.3](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.46.3). See [CHANGELOG.md](https://github.com/OllO-Station/blob/v0.46.3/CHANGELOG.md) for details.
  

### Bug Fixes

* (ollod) slashing `downtime_jail_duration` reduced to `600000000000ns`

### Breaking Changes

* (ollod) `chain_id` updated to reflect new value `ollo-testnet-1`

### Features

* (ollod) User balances and accounts have been brought over at zero height
* (ollod) add [interchain account](https://github.com/cosmos/ibc-go/tree/main/modules/apps/27-interchain-accounts) module (interhchain-account module is part of ibc-go module).
* (ollod) add [ibc fee](https://github.com/cosmos/ibc-go/tree/main/modules/apps/29-fee) module
* (ollod) add [group module](https://github.com/cosmos/cosmos-sdk).
* (ollod) add [nft module](https://github.com/cosmos/cosmos-sdk).

### Improvements

* (ollod) More user-friendly CLI formatting & subcommands
* (ollod) Changed `chain.schema.json` to reflect current values
* (ollod) Updated Github build, protoc, release actions to work properly
* (ollod) Added Docker build file
* (ollod) Added `balances-export` subcommand to root command, removed extraneous subcommands
* (ollod) Updated `chain.json` to reflect accurate values and moved to `/assets` folder
* (ollod) Added `assetslist.json` file prototype and IBC data JSON placeholder
* (ollod) Added multli-node testnet initialization scripts
* (ollod) Added new config.yml specification file for [Ignite](https://github.com/ignite/cli)

<!-- Release links -->

[Unreleased]: https://github.com/OllO-Station/ollo/compare/v0.0.1...HEAD
[v0.0.1]: https://github.com/OllO-Station/ollo/releases/tag/v0.0.1
