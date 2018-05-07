ULTIMATESHUTTLEIVA - Full Retro

This is the initial testing version of Full Retro. As should have been stated already, we need to look at prop placement and functionality, efficiency of prop placement for gameplay purposes, and to see where and what other improvements can be made to the design.
---
Requirements:

KSP 1.4.2  - I designed in 1.4.2, but it will likely work in earlier versions depending on MAS, as the latest release for that and what ksp version it is for would define the required version. 

MAS - https://forum.kerbalspaceprogram.com/index.php?/topic/160856-wip-14x-moardvs-avionics-systems-mas-interactive-iva-v0130-18-march-2018/

RPM - https://forum.kerbalspaceprogram.com/index.php?/topic/105821-14x-rasterpropmonitor-still-putting-the-a-in-iva-v0300-14-march-2018/

ASET Props and Avionics Packs - https://forum.kerbalspaceprogram.com/index.php?/topic/116430-aset-props-pack-v15-for-the-modders-who-create-iva/

https://forum.kerbalspaceprogram.com/index.php?/topic/116479-aset-avionics-pack-v-21-for-the-modders-who-create-iva/

BDB - https://forum.kerbalspaceprogram.com/index.php?/topic/122020-14x-bluedog-design-bureau-stockalike-saturn-apollo-and-more-v142-%D0%B0%D1%82%D0%BB%D0%B0%D1%81-1feb2018/   ( Strictly only need the props folder from BDB for its flight seats. Currently the only good looking seats I could find that were also compact enough to allow for the numerous seats in the cockpit)

Module Manager

Required for full functionality in IVA:

MechJEB
Kerbal Alarm Clock
Chatterer

---
Installation:

Presuming you have the requirements in place, drag and drop UltimateShuttleIVA into your Gamedata.  The MM Patch within will set up the internal for the Mk3 Cockpit, and set its crew capacity to 6. 

---
CHANGELONG:

V0.01: Initial Testing Release

v0.02: Second Testing Relz.

	*Fixed MM Patch, killing IVA bugs across game.
	*Added Overlay, allowing for better cutaway in external views.
	*Reconfigured Panels - Comms Panel moved center console. Docking Panel added X-pointer. More useful in-game than a simple RCS hand controller. Turn Coordinator deleted, replaced with Landing Gear Control section. Left and Right most panels angled inward.
	*Adjusted HUD placements. Provides better downward FOV out of window
	*Deleted redundant Fuel/Ox gauges on center Gauge panels. Replaced with SRB Gauges
	*New Label props added.
	*Commander and Pilot Seats moved backwards in preparation for Transform update - KNOWN ISSUE: They do not line up with the transforms, they have not been edited yet.
	*Further refinement of prop placement across the board

v0.03: Third Testing Relz

	*Added Camera Transforms for Docking section, Cmd and Plt seats, as well as farthest port and starboard windows. By clicking on back left and right walls, can view mid-deck from two angles.
	*Docking Section - Set of controls for docking.
	*Fixed placement of Window model, should no longer have any gaps.
	*KNOWN ISSUE: Princibly Docking Section issue, all MAS props do not work while in any camera transform view. Resolution pending research and possible fix to MAS from MoarDV

v0.04: Fourth Testing Relz

	*Full Retro Revamp - Rebuilt the IVA from zero. Features -much- better accuracy to the real cockpit as well as better functionality across the board.
	*Stop-gap measure to enable Docking controls. Docking section's instruments are purely RPM. They can be used, but any issues short of placement issues are -NOT- to be reported, as they won't be fixed or fixable. 
	*Known Issues: 
		-CRT Displays upfront are kind of pointless. My next deveopment cycle this weekend wil focus on creating an MFD out of this prop.
		-Related to above, docking section lacks the accurate CRT it should have. Not adding until I have a proper CRT.
		-Upper panel switches, buttons, and rotaries have no animation. Need to touch base with MoarDV on syntax for dummy switches in MAS. Are also obviously copied and pasted everywhere. Is being put in the project to space them out semi-randomly in places to make the upper panels a bit more interesting.
		-FDAI's do not have a back panel currently. Kept running into some strange bug that kept messing up the panels I had. Will try again with it later, but for now deleted to spare the nonsense.
		-Side "shelves" are kind of bare short of hand holds and Light controls. May or may not populate this with stuff. 

v0.05 Fifth Testing Relz -Tentative FullRetro Release- Requires latest update of MAS!

	*New CRT Displays - RETRO MFD's!
	*Fixed placement on props in center console.
	*Docking Controls are now MAS again, as MAS bug has been fixed. CRT Displays have been added to section
	*New props from NFProps - New Dependency!
	*New Camera view, nicknamed Glory. To access it, turn your kerbals head towards the back of the pit, and click towards the top of the screen. 
	*As a result of the new view, the docking view point access has changed slightly. You still turn towards the back, but click towards the floor.
	*Recover Vessel buttons removed - Buggy
	
	
-------
This is probably where I put a bunch of legal and credit crap. I'm not worried about it right now.