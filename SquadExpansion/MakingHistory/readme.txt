*****************************************************************************************************
      __ _______ ____     __  ___      __   _               __  ___      __ 
     / //_/ ___// __ \   /  |/  /___ _/ /__(_)___  ___  _  / / / (_)____/ / ____ 
    / ,<  \__ \/ /_/ /  / /|_/ / __ `/ //_/ / __ \/ __ `/ / /_/ / / ___/ __/ __ \/ ___/ / / /
   / /| |___/ / ____/  / /  / / /_/ / ,< / / / / / /_/ / / __  / (__ ) /_/  /_/ / /  / /_/ /
  /_/ |_/____/_/      /_/  /_/\__,_/_/|_/_/_/ /_/\__, / /_/ /_/_/____/\__/\____/_/   \__, /  
                                                /____/                              /____/ 
 
*****************************************************************************************************

Thank you for downloading the Making History Expansion for Kerbal Space Program!

Version 1.3.0

====================================================================================================
Installation / Updating:

Windows Installer:
* Run the installer .exe and follow the instructions.

OSX Installer:
* Uncompress the file provided
* Place the contents of the file in your KSP installation directory
* Run the script called dlc-mhe-[lang].command

Linux Installer:
* Uncompress the file provided
* Place the contents of the file in your KSP installation directory
* Run the script called dlc-mhe-[lang].command

Steam:
* Steam will keep the game automatically updated. You can change update preferences in Steam's application settings for KSP. 

Languages:
* Make sure you grabbed the installation file for the language you want to install and follow the above instructions.


====================================================================================================



ChangeLog:
====================================== v1.3.0 - Requires KSP v1.4.4 ===============================
+++ Improvements
* Add SPH camera panning to the GAP when SPH camera controls are set.
* Add Making History stock launch sites to Career game Points of Interest list.
* Add parameter details for any action nodes in the Missions App during mission play.
* Add validation error for nodes that have part selectors and the selected part is invalid.
* Add incompatibility checks to mission files for a range of checks including version issues and action or test modules that aren’t available.
* Improve information displayed in node body for repair node.
* Add Steam Workshop support for mission files.
* Added Steam cloud support for missions.
* Improved Mission file size and load performance.
* Reworked builder canvas and camera to improve performance
* Change line connectors in the builder to improve visual quality.
* Added GAP camera settings and canvas zoom setting to game settings.
* Added ability to set launch sites as targets for vessel crashed and landed nodes.
* Auto-recover vessels on launch sites when spawning creator defined vessels to launch sites during a mission.
* Remove launch clamps from vessels spawning splashed on liquid surface.
* Added key binding to focus the search bar in the mission builder.
* Added Escape key binding for closing all dialogs in the mission builder.
* Added tab and shift-tab key binding to move between SAP input fields in mission builder.

+++ Localization
* Localize values and status for no active vessel on test nodes.

+++ Parts
* Updated the M1-F rover wheel suspension to resolve an issue with ground bounce / jitter and increased the suspension stiffness and ground clearance.
* Structural tubes now vary mass and cost based on length/diameter.  Note that mass updates only apply to new instances of these parts - vessels in flight will not have the mass of these parts adjusted.

