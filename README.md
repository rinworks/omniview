# omniview
Viewers for objects in 3D and with varying time and space scales.

Goals:
1. A laboratory display that provides high resolution views into 3D models. The primary models
being targeting are captured stereo images of macro objects viewed from different angles, and over varying spans of time (for example, images captured using a CMRig (http://

Priorities:
1. Very high resolution and color fidelity
1. Use off-the-shelf displays and display drivers


Non Goals:
1. Not portable. This is a laboratory prototype attached to a table.
2. No motion tracking. User places their head at a fixed location - probably on a chin rest.


Approach:
User places head on a chin rest. In front are two mirrors, one targeting each eye. 
The mirrors redirect the gaze to 2 full-size displays located to the left and right.

  |  \M    M/  |		M: mirror (x2)
  |<--\    /-->|		D: display (x2)
  |   |\  /|   |		E: eye (x2)
  D   | \/ |   D
      .    .
      E    E

The angles of the mirrors and therefore the positioning of the displays will need to be tweaked
based on a prototype.
