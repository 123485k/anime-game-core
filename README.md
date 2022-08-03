# 🦀 Anime Game Core

Common library to control the Anime Game installation, written in Rust

## Roadmap to 1.0.0

* [x] Game
  * [x] Get current version
  * [x] Calculate difference with the latest version

  Feature: `install`

  * [x] Install the difference
  * [x] Apply changes for updates
    * [x] Remove outdated files
    * [x] Apply hdiff changes
  * [x] Repair game files

* [x] Voice packages
  * [x] List installed packages
  * [x] Get packages versions
  * [x] List available packages
  * [x] Calculate difference with the latest version

  Feature: `install`

  * [x] Install the difference
  * [x] Apply changes for updates
    * [x] Remove outdated files
    * [x] Apply hdiff changes
  * [x] Delete voice packages
  * [x] Repair broken packages

Feature: `telemetry`

* [x] Check if disabled
* [ ] Disable / enable

Feature: `linux-patch`

* [x] Fetch remote patch info
* [x] Identify installed patch info
* [x] Apply / revert patch
