# DepotDownloader-er

A simple batch script that makes using [DepotDownloader](https://github.com/SteamRE/DepotDownloader) easier.

## What it does

1. **Checks if DepotDownloader is installed**

   * If not, it automatically downloads the official release.
   * Extracts it into the `Resources` folder.
   * Cleans up the leftover `.zip`.

2. **Prompts you for details**

   * **App ID** → The game or app you want.
   * **Depot ID** → The specific part of the game (like binaries, language packs, etc.).
   * **Manifest ID** → The version/build you want.
   * **Steam Username** → Your account to log in with.

3. **Runs DepotDownloader**

   * Uses the details you entered to download the files directly from Steam.

## Why use this?

Instead of manually downloading, extracting, and typing long commands, this batch file automates the boring setup and lets you just enter the numbers you need.

---

## Usage

1. Download this repo.
2. Run `DepotDownloader-er.bat`.
3. Follow the prompts (enter App ID, Depot ID, Manifest ID, and your Steam username).
4. The files will be downloaded into the folder specified by DepotDownloader.

---

## Example

Let’s say you want to download an older version of **Counter-Strike: Global Offensive**.

* **App ID:** `730` (CS\:GO)
* **Depot ID:** `731` (main game content)
* **Manifest ID:** `1234567890123456789` (replace with the actual manifest ID of the version you want — you can find this on sites that track SteamDB manifests)
* **Steam Username:** `yourusername`

When you run the script, enter these values at the prompts.
DepotDownloader will then download that exact version of CS\:GO into your system.

---

## Credits

* [DepotDownloader](https://github.com/SteamRE/DepotDownloader) is created and maintained by **SteamRE**.
* This batch script simply automates setup and usage.

---

⚠️ **Note:** You must own the game on Steam and know the correct manifest ID. This script does not bypass Steam’s ownership checks.
