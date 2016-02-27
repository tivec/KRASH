# KRASH
KRASH - Kerbal Ramification Artifical Simulation Hub (simulation mod for KSP)

This mod includes version checking using MiniAVC (http://forum.kerbalspaceprogram.com/threads/79745)
If you opt-in, it will use the internet to check whether there is a new version available. Data is only
read from the internet and no personal information is sent. For a more comprehensive version checking 
experience, please download the full KSP-AVC plugin (http://forum.kerbalspaceprogram.com/threads/79745">KSP-AVC Plugin)

KRASH lets you launch flights from the VAB\SPH, and when the flight is over, it restores the game to the exact state that 
it was in before the simulation started. It handles restoring the state of any mod which stores its data in the vanilla 
persistence file (basically any of them worth their salt), and even handles it if you exit the game during a simulation.

Instructions


In the VAB/SPH, load the ship you want to simulate
Click the SIM button, you will see the following screen:
[screenshot 0]

The buttons at the top select the starting location, and are as follows:

Kerbin - The homeworld of the game.  If you are running a mod which changes the homeworld, it will be shown here
Landed - Start sim landed on any planetary body
Orbit Selection - Start sim in an orbit around any planetary body

In career mode, if you haven't reached a planetary body, you won't be able to start the sim there

Starting sim at Kerbin
You will be able to start the sim either at the Runway or the Launchpad.  Selected which one you want,see this screen:
[screenshot 1]

Starting sim Landed
There is a row of buttons which will allow you to filter the displayed planetary bodies by either planets, moons, or all.
Select the planetary body you want to start the sim at from the displayed list.  Also, 
enter an altitude where the vessel should be started at.  You can also enter the Latitude 
and Longitude for the starting location.  It will start there, and very 
slowly descend until it touches the ground.  See the following screen for details:
[screenshot 2]

Starting sim in Orbit
There is a row of buttons which will allow you to filter the displayed planetary bodies by either planets, moons, or all.
Select the planetary body you want to start the sim at from the displayed list.  Also, 
enter an altitude where the vessel should be started at.  Note that when you select a body, the
altitude will be automatically adjusted to be just outside the atmosphere if it has one, or
at an altitude of 10000m.  You can override it with whatever values you want.

Click the big green button to start the simulation

IMPORTANT NOTE:  If you are running RemoteTech, be sure that ALL your antennas are set to start retracted,
otherwise they will be ripped off during the teleportation process.

During the simulation, everything works normally, except you can't go to the Space Center.  Hitting the Escape key
will bring up the Simulation menu, see the following screenshot:
[screenshot 3]

At this menu, you can either restart the simulation, or terminate the simulation and return to the editor.

In the event of either a game crash during the simulation, or exiting the program, restarting the game will restore 
the game to the point just before you started the simulation.

When the simulation is terminated, you will see the usual flight history dialog before the final revert.