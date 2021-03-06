# Satisfactory-AB_TrashSeason
The development source for the Satisfactory mod AB_TrashSeason

See the [mod page](https://ficsit.app/mod/EbrX9MZXd9Ge4f) for details

# Setup
If you want to play the mod, install it via SMM.

If you want to do development work with this content first checkout the structure:
* `/_promo/`
  * Promotional pictures and references for remote linking
* `/.gitignore/`
  * This will list important files that must exist but can easily be regenerated
* `/UEContent/`
  * The mod folder(s) that should be added to your dev build's /content folder
  * I recommend symlinks to the folders inside here rather than copying
* `/UESource/`
  * The mod folder(s) that should be added to your dev build's /source folder
  * I recommend symlinks to the folders inside here rather than copying
* `/<other>/`
  * Folder for a major piece of content and its related dev files

I use the following software:

* Blender
  * Y.A.V.N.E.
* Affinity Designer
* Substance Painter

Given how important files are ignored you'll need to re-export fbxs from blender and tgas from substance/affinity as you change the sources, but the uassets in the content folders should already be cached and work fine.

# License
All work is free to use or redistribute for the purpose of Satisfactory modification, given proper attribution to me and identical restrictions on derivative content.

If I've abandoned this and you would like ownership, let me know. If I'm dead, go nuts.
