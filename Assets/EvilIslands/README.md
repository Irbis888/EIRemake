# Evil Islands courtyard

Open Scenes/EvilIslandsCourtyard.json. It is the project startup scene.
The original Scenes/Main.json was preserved. Previous project settings are in MyGame0.lsproject.before-ei.

10 distinct static EI assets: Human House, Kanian House, Travel Tent, Army Tent, Well, Cart, Ogre Chest, Hadogan Chest, Altar, Stone. Ground is an additional engine primitive.

Sources were extracted locally under C:/GOG Games/repack-out with EIrepack. Collada node transforms and Z-up conversion were baked with Assimp into OBJ before import; OBJ material texture paths are relative to the project root. All required textures are included. SOURCE.json lists the original files and bounds.

This is a static scene: no character animation, gameplay or custom collision meshes were added. The two source textures that contain alpha use the current engine opaque material path; masked-material support has not been added.
