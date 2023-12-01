TDC Tools: Boardmaker 1.0
This script is developed by Thea Design + Concept (T.D.C.). It is designed to create a floorboard pattern in Blender 4.

Description
The TDC Tools - Boardmaker 1.0 script creates a floorboard pattern based on the dimensions of a selected object in Blender 4. It generates individual floorboards, applies a random vertex color to each one, and arranges them in a pattern along the y-axis. The floorboards are created as separate objects and then joined back together, allowing the user to adjust the board depth and uvs with ease and as needed.

Usage
Select a flat object in Blender. The object must be flat on the z-axis.
If you need the boards to run along a different axis, rotate the origin of the selected object to suit the direction you want the boards to go. It must be set to local rotation of the origin. The boards will always be placed lengthways in rows along the y-axis.
Run the TDC Tools: Boardmaker 1.0 script.
The script will create a floorboard pattern based on the dimensions of the selected object.
After the script has run, you can manually adjust the floorboards thickness with the solidify modifier as needed.

Customization
You can customize the script to suit your needs by changing the following variables manually within the script:

PLANK_WIDTH: The width of the planks. Default is 130mm.
GAP: The gap between the planks. Default is 0.5mm.
MIN_LENGTH: The minimum length of the planks. Default is 0.6m.
MAX_LENGTH: The maximum length of the planks. Default is 4.2m.
THICKNESS: The thickness of the planks. Default is 19mm.
This can be done until the script is further developed to have a user interface.

Note
The TDC Tools: Boardmaker 1.0 script is designed for use with Blender 4. It may not be fully compatible with older versions due to potential differences in the API and available features. Therefore, it’s recommended to use this script with Blender 4 to ensure optimal performance and compatibility.

For more information, find us on X (Formerly Twitter) at @Thea_D_C. Code written by T.D.C. Founder - Manoli
