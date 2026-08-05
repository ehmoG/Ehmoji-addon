# Ehmoji-addon

Official distribution repository for **AI_Remesh by Ehmoji**.

- Created by Ehmoji
- Official YouTube: https://www.youtube.com/@ehmoji
- Blender 4.1+
- Download only from [Releases](https://github.com/ehmoG/Ehmoji-addon/releases)

## Install

1. Download `AI_Remesh_Blender_Addon_vX.Y.Z.zip` from Releases.
2. In Blender, open **Edit > Preferences > Add-ons > Install**.
3. Select the ZIP and enable **AI_Remesh**.
4. Open **View3D > Sidebar > Ehmoji**.

The add-on checks the latest official Release automatically and accepts an update only when its GitHub SHA-256 digest matches.

## Publish An Update

1. Change `bl_info["version"]` in the private development file.
2. Run the Blender self-test.
3. Build a ZIP named `AI_Remesh_Blender_Addon_vX.Y.Z.zip`.
4. Open [New Release](https://github.com/ehmoG/Ehmoji-addon/releases/new).
5. Create the matching tag, such as `v0.1.1`.
6. Attach only the ZIP, set it as the latest release, and publish.

Do not upload the private development source file to this repository. Published releases are immutable, so a published tag and ZIP cannot be replaced.
