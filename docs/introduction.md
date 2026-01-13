## Introduction

**UAsset Importer** is an Unreal Engine editor plugin that enables direct import of `.uasset` files into your project with automatic dependency analysis and gathering.

Unlike Unreal’s built-in migration workflow, UAsset Importer allows you to reuse assets without opening the source project or manually tracking dependencies. During import, the plugin analyzes asset references and ensures that all required dependencies are collected and imported together, providing a reliable and streamlined workflow for cross-project asset reuse.

UAsset Importer is designed to stay lightweight and unobtrusive. It integrates directly into the Unreal Editor through the File menu, Content Browser context menu, and drag-and-drop support, allowing it to fit naturally into existing workflows without introducing unnecessary complexity.

The plugin is particularly useful for:
- Importing assets from the Vault Cache
- Reusing assets across multiple Unreal Engine projects
- Avoiding repetitive project migration steps
- Maintaining clean and predictable dependency handling

<!-- prettier-ignore -->
> Asset compatibility depends on the target project’s engine version, enabled plugins, and editor configuration. UAsset Importer will import assets that are supported by the current project environment.

> Cooked assets and Virtual Assets are not supported.
