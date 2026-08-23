# 80mm-Dust-Shoe
Dust shoe for a 80mm spindle which is dockable

double stacked N52 6x3mm magnet's are used to attract the dockable ring to the dust boot dock and keep it in place a single 6x6 would work as well. Make sure of the direction on the two parts, upper and ring or you'll be reprinting it. Also used to attach the ring to the shoe.
m3x14 and inserts from a voron build are used to attach the shoe to your spindle.
thin foam padding is added to the ring and the shoe helping with a vacuum seal between them

Printable on Bambu P1S or X1C in your choice of colors.

Included are a couple of functions for MachPro. These should be placed in the <Profile>/Macros/Scripts/UserMCodeModule.mcs (Renamed from UserMCodeModuleDefault.mcs). Compile scripts. 
A couple of persistant Register values are also needed. IgnoreDustBoot, DustBootStatus. Adding a button to the MachPro screen for IgnoreDustBoot which is a toggle to do exactly what it suggests.
DustBootStatus is just how we keep track of where the boot is. Location of the register's are in the functions.

Magic values are in the functions for Locations, feedrates etc. So make sure you modify them as your machine is differant than mine.

Dock was created by me in Fusion360. Logan of PrintNC created the ring and top which were then modified by me adding the magnets for stability in Dock and other minor changes. (beefier mount bracket for spindle attachment).
