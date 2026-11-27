# Static EI characters

Zak, Ogre, Lizard Hermit and Estera are placed in Scenes/EvilIslandsCourtyard.json. Reusable prefabs are in Prefabs/EvilIslands/.

OBJ files are baked from EIrepack Collada; node hierarchy transforms are applied before import. No animation is sampled: these are source default/bind poses. Original source assets are untouched.

Hermit is OLiz/DragonkinOrcishF9 from bz5g. Estera is Witch/Human Gipath NPC Witch M1 from bz2g. Ogre is the OgreTutor instance from zone1. Zak uses unhuma with Human Hero skin 0, hair 1 and wool clothing; the base exported body proportions are retained, then uniformly scaled for display.

Human albedo atlases combine the corresponding Res/redress skin and clothing layers according to units.udb.csv and items.idb.csv. This is a static preview, not a runtime implementation of EI equipment, body morphing or skinning. SOURCE.json documents the source nodes, texture layers and display heights.
