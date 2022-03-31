# How to setup the MDT

When you receive the product there will be a folder with contains a GUI & Roblox Model.
The model & gui included are the only things needed for the system to work.

## Setup the MDT
* Move the Roblox model "UNGROUP WORKSPACE" & ungroup into Workspae.
* Move the Roblox model "UNGROUP STARTERGUI" & ungroup into StarterGui. We will customise the script below.
* Move the Roblox model "UNGROUP REPLICATEDSTORAGE" & ungroup into ReplicatedStorage.<br/>
![Where to move contents](https://i.ibb.co/MS2vFzh/instructions.png)

### Add Users to the UserOnly script
#### This tutorial will show you how to edit the User Only script.
* Open the script "UserOnly" inside the MDT GUI
* Add your name to the allowed table at the top. (e.g. {"UserOne", "UserTwo"})
* Close the script and play the game. You should now see the GUI on your screen

### How to change Identification code
#### This tutorial will show you how to change the identification code on the MDT.
* Open the MDT Terminal and navigate to "Identifier"
* Open the part & then open the SurfaceGui to find "Id" (this will be where you change you the identification code.)
* You change the "Text" property to the identification code
#### This will now change the identification code which you input via the MDT GUI.