+++ Bugfixes
* Fix mouse scroll in the GAP to work when mouseover GAP, and not require a click first.
* Fix mission browser from locking up whilst a pending delete confirmation dialog is open.
* Fix error when docking nodes in the mission builder and selecting Undo.
* Fix NRE when deleting nodes in mission builder in pressing Delete key twice.
* Fix crew dialog list/assignments in editors (VAB/SPH) when stay in editor is selected during mission play.
* Fix spawning vessels during mission play and whilst in the flight scene.
* Fix bug when attempting to test mission from the mission builder with the default mission loaded.
* Fix destructible building log errors when changing scenes during mission play.
* Fix crew assignment test node when using multiple instances of the same craft file in a mission.
* Fix mission node updates in mission builder for nodes that have number range parameters.
* Fix resource drain node not draining resources correctly in some circumstances.
* Fix part failure and repair node display in the mission builder and missions app.
* Fix localised resource names used in the part resource drain and part resource amount nodes.
* Fix localized resource names display in mission builder node bodies.
* Fix Point Of Interest bonus being awarded for reaching new launchsites if you are able to launch directly there.
* Fix Mission Objectives Flow from missing some branches in logic.
* Fix launch site display name in mission builder canvas nodes UI.
* Fix test vessel situations against launch sites.
* Fix Mission Builder music on returning from Editor.
* Fix flag spawning at start of mission when player created vessels on start node.
* Fix stuck at loading orrery on play mission under certain conditions.
* Fix infinite loading screen if user tries to test/play an empty mission.
* Fix mission browser dialogs cancel button being not interactable after deleting a mission.
* Fix automatic completion of kerbal recovery node when set to Any kerbal.
* Fix launchsite rotation to match model rotation.
* Fix possible lock-up if mission banners are missing.
* Fix NREs when spawning vessels with RCS.
* Fix not saving a revert checkpoint when spawning vessels in flight during a mission and vessel is not set to switch to that vessel.
* Fix deleting missions and possibility to have inoperable cancel button.
* Fix builder dragging at non-100% UI scaling.
* Fix vessel spawning in a mission during flight.

+++ Missions
* Fix localized text in Mission - To the Mun Via Minmus.
* Fix localized text in Mission - Munar 1.
* Fix localized text in Mission - Sally-Hut 1.
* Fix localized crew names in Mission - Acapello 13.

+++Miscellaneous
* Corrected prices for structural tubes.

