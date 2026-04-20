# Minecraft-MultiBlock-Custom-Texture-Pack
Make your custom multiblock textures! Supports 2*2*2, 1*2*1, and above!

# Multi-Block Texture Studio 🎨⛏️

A purely browser-based, client-side tool to design and generate **Custom Multi-Block Textures** for Vanilla Minecraft. No mods, plugins, or external server software required. 

This studio allows you to design large, multi-block structures (like a 1x2 Vending Machine or a 2x2x2 Pizza Oven) and instantly packs them into a ready-to-use **Datapack** and **Resource Pack**. When the system detects your specified block configuration in-game, it seamlessly replaces them with your custom 3D-rendered texture!

## ✨ Features

* **Live 3D Preview:** A fully rotatable 3D canvas with synchronized axis guides to preview exactly how your textures will stretch and map in-game.
* **Built-in Pixel Studio:** Don't have a texture ready? Draw it directly in the browser! Supports multiple resolutions (16x to 512x) with brush, fill, and grid tools.
* **Automatic Formatting:** Safely scales and compresses rectangular designs into perfect square UV mappings required by Minecraft's internal engine.
* **Bulk Hitbox Editor:** Easily define the hidden, functional blocks inside your texture (e.g., hiding a working Furnace inside a custom Pizza Oven texture).
* **Universal Toggle Wand:** Includes an in-game tool to easily toggle your custom textures on and off without breaking the blocks underneath.

## 🚀 How to Use the Studio

1. Clone this repository or simply download the `index.html` file.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Set your dimensions (Width, Height, Depth).
4. Upload your 2D textures (or draw them in the Pixel Studio). 
5. Configure the interactive blocks you want hidden inside.
6. Click **Download Embedded .ZIP**.

*Note: The generated ZIP utilizes DEFLATE compression to ensure flawless extraction across all operating systems, including Windows File Explorer.*

## 🎮 In-Game Installation & Usage

1. Extract the downloaded `.zip` file. Inside, you will find two folders: a **Datapack** and a **Resource Pack**.
2. Place the Datapack in your world's `datapacks` folder.
3. Place the Resource Pack in your Minecraft `resourcepacks` folder and enable it in your game settings.
4. Type `/reload` in the Minecraft chat.
5. Obtain the **Universal Toggle Wand** by running the following command:
   ```mcfunction
   /give @s warped_fungus_on_a_stick[custom_data={toggle_wand:1b},item_name='{"text":"Universal Toggle Wand","color":"yellow"}']
