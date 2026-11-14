# secretserver.pro Coincide assets

This package contains the branded Coincide UI library, the white S mark, and ten renamed overlay images for the BloxRP hub.

- `coincide/lib.luau`: branded copy of [ExtroDevGit/Coincide-UI](https://github.com/ExtroDevGit/Coincide-UI), upstream blob `0778b5e23778858fc742ccf98287047f1c06a0ab`.
- `coincide/mark-white-v2.png`: secretserver.pro logo.
- `waifus/*.png`: renamed images resized to fit the overlay.
- `waifus/manifest.json`: image names and paths.

The hub loads the owned library URL and downloads the selected image on demand. Its fallback to the upstream UI library can be removed once the owned files are published and verified.

