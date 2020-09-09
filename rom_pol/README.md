# Sonic the Fighters Object Models
This folder contains *all* object files within the game. All 4475 of them.
## There are a few things to note about this archive:
- ### There are no textures mapped to these models:
There is no current way to understand how the placement of texture files and the objects relate. When this is understood, the information will become available in this disassembly via a script or a tool.
- ### There is no pallet data mapped to these models
There is currently no automatic way to understand how to translate pallet data to all the surfaces of the model. When this is understood, the information will become available in this disassembly via a script or a tool.
- ### There is no skeleton data yet to map the player model objects to (yet)
Each player has their own skeleton data that connects approximately 16 model objects to make up a player seen in-game. When this is understood, the information will become available in this disassembly via a script or a tool.
- ### These models are for research purposes only
Until the problems above are resolved, any models created using the assets in this folder will be inaccurate and are not endorsed by this project. We kindly ask that fan game makers, modders, artists, and anyone else interested in using these assets kindly refrain from doing so until we have achieved usable models 1:1 accurate with what is seen in-game. We realize we can't stop you from doing this and users of your creations will most likely never see this message, but I believe hoarding this data until a point  of 1:1 game accuracy would be a disservice to the research community.
- ### Models can not yet be re-imported into the game
This is top priority (and probably most simple thing to do on this list).
- ### You will see an abundance of duplicates
The game engine may reuse the same model for Sonic's head, Sonic's shadow head, Grey Sonic's head, and Grey Sonic's shadow head. This does not mean they are numerically the same model. If you find a model you wish to understand further, fully colored and textured, please enable the in-game debug menu and use the POLYGON TEST feature to explore the model within the game's engine.