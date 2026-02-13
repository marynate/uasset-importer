# Change Log

## 1.0.6
* Assets are now properly marked as Invalid when the asset class or dependent plugin/module is not supported by the current project or engine version
* Properly import assets with soft references missing but ignorable legacy asset types (mainly UE4 rig assets)
* Import results now display the total number of imported assets (previously showed total dependencies)
* Fixed unnecessary asset duplication during import caused by class name changes in newer engine versions
---
## 1.0.5
* Allow importing assets with missing editor-only engine package references
---
## 1.0.4
* Added a show/hide overlay button and asset thumbnail overlays for Engine Version, Validation Status, and Content Type.
* Assets are now automatically validated, with validation status icons displayed on asset thumbnails.
---
## 1.0.3
* Added plugin version display to the Import Options dialog
* Enabled drag-and-drop import into folders in both Path View and Asset View (previously only supported dropping onto empty space in Asset View)
* The last opened directory is now also saved when importing via drag-and-drop
---
## 1.0.2
* Now remembers the last import directory
---
## 1.0.1
* Fab Release
---
### 1.0
* First release
