**IL-2 VR Snapview Mod**

A collection of modified script files to correct VR head position in the IL-2 Great Battles Series. 

The current planes modified are the following:

Axis:

* Bf-109 (E7, F2, F4, G2, G4, G6, G6-Late, G14, K4)\*\*
* Bf-110 (E2, G2)\*
* Fw-190 (A3, A5, A6, A8, D9)\*\*
* Hs-129 B2\*\*
* Mc-202 S8\*\*
* Me-262 A2\*\*

Entente:

* Sopwith Dolphin\*\*
* Spad XIII\*\*
* Bristol F2b (F2, F3)\*\*

\* Adjusted for only seating distance.

\*\* Adjusted head center and seating distance, if needed.

**Installation**

Copy the "snapviews" folder to the "..\data\LuaScripts\" folder of the IL-2 root directory. Overwrite the files already in the directory.

**Uninstallation**

Replace the conents of the "..\data\LuaScripts\" directory with that of the "..\data\LuaScripts\defaults" directory.

**Notes**

The snapview files contain many variable arrays that are arranged in the following manner:

*A, B,			Z, Y, X,		F;*

These variables represent the following:

* A - Camera Pitch from -1 to 1 (roughly -90 degrees to 90 degrees).
* B - Camera Yaw from -1 to 1 (-360 to 360 degrees).
* Z - Camera position forward (positive) or backward (negative); roughly in meters.
* Y - Camera vertical position up (positive) or down (negative); roughly in meters.
* X - Camera horizontal position left (negative) or right (positive); roughly in meters.
* F - Camera field of view from 1 (30 degrees) to -1 (150 degrees); More information can be found at the following forum post: <https://forum.il2sturmovik.com/topic/41919-snapview-svc-file-exactly-fov-calculation/>

**Links**

* [www.github.com/Stiggles/IL2-VR-Snapviews](http://www.github.com/Stiggles/IL2-VR-Snapviews) - The source of this file and the snapview files associated with it.
* [www.il2sturmovik.com](http://www.il2sturmovik.com) - The main website of the IL2 Great Battles series.
* [forum.il2sturmovik.com](http://forum.il2sturmovik.com) - The IL-2 Great Battles series forum.

