# Reil VRM asset

The homepage loads the 3D mascot only after a visitor chooses **“Добавить Reil”** in the consent dialog.

## Required file

Upload the exported avatar model as:

`models/Reil.vrm`

Use the **VRM** download from the avatar editor, not the backup file or the Unity package. Keep this filename exact because `index.html` loads it from `./models/Reil.vrm`.

The model is loaded in the browser using Three.js and `@pixiv/three-vrm`. It is not downloaded until the visitor opts in.

This folder currently contains instructions only; the VRM model itself must be uploaded separately.
