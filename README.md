# EULA Popup Addon
is a lightweight Minecraft Bedrock behavior pack that displays a Terms of Service in a popup to players the first time they join your server or world.  
Players must actively accept the rules before playing.  
if they decline, they are kicked and can rejoin at any time to accept.  

Features:

Popup appears automatically 30 seconds after a player's first join, giving them time to load in
Acceptance is saved permanently — returning players never see it again
Fully customizable text, buttons, and messages via eula_config.js  

commands:  
/function show.eula — manually show the popup to yourself at any time
/function eula.reset — wipe all acceptances so every player sees the popup again on next login (operators only)

Installation:

Double-click EULA_Popup_Addon.mcaddon to import into Minecraft
Add the behavior pack to your world
Enable Beta APIs under Experimental Features in your world settings

Customization:
Open behavior_packs/EULA_Popup_Addon/scripts/eula_config.js and edit the text to match your server rules. Restart the world to apply changes.
