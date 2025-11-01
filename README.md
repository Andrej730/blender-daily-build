# Blender Daily Build (Patched for 4.5)

This repository is a patched version of [nutti/blender-daily-build](https://github.com/nutti/blender-daily-build) to address issues with Blender 4.5.

## Issue with Blender 4.5

Official Blender 4.5 breaks stubs generation due to [issue #141853](https://projects.blender.org/blender/blender/issues/141853). The fix is confirmed to be backported and will likely be available in 4.5.5.

In the meantime, this repo applies the necessary patches (2 commits) to fix the issue in Blender 4.5. Once v4.5.0 is released, we can switch to official archives and the v4.5.5 tag for the source.

## Downloads

The built Blender can be downloaded via the [Releases](https://github.com/Andrej730/blender-daily-build/releases).
