# armenian-eastern-legacy-mac

Armenian Eastern (Legacy) keyboard layout for macOS.

This layout reproduces the classic **Armenian Eastern (Legacy)** typewriter arrangement so you can type Armenian on any modern Mac.

## Requirements

* macOS (Intel or Apple Silicon)
* The `Armenian Eastern.bundle` file included in this repository

## Installing

1. Download the layout by pressing the `Code` button on GitHub, then `Download ZIP` (or clone the repository).
2. Unzip the archive if needed.
3. Double-click `Armenian Eastern.bundle` to install the keyboard layout.

   Alternatively, copy `Armenian Eastern.bundle` into one of these folders:
   * `~/Library/Keyboard Layouts/` — installs for the current user only
   * `/Library/Keyboard Layouts/` — installs for all users (requires admin rights)
4. Log out and log back in (or restart) so macOS picks up the new layout.

### Adding the input source

* **macOS Ventura (13) and later:** `System Settings` → `Keyboard` → `Text Input` → `Input Sources` → `Edit…` → `+`.
* **macOS Monterey (12) and earlier:** `System Preferences` → `Keyboard` → `Input Sources` → `+`.

Then choose `Armenian` in the sidebar, select `Armenian Eastern`, and add it.

Switch between layouts with the input-source menu in the menu bar, or press `Control` + `Space` (or the `🌐`/`fn` key on newer keyboards).

You're done ☺️. Enjoy!

## Troubleshooting

If the steps above don't work, macOS may not recognize the folder as a bundle. In that case use the [Ukelele](https://software.sil.org/ukelele/) tool to install the layout:

1. Open Ukelele.
2. Go to `File` → `Install` → `Show Organizer`.
3. Use the `Set Folder` button to import the folder.

If the layout still doesn't appear after installing, make sure you logged out and back in, and confirm the bundle lives in a `Keyboard Layouts` folder listed above.

## Built With

* [Ukelele](https://software.sil.org/ukelele/) — keyboard layout editor for macOS

## Authors

* **[Narek Hovhannisyan](https://github.com/narekhovhannisyan)**

## Acknowledgments

* If you liked my keyboard layout, please star the repository 🤩
