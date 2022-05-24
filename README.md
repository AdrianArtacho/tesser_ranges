This Patch is part of the [TESSER environment](https://bitbucket.org/AdrianArtacho/tesserakt/src/master/).

![TTESS:Logo](https://bitbucket.org/AdrianArtacho/tesserakt/raw/HEAD/TESSER_logo.png)

# Tesser_Ranges

This Patch is part of the TESSER environment.

![TESS:ranges](https://docs.google.com/drawings/d/e/2PACX-1vTd87VvT12Wwtq1X0U8FDUD_WdUwUhupUs52MiELvew95H0aXn0fMG8_2t1Kb0z0WI8AZdzeiJ3NMuH/pub?w=240&h=177)

## Usage

**CC86** Center of the range

**CC87** Width of the range

____

# To-Do

* Finish documentation...
* <> sppedlim 60, deferlow, to sones out!
* <> Ranges could have midi pitches as input (as it is working now) but also take in CC controller data, so that I can SCLAE and WARP the values stored in a clip dynamically, preserving the inflexions but adapting the range...
* Have different modes: GATE (only notes within the range are let through), SCALE (map 0 -127 values onto the limits of a range; for this one I would need at least an additional MAX value, which can be set via CC 117), and WARP (which makes all inputted notes fit within a given range, but not scaling equally but warping the edges of the range and leaving the central part relatively undistorted; a MAX value CC117 would be here also of use)
* <+> The popup window: set dimensions via command, so I don't have to deal with that everytime I edit the patches.
* <+> the popup windoe dowsn't seem to be responsive if I am not focused on the device at that moment@!
* <+> have display show on the left the incomming midinote, and on the right, the notes out
* <+> would it be possible to show all the incomming/outcoming notes, and not only the slider?)
