# NNMV-Modpack

Welcome to the NNMV-Modpack! This repository contains a collection of mods, resource packs, and shaders to enhance your Minecraft experience.

This guide provides instructions on how to install and initialize the modpack, specifically for **TLauncher** users.

## ❗️ Important Prerequisites

Before you begin, you **must** have the correct version of **Fabric** installed in your TLauncher. This modpack's files will not work without the correct mod loader.

* In TLauncher, select `Create version` in the versions list (at the top most of the time), find the corresponding game version with the correct mod loader (`Fabric 1.21.1`). <b>UNCHECK EVERY CHECKBOX INSTEAD OF THE 1ST</b>. Install it and run it at least once to create the necessary folders.

---

## 🚀 Installation Guide (TLauncher)

Follow these steps to install the modpack.

### Step 1: Download the Modpack

1.  Go to the main page of this GitHub repository.
2.  Click the green **`< > Code`** button.
3.  Select **`Download ZIP`**.
4.  Save the file (e.g., `NNMV-Modpack-main.zip`) to your computer and unzip it. You will now have a folder named `NNMV-Modpack-main`.

### Step 2: Open Your TLauncher Game Folder

1.  Open TLauncher.
2.  Click the **"Folder" icon** 📁 next to the "Enter the game" button.
3.  This will open your `.minecraft` game directory.
4.  Choose the corresponding custom version at `/versions` directory


### Step 3: Copy the Modpack Files

Now you will copy the files from the `NNMV-Modpack-main` folder you unzipped into your `.minecraft` folder.

1.  **Mods:**
    * Open the `mods` folder from the unzipped `NNMV-Modpack-main` folder.
    * In your `.minecraft` directory, find the `mods` folder.
    * Copy **all** the `.jar` files from the modpack's `mods` folder and paste them into your `.minecraft/version/{your_version}/mods` folder.

2.  **Resource Packs:**
    * Open the `resourcepacks` folder from the unzipped `NNMV-Modpack-main` folder.
    * In your `.minecraft` directory, find the `resourcepacks` folder.
    * Copy the packs (they may be `.zip` files or folders) and paste them into your `.minecraft/version/{your_version}/resourcepacks` folder.

3.  **Shaders:**
    * Open the `shaderpacks` folder from the unzipped `NNMV-Modpack-main` folder.
    * In your `.minecraft` directory, find the `shaderpacks` folder.
    * Copy all the `.zip` files from the modpack's `shaderpacks` folder and paste them into your `.minecraft/version/{your_version}/shaderpacks` folder.

**Note:** If any of these folders (`mods`, `resourcepacks`) do not exist in your `.minecraft/version/{your_version}` directory, it's likely because you haven't run the correct Fabric version yet. Please run it once and then check again. If there's no `shaderpacks` folder in respective folder you can just create one.


---

## 🎮 How to Activate in-Game

After copying the files and launching the game with the correct Forge/Fabric profile, you need to enable the resource packs and shaders.

### Activating Resource Packs

1.  From the main menu, go to **`Options...`** > **`Resource Packs...`**.
2.  You will see the packs from the modpack under the "Available" column.
3.  Click the **arrow** ▶️ on the pack's icon to move it to the "Selected" column.
4.  Click **`Done`**. The game will reload with the new textures.

### Activating Shaders

*Note: This requires a shader-enabling mod like **OptiFine** or **Iris & Sodium** (which should be in your `mods` folder).*

1.  From the main menu, go to **`Options...`** > **`Video Settings...`** > **`Shaders...`**.
2.  You will see a list of all the shaders you copied.
3.  Click on the name of the shader you want to use.
4.  Click **`Done`**. The shader will be applied, and you can now play.


# Have fun.