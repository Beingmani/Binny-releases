<p align="center">
  <img src="images/icon.png" width="128" alt="Binny icon" />
</p>

<h1 align="center">Binny</h1>

<p align="center">
  When your Trash gets messy, Binny throws a blanket over it.<br />
  A cozy, real-time cloth simulation draped over the Trash in your Dock.
</p>

<p align="center">
  <a href="https://github.com/Beingmani/Binny-releases/releases/latest/download/Binny.dmg"><strong>Download for Mac</strong></a> ·
  <a href="https://beingmani.github.io/Binny-releases/">Website</a> ·
  <a href="https://github.com/Beingmani/Binny-releases/releases">All releases</a> ·
  <a href="https://github.com/Beingmani/Binny-releases/issues/new/choose">Report a bug</a>
</p>

<p align="center">
  <img src="images/hero.png" width="640" alt="A rug draped over the Trash, with flies circling it" />
</p>

---

## What it does

Binny sits in your menu bar and keeps an eye on the Trash. Once the Trash passes a limit you choose, a blanket drops onto the Trash icon in your Dock, drapes over it and settles into folds.

- **It grows with the mess.** The fuller the Trash, the bigger and lumpier the blanket. Every file you delete makes a lump pop up and the blanket jump.
- **It gets smelly.** A faint smell seeps out from under the blanket, and houseflies arrive. They loop around the bin, land on the blanket, walk about and clean their wings.
- **It reacts to you.** Point at the Trash and a corner lifts while the flies scatter. Drag the blanket anywhere, then let go above the Trash and it drapes back over it.
- **It goes away when you clean up.** Empty the Trash and the blanket gets pulled off.

The cloth is simulated, not animated, so it falls, slides and folds differently every time. Once it settles, it stops using your CPU.

## Eight fabrics

<p align="center">
  <img src="images/fabrics.png" alt="The eight fabrics draped over the Trash" />
</p>

Top row: Persian rug, wool tartan, faded denim, rust corduroy. Bottom row: patchwork quilt, emerald silk, buffalo-check flannel, striped serape. Each fabric hangs its own way: silk floats down in fine folds, and a quilt drops heavy and stiff.

## Install

1. [Download **Binny.dmg**](https://github.com/Beingmani/Binny-releases/releases/latest/download/Binny.dmg).
2. Open it and drag **Binny** into **Applications**.
3. Open Binny. A short setup walks you through the permissions and lets you pick a blanket. When you finish, Binny leaves the Dock and lives in the menu bar.

Binny is signed and notarized by Apple, so it opens like any other app.

Used **Blanket Bin** before? Binny is the same app with a new name. It brings your settings over, quits Blanket Bin and moves it to the Trash. macOS asks for the two permissions once more.

**Requires** macOS 13 Ventura or later. Binny is a native Mac app, a 3 MB download, and runs on Apple Silicon and Intel Macs. On macOS 26 it uses Liquid Glass.

## Permissions

Binny needs two permissions. Setup asks for both and opens the right page in **System Settings → Privacy & Security**. If you skip one, the menu bar panel shows a notice with the same button.

| Permission | Why it needs it |
|---|---|
| **Accessibility** | Finds where the Trash icon is in your Dock, so the blanket lands on it |
| **Full Disk Access** | Measures how big your Trash is. Without it, Binny counts items instead |

Binny also asks once to control **Finder**, so it can open and empty the Trash for you.

Binny never reads, uploads or deletes your files. It only measures the size of the Trash, and it collects no analytics.

## Using it

- **Click the menu bar icon** to open the panel: the blanket, how full the Trash is, and Open Trash, Put Blanket Back and Empty Trash.
- **Right-click the menu bar icon** for quick actions.
- **Drag the blanket** around the Dock. **Right-click it** and it floats back over the Trash.
- **Click the blanket** to open the Trash, like clicking the icon underneath.

## Settings

- **Fabric:** pick any of the eight blankets.
- **Cover the Trash at:** a size (100 MB to 10 GB) or a number of items, with iCloud Drive included if you like.
- **Switches:** cover the Trash in the Dock, let me move the blanket, flies and smell, fabric sounds, open at login.

## Updates

Binny updates itself. New versions download in the background, and the menu bar panel shows **Restart to update**; if you leave it, the update installs the next time Binny quits. Your settings and permissions stay. To check now, right-click the menu bar icon and choose **Check for Updates…**

## Questions

**Does it delete anything?** No. Binny only empties the Trash when you click Empty Trash and confirm it.

**Does it slow my Mac down?** The blanket stops simulating as soon as it settles. Flies keep moving at a low frame rate, and you can turn them off in Settings.

**The blanket isn't on the Trash.** Check that Accessibility is on for Binny in System Settings → Privacy & Security. If it still misses, [report it](https://github.com/Beingmani/Binny-releases/issues/new/choose) with a screenshot of your Dock.

**How do I uninstall it?** Quit it from the menu bar icon and drag **Binny** from Applications to the Trash. Then it gets a blanket too.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/Beingmani/Binny-releases/issues/new/choose) and include your Binny and macOS versions.

<p align="center">
  <sub>Made by <a href="https://github.com/Beingmani">BeingMani</a></sub>
</p>
