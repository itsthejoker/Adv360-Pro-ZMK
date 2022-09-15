# Joe's Advantage360 Layout

This is mostly stock with the addition of a Mac-specific layer in position 1, toggleable with MOD+M. All other layers are above it, so the status light for which layer you're on will continue to work as expected, just +1 color. To download, go to Actions, then to the most recent workflow run, then "firmware" under the Artifacts section. This is still my personal layout though and is subject to change, so fork it if you want to keep my Mac-specific changes.

Edit here: https://kinesiscorporation.github.io/Adv360-Pro-GUI/

## To build Firmware in GitHub Actions

### Setup

1. Fork this repo.
2. Enable GitHub Actions on your fork.

### Build firmware

1. Push a commit to trigger the build.
2. Download the artifact.

## To build Firmware locally using Docker

### Setup

1. Execute `setup.sh`.

### Build firmware

1. Execute `run.sh`
2. Check the `firmware` directory for the latest firmware build.

### Flash firmware

Resources can be found on Kinesis.com
https://kinesis-ergo.com/support/kb360pro/#firmware-updates
https://kinesis-ergo.com/support/kb360pro/#manuals
