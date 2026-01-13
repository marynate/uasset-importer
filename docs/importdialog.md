# Import Options

The Importer Options dialog allows you to select which assets to import and customize the import process.

![Import Options](/_media/import_options_dialog.jpg)

---

## 1. Asset List

You can preview asset thumbnail, view asset name, asset class, saved with engine version, and select which assets to import when drag in multiple .uasset files.

![import_options_dialog_asset_list](/_media/import_options_dialog_asset_list.jpg)

You can inspect the meta data of the asset by mouse over the asset thumbnail.

![Import Options](/_media/import_options_tooltip.jpg)


## 2. Import Options

### Import

![import_options_dialog_import](/_media/import_options_dialog_import.jpg)

| Setting | Description | Default |
|---------|-------------|---------|
| **Abort If Dependency Missing** | Stops the import if any required dependency is missing or invalid. Useful to ensure complete imports. | Disabled |
| **Ignore Soft Reference Errors** | Ignores missing or invalid soft references during import. Useful if some references are optional. | Enabled |
| **Overwrite Existing Assets** | Replaces existing assets in the project with the imported versions. | Disabled |
| **Rollback on Failure** | Rolls back all imported assets if the import fails. May not work if files are locked by the editor. | Enabled |

---

### Post-Import

![import_options_dialog_post_import](/_media/import_options_dialog_post_import.jpg)

| Setting | Description | Default |
|---------|-------------|---------|
| **Sync Imported Assets in Content Browser** | Automatically shows newly imported assets in the Content Browser. | Enabled |
| **Sync Skipped Existing Assets** | Shows assets that were skipped because they already exist. | Enabled |
| **Load/Reload Assets After Import** | Loads or reloads assets into memory after import completes. | Enabled |

---

### Collection

![import_options_dialog_collection](/_media/import_options_dialog_collection.jpg)

| Setting | Description | Default |
|---------|-------------|---------|
| **Add Imported Assets to a Collection** | Adds imported assets to a collection for easier management. | Disabled |
| **Unique Collection Name for Each Session** | Uses a unique collection name for every import session. | Disabled |
| **Collection Name** | Name of the collection to add imported assets to. | None |

---

## 3. Finish the Import

![import_options_dialog_footer](/_media/import_options_dialog_footer.jpg)

**Save Improt Settings:** Save the import settings for the next import.

**Always Show Import Options Dialog on Import:** If diabled, the import options dialog will not be shown again next time.

> You can re-enable the Import Options Dialog in **Editor Preferences**.

![import_options_dialog_enable](/_media/import_options_dialog_enable.jpg)

**Reset Options:** Reset al import options to the default values.

**Import:** Click the button (or press the **Enter** key) to start the import

**Cancel:** Click the button (or press the **Esc** key) to close the dialog without import.