====================================== v1.2.0 - Requires KSP v1.4.3 ===============================
+++ Improvements
* Add Astronauts to the available avatars for dialog message nodes and starting briefing node and added more animations. 
* Add ability to set placeable launch pads in missions onto the water’s surface with auto-switchable model components.
* Add Dessert Runway and Launch Site (available in any game mode with Making History (Installed).
* Add ability to select The Sun and Jool on science experiment node.
* Improve tutorial highlighters for better ease of use
* Mission Difficulty is now more easily visualized with icons for each level
* Addition of new ActionGroup node so you can control the action groups from inside a mission
* Created an icon with a tooltip in the Missions App for additional information, such as timestamp on objective completion.
* Addition of an Advanced Tutorial for the Mission Builder

+++ Localization
* Fix some translation issues for part failures in the PAW.
* Fix localization of Woomerang mini-biome.

+++ Parts
* Corrected the model scale of the size 4 fairing
* The textures on the various structural panels are now symmetric
* Fixed the airlock camera, resolving an issue where some kerbals had a black portrait.
* Fixed off-center thrust on the Wolfhound and Cheetah engines.  
* Corrected the node sizes on the 3.75m structural tube
* Removed obsolete test command module from SM-25 - Plenty of space inside for player added equipment.

+++ Bugfixes
* Fix NRE when stay in editor is selected during mission vessel building and vessel has kerbals that were hired during mission play.
* Fixed an NRE caused when a 2.5m service module was the only part on a vessel
* Fix mission not progressing after stay in editor is selected during mission vessel building and the player leaves the mission and later returns and continues the mission.
* Fix ladder on Woomerang Launch Site.
* Fix mobile launch sites from not being cleaned up fully when quit to main menu from a mission.
* Fix mobile launch sites orientation to match placement in the GAP.
* Fix test orbits not being shown and spamming log when going from Mission Builder to Tracking Station.
* Fix scroll view on Tracking Station Mission Objectives list.
* Fix infinite loading screen if Tracking Station button is pressed in Mission Builder with default mission (not saved).
* Fix Null Reference Error when placing part node in mission builder and active mission has no vessel nodes.
* Fix warning on launchpad lights when not started.
* Fix no revert save being saved when mission only has creator defined vessels on the start node.
* Fix no revert save being saved when creator defined vessels spawn during the mission and are set to focus the view on these vessels.
* Fix for localization keys appearing on the UI in many places in the mission editor and flight apps.
* Fixed the impossibility of renaming new missions after a stock one had been open in the Mission Builder.
* Corrected de-clutter message when debris is removed from non-KSC launch sites.
* Fix Launch Site MapNodes in GAP being at the center of the planet.
* Fix value clamping when large number entered in Int field in SAP.
* Fix for handling corrupted zip files during mission import.
* Fix Undo/Redo behaviour with text fields and Node deleting.
* Fix for Mission Briefing saving changes when you press Cancel.
* Fixes to change mission detection for the unsaved changes warnings.
* Fix OrbitParameters node not updating all its information properly on the node text.
* Fix to SpawnVessel node to use degrees instead of radians in its Mean Anomaly values.
* Fix to the TakeKerbal node where it was getting triggered in the air for biomes and areas.
* Fix check for vessel recovery enabled in mission when clicking the launchsite facilities.

+++ Missions
*All stock missions fully localized.
*Adding Sally-Hut 1 mission.
*Adding Acapello 13 mission.
*Adding Ziggy Kerman and the Spiders from Duna mission.

Munar 1
* Fix Gold Award cannot be earned.
* Fix an incorrect fail condition.
* Grammar and punctuation corrections.

Acapello 15
* Fix Gold Award cannot be earned.
* Fix mission can be completed without bringing Valentina back to Kerbin.
* Changed vessel to any/active to avoid nodes not firing when undocking/docking.
* Changed difficulty to intermediate.
* Changed crew experience level.

+++ Known Issues
* During missions sometimes vessels and kerbals can suffer additional forces when a vessel is spawned in the middle of a mission 

====================================== v1.1.0 - Requires KSP v1.4.2 ===============================
+++ Improvements
* Show node type icon in the node header of all nodes in the Mission Builder.
* Node category color defaults amended.
* Improve CPU Load performance when placing nodes on canvas.
* Awards display now doesn’t overflow with long texts and improved awards UI design.
* Allow zoom in Mission Builder canvas to go down to 20% - can also be reduced more via settings.cfg.
* Can now delete nodes and connectors in the builder canvas with the backspace key (in addition to the delete key).
* Add mission difficulty setting to allow/disallow vessel recovery in a mission (default - disallow).
* Add ability to go to vessels on LaunchPad/Runway when clicking the Launchpad or Runway in a mission game.
* Add kerbal killed node.
* Reordered Node parameters.
* Upgrade difficulty setting for missions in the Briefing to a slider.
* Stock missions improved (see missions section below).
* Node expand/collapse button now only appears on Node headers when applicable.
* Starting funds now has a text field and slider for setting the value.
* Change vessel viewer in Mission Builder GAP to function like the VAB/SPH camera. Can be toggled via settings.cfg.
* Change Filters in vessel viewer to completely hide/show parts rather than changing their opacity.
* Change mission briefing dialog at start of mission to max-size the text.
* Fix disabled shrouds on parts reappearing when changing vessels.

+++ Localization
* Mission meta files now support localization. This indirectly also solves an issue where the expansion folder was not being removed when uninstalling the expansion.
* KSPedia fixes: Localized all images in the Making History section of the KSPedia. Added missing text to Chinese pages.
* Fix localized text for resource name on vessel resource node.
* Translations for GAP descriptions.
* Fix for certain pinned nodes coming up unlocalized.
* Fix missions not supporting non-ascii languages for mission names.

+++ Parts
* The Mk2 Pod reaction wheel EC cost has been increased for consistency with other parts.
* The Wolfhound engine is now properly centered.
* The truss sections of the 5m fairing and accompanying nodes are now scaled correctly.
* Add IVA window cameras to new command pods.

+++ Bugfixes
* Fix revert to last build/editor session in missions not always saving and therefore not allowing revert.
* Fix saving mission when entering mission difficulty settings.
* Fix checking values on time control parameters.
* Fix date handling greater than 235 years.
* Fix orbit parameters when minimized in node display in the Mission Builder canvas.
* Fix launch site being displayed when clicking on a vessel situation node with landed or 
orbit selected.
* Fix spawning orbiting vessels in missions in some circumstances causing explosions.
* Fix vessel restrictions not updating in Missions App in VAB/SPH when loading a new craft file.
* Fix hovering the mouse on slider parameters in the SAP preventing the user to continue scrolling.
* Fix copy-pasted nodes that spawn things not having unique IDs.
* Fix handling of newline and tab in message nodes to display correctly when playing a mission.
* Fix vessel resource amount node to work with unloaded vessels.
* Fix Orbit Parameter and Orbit node value sliders and max values.
* Fix Start Node activated time being always 0 UT, even when the mission was set to start at a different UT.
* Fix Vessel Naming to set default type to be the parts default type.
* Fix for vessel naming changes not updating ship name in editor scenes.
* Fix node position not been saved when moving groups of nodes.
* Fix mission not progressing when loading a create vessels node checkpoint when testing a mission.
* Fix node name changes not being updated when loading checkpoints when testing a mission.
* Fix music not playing after resuming a mission being played that was last closed in the VAB/SPH.
* Fix arrange nodes function to rescale the canvas correctly so nodes do not go off the edge.
* Scale node line connectors at low zoom levels so the lines can be seen.
* Fix node connector lines not aligning correctly when parameters are pinned/unpinned.
* Change key-combo for Copy Paste in the builder to Cmd-C, CMD-V for OS-X.
* Fix import mission zip extract method for Unix based systems.
* Fix Vessel text to correctly identify Active vs Any vessel.
* Fix node connector pin buttons triggering drag.
* Fix Orbit node to support correct accuracy testing.
* Fix event node and objective hiding so these get hidden from players.
* Fix end mission dialog coming up over a dialog message node that is set to pause the mission.
* Fix vessel viewer filters in Mission Builder GAP to switch off colliders so player can select parts inside other parts.
* Fix when selecting new or load mission in the Mission Builder with a node connector being selected breaking the Mission Builder.
* Fix the Take Kerbal node not triggering correctly after switching vessel in some cases.
* Fix the LAN orientation to match the Mission Editor in the Orbit node.
* Fix the loading screen sometimes getting locked after transitioning between scenes.
* Fix orbits sometimes getting rendered over the Mission Editor canvas after loading the tracking station or flight scenes.

+++ Missions
Dawn of the Space Age
* Added missing end conditions.
* Improved instructions with better hints.
* Improvements in the objective lists in all launches.
* Fix scoring for destroyed jebnik 1 in atmosphere.

Trouble In The Void
* Improved instructions.
* Extra test for checking if the wrong kerbal has boarded.
* Fix the explosion sequence.
* Added failure condition.

To The Mun Via Minmus
* Improved instructions.
* Removed time limit.
* Fix a Time Since Node for the second Goo Experiment not working correctly.
* Fix the objective list not updating correctly in the second launch.

Meet Me In Zero G
* Improved instructions.
* Fix craft not exploding.
* Low fuel message now appears in the second launch.
* Fix orbit accuracy parameters having incorrect values.
* Fix splash down not triggering successful mission.

Blue Moon
* Improved instructions.
* Added 3 tons to the mass limit.
* Changed the values for the fuel efficiency bonus.

Munar 1
* Added failure conditions.

Acapello 15
* Fix Time Since Node in splash test had an incorrect value causing a 5 min wait for the mission to complete.

====================================== v1.0.0 - Requires KSP v1.4.1 ===============================

* Initial Release

===================================================================================================
Copyright Notice:
©2011-2018 Take-Two Interactive Software, Inc.
The UKSA logo is property of the UK Space Agency. Used with permission.
