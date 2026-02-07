## Version Changelog

### Enlightenment (01.29.26)
I discovered that "1.19-1.20.1" actually works all the way down to 1.7.2 (and probably lower but I can't be bothered to check).
- Updated pack_format of the new 1.7.2-1.20.1 to 15.

### Major restructuring (10.24.23)
I learned more about how resource pack compatibility works and discovered I don't actually need to update the pack_format every time.
As long as the resource itself wasn't modified, I don't need to care about incompatibility warnings.
This makes maintaining and versioning the project much easier.
- Merged the previous 1.19-1.20 releases into one. The only difference was the pack_format, and nothing actually changed between these releases.

### 1.20.2 (10.24.23)
- Updated pack_format to 18 to support 1.20.2.
- Fix Minecraft resource change (assets/minecraft/textures/gui/icons.png -> assets/minecraft/textures/gui/sprites/hud/experience_bar_progress.png)
- Optimized image files for smaller file size and re-packaged all previous releases.

### 1.20 (06.14.23)
- Updated pack_format to 15 to support 1.20.

### 1.19.4 (04.11.23)
- Updated pack_format to 13 to support 1.19.4.

### 1.19.3 (12.22.22)
- Updated pack_format to 12 to support 1.19.3.

### 1.19 (07.06.22)
- First release.
