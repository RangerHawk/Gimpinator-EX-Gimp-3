# Gimpinator EX — GIMP 3.x Plugin

Generate AI images directly inside GIMP, from a text prompt, using Stable
Horde (free) or a local image-generation server.

## What it does

Gimpinator EX adds a menu item to GIMP — **Filters → Gimpinator → Gimpinator
EX** — that opens a prompt dialog, sends it to an AI image backend, and
drops the result into your image as a new layer.

- **Compatible with GIMP 3.x**
- **No subscription, no account required to use the plugin itself** — only
  a free Stable Horde account if you use that backend
- **Rebuilt and corrected 24 Oct 2026**: removed the hand-edit step that
  used to require typing your Windows username into the plugin file by
  hand, fixed the dialog's width/height/steps/etc. fields (they were
  locked and couldn't actually be changed), and removed two backends
  (Recraft, AIML) that were unfinished and never worked.

## Download & install

1. Click **gimpinator_ex.zip** above, then "Download raw file" (or grab it
   from the Releases page).
2. Unzip it and follow the step-by-step walkthrough inside:
   `Gimpinator GIMP 3.x Plugin Activation Guide.txt`.

## License & Credits

Released under the [GNU General Public License v3.0](LICENSE).

Gimpinator EX is based on the original [Gimpinator plugin by
PCOW](https://github.com/PCOW/Gimpinator), licensed under the MIT License.
You're free to use, remix, and redistribute this plugin.

Created by RangerHawk Studios (Joe Molnar), with AI assistance.
