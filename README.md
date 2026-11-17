# Better Than Ocelots - Test Builds

Test builds of the **Better Than Ocelots** modpack (Minecraft 1.21.1, Fabric) - a modern Better Than Wolves port with additions. These are early builds for testing, released before they reach the public CurseForge version.

> **Test builds can have bugs. Back up your worlds before playing one.**

## Download

**[Download the newest test build](https://github.com/Gillly1313/bto-test-builds/releases/latest/download/Better-Than-Ocelots-Test.zip)** - the link always points at the latest build.

Every build, with its changelog: **[Releases](https://github.com/Gillly1313/bto-test-builds/releases)**

## Install

### CurseForge app
1. Download `Better-Than-Ocelots-Test.zip` (don't unzip it).
2. In the CurseForge app, open **Minecraft**, click **Create Custom Profile**, then the **Import** link at the top of that window.
3. Pick the zip. CurseForge downloads the mods and makes a new profile - your normal install is not touched.
4. Click **Play**.

### Prism Launcher
1. Download the zip.
2. **Add Instance -> Import**, choose the zip, then **OK**.

### Check it loaded
The game log (`logs/latest.log` in the profile folder) prints the build number, e.g. `===== BUILD v565 =====`. It should match the release you downloaded.

## Playing an existing world

1. Make a backup copy of your world folder first.
2. Copy the world folder from your normal profile's `saves` folder into the test profile's `saves` folder (in CurseForge: right-click the profile -> **Open Folder**).

Worlds played on a test build may not go back to an older version cleanly - keep the backup.

## Updating to a newer test build

Import the new zip the same way. It becomes another profile; copy your test world into it (or delete the old test profile once you have moved your worlds).

## Requirements

- Minecraft 1.21.1 with Fabric (the launcher installs both).
- About **8 GB of RAM** allocated to the game is recommended.

## Reporting problems

Report bugs in the Better Than Ocelots Discord server. Please include:
- the build number (from the log line above),
- what you did and what happened,
- your `logs/latest.log`, and the crash report from `crash-reports/` if the game crashed.
