# Northstar Career — Windows downloads

An alpha general aviation career companion for Microsoft Flight Simulator.

## Download and install

1. Open the [latest Windows release](https://github.com/leoOH159/northstar-career-downloads/releases/latest) and download **Northstar-Career-Setup-VERSION.exe** under Assets.
2. Close Northstar if it is already running, then run the installer. Install over your existing copy to keep your career and settings.
3. Sign in or create an account. New pilots need a Northstar activation key.

You can also use the [online dashboard](https://northstar-ga-career.pages.dev/) for career management. Simulator flight recording requires the Windows app.

## Automatic updates

Install version **0.2.8 or newer once**. Northstar then checks for future published releases and downloads updates in the background. A downloaded update installs when the app closes. You can check status and restart to update in **Settings → Desktop updates**. The app will not automatically restart during a flight.

Older versions do not contain an updater, so they require this one installation to enable it.

## MSFS connection

Run MSFS, FSUIPC7 and the Northstar Windows app on the same PC. In FSUIPC7, select **Add-ons → WebSocket Server → Auto-Start** and start the server if it is stopped. Its default address is `ws://localhost:2048/fsuipc/`.

Accept a contract in Northstar, load the assigned aircraft at departure, fly, and park below 3 kt for 20 seconds after landing. Northstar records and rates the flight automatically.

## Release files

- `.exe`: the Windows installer.
- `.exe.blockmap`: used for smaller update downloads; pilots do not need to open it.
- `latest.yml`: the updater's version and checksum metadata; pilots do not need to open it.

This repository distributes installers and update files. The application's source repository is private.
