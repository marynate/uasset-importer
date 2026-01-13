## Quick Start

This section walks you through the most common workflows for importing `.uasset` files using **UAsset Importer**.

### Prerequisites
- Enable the UAsset Importer plugin, and make sure the project is configured with the required engine version and plugins for the assets you plan to import

![quickstart_plugin_window](/_media/quickstart_plugin_window.jpg)

> Note: Assets can only be imported if they are supported by the current project’s configuration.

---

### Basic Import Workflow

#### Step 1: Locate the `.uasset` Files
Identify the `.uasset` files you want to import. These may come from:
- Vault Cache
- Another Unreal Engine project
- A backed-up Content folder

![Step1](/_media/quickstart_locate_uasset.jpg)
---

#### Step 2: Choose an Import Method

UAsset Importer supports three equivalent import methods:

**Option A: Drag & Drop (Recommended)**
1. Open the Unreal Editor.
2. Drag one or more `.uasset` files from **File Explorer**.
3. Drop them directly into the **Content Browser**.

![Step2](/_media/quickstart_drag_n_drop.jpg)

**Option B: File Menu**
1. In the Unreal Editor menu bar, select:  
   **File → Import .uasset File...**
2. Select `.uasset` file to import.

![Step2](/_media/quickstart_file_import.jpg)

**Option C: Content Browser Menu**
1. In **Content Browser**, click **Add** button
2. Select:  
   **Add .uasset File...*
3. Choose the `.uasset` file to import.

![Step2](/_media/quickstart_contentbrowser_add.jpg)

---

#### Step 3: Import Options

After selecting files, the import dialog appears:

![Step3 Import Options](/_media/quickstart_import_options.jpg)

- Inspect the assets by mouse over the asset thumbnail
- Adjust available import options as needed
- Confirm the import

![Step3 Tooltip](/_media/quickstart_inspect.jpg)

---

#### Step 4: Import

When you confirm:
- All required dependencies are automatically gathered and imported
![Step4 Import Progress](/_media/quickstart_import_progress.jpg)
- A result window shows up after import finished
![Step4 Import Result](/_media/quickstart_import_result.jpg)
- Assets appear in the Content Browser once the process completes
![Step4 Import Finished](/_media/quickstart_in_contentbrowser.jpg)

#### Have Fun

![Step5 Asset In Level](/_media/quickstart_asset_in_level.jpg)


