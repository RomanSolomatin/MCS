
PROJECT
-
<b>Unreal Engine 4 Melee Combat System (aka Open Saber Project)</b>

Prototype Gameplay: https://www.youtube.com/watch?v=QPkMwPUsyTo

<b>Target Platform:</b> PC (Windows and Linux)

<i>This is an open source project created by and for JK fans in an attempt to re-create the multiplayer melee combat in the Jedi Knight series of games using a modern game engine (UE4).</i>

<i>The main goal of this project is to create a full featured multiplayer (client/dedicated server) melee combat game using Unreal Engine 4.</i>

<i>This project is NOT meant to be a one-to-one remake of Jedi Outcast/Jedi Academy, but as mentioned above, it focuses on the combat systems of those games.  Specifically, a free-flowing sword melee and movement system (including acrobatics) which may be used in any setting.</i>

This project is currently in the prototype stage.  For multiplayer, it has a very basic menu system for the client to connect to a dedicated server via IP address (local host or Internet).  Basic movement and combat are implemented using animations (mostly) from Jedi Outcast.  In short, there is still a lot of work to be done.

How to Contribute
-
The project is currently built using Unreal Engine 4 (version 4.18.3).

This prototype is almost exclusively done using UE4’s blueprint system (so no C++ is required), however, it is built using the UE4 source due to the fact that it requires a dedicated server.  You will need Visual Studio Community 2017 in order to re-build the project using the downloaded version of the engine.  Ensure that your Visual Studio installation is setup correctly for development with UE4 (https://docs.unrealengine.com/latest/INT/Programming/Development/VisualStudioSetup/).

In order to create the binaries, you will also be required to download the UE4 source code (https://docs.unrealengine.com/latest/INT/Programming/Development/BuildingUnrealEngine/)

<b>1)</b> Download UE4 (version 4.18).

<b>2)</b> Clone the "develop" branch of this repo (https://github.com/ClydeFrog68/MCS.git) to a local directory of your choice.

<b>3)</b> Right click on the ".uproject" file and "switch engine versions" and select 4.18.  When you try to launch the project you will be prompted to re-build.  If you have installed Visual Studio (with the required components for UE4), the project should build and launch the editor.  

<b>4)</b> Once inside the editor in the top toolbar -> source control (second from left), choose Git for source control and then "connect to source control".

Any contribution(s) would be welcome.  Character models, animations, maps (levels), props, sounds, music, AI bots, anything.  If you have any questions, feel free to send me an email.  I’ll get back to you as soon as possible.

Project Info
-
<b>Discord server:</b> https://discord.gg/M25fJx4

<b>Project Email:</b> <i><b>mcsgitproject@gmail.com</b></i>

PROTOTYPE BINARIES (version 0.0.0.3)
-
Windows Client: 
https://drive.google.com/open?id=1b4DrWmpXmNC5bNYg2TXwBP1LoEPjXwhh

Windows Server: 
https://drive.google.com/open?id=1UQqFquoH2LmN_P2a2cZfLmoKDUAQZ09-

Linux Client: 
https://drive.google.com/open?id=1enz61HZh3F5UVW8rJMDDDIxo7Ti0GLws

Linux Server: 
https://drive.google.com/open?id=1BZebzLWTvTrWNMXKLDi7ab0ntW2-lkro

<b>NOTE: You must also install this patch - just copy the file (*.pak) to your MCS\content\paks.</b>  
<b>IMPORTANT:  Remove the savegame from MCS\Saved\SaveGames (if you have one).  The game will make a new one.</b>

PATCHES (0.0.0.3p1)
-
Windows Client: 
https://drive.google.com/open?id=1QBZpqkAZdLj7ryeIDnsqRjtL8dzY-du9

Windows Server: 
https://drive.google.com/open?id=1_9x8QG2rQuX4vbvk8VOZRjTm4zqNS5xA

Linux Client: 
https://drive.google.com/open?id=1kxKqo8tnob3KSNFvqonqw_hTnNX03OcI

Linux Server: 
https://drive.google.com/open?id=1lguxyTbnvj7e4AzkToNXYuaeB4PXmWaC

