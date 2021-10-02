# RA Garage Desktop App [![CircleCI Build Status](https://circleci.com/gh/revidian-auto/ra-garage-desktop-app.svg?style=shield)](https://app.circleci.com/pipelines/github/revidian-auto/ra-garage-desktop) [![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/felicianotech/pocket-casts-desktop-app/trunk/LICENSE)

RA Garage is modern motorcycle management.
It's an app to manage your motorcycle mileage, fuel, and services.
Keep an accurate history of your bike without the pen and paper.
This repository is for the desktop version of the app, available for Linux and macOS.
The web version of the app can be found at [garage.revidianauto.com](https://garage.revidianauto.com).


## Installation

### Ubuntu & other Linux distros supporting .deb files

We publish a `.deb` file for each release in GitHub Releases.
Check out the [releases page](https://github.com/revidian-auto/ra-garage-desktop/releases) to find them.

### macOS

I don't currently publish any packages for macOS.
If you want one, request it in a GitHub Issue (check for an existing issue first) or open a PR.
Since this is built with Electron, it shouldn't be too much extra work to build for macOS if the desire is there.

### Windows

There isn't a Windows build.
Please use the web version of the app [here](https://garage.revidianauto.com).
If you would like to request a Windows app, please open a GitHub Issue [here](https://github.com/revidian-auto/ra-garage-desktop/issues) or email us Ricardo <at> RevidianAuto.com.


## Usage

This is a desktop app.
Open whatever app launcher you normally use and search for "RA Garage".


## Development

This app is built with Electron.
Standard Electron, Node.js, and JavaScript best practices apply.
I'll add more info here in time.
Please keep in mind this codebase is for the Electron wrapper around the core app.
The core app is not open source.


## License

The code for this repository is licensed under the MIT license.
This repo's license can be found [here](./LICENSE).
The code for RA Garage itself is proprietary and not available within this repo.
