MinecraftModelMaker is a tool designed to simplify the creation of 3D models for Minecraft using Block Displays. Follow this guide to get started with generating and placing your custom models in the game.

Getting Started
1. Select Output Location
Choose the location where you want the generated file to be saved.

2. Configure Model Dimensions
Enter the following parameters for your model:

Block Scale: Sets the scale of each block. Use decimal numbers in the format (e.g., 0.1).
Rows (X): Number of blocks in the width.
Columns (Y): Number of blocks in the depth.
Height Layers (Z): Number of blocks in the height.
3. Generate Layout
Click the "Generate Layout" button to create a layout based on your dimensions.

4. Place Blocks
Select Blocks: Choose blocks from the selection menu at the top of the interface.
Change Layers: Use the selection tool on the middle left side to switch between different layers of the model.
5. Generate File
Once you're satisfied with the model, press the "Generate Script" button. This will create a folder with the necessary files for your model.

6. Move Files to Minecraft
Open Minecraft’s save folder:
Navigate to %appdata%
Go to .minecraft -> saves
Select your world, then open the datapacks folder.
Place the generated folder into the datapacks folder.
7. Load and Display the Model in Minecraft
Run the following commands in the Minecraft chat console in this order:

/reload
/function pack:test

Your model will appear near the player's feet.

Enjoy creating and displaying your custom 3D models in Minecraft!
