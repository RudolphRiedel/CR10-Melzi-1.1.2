This is a fork from https://github.com/Creality3DPrinting/CR10-Melzi-1.1.2

To me Creality3D once again failed the OpenSource community.

The provided files are neither the Source or Open and as a clone of the Melzi design which is under GPL Creality3D
should have released the real files over a year earlier than the subset that they released now.
Furthermore all Creality3D does is dumping the files on Github and not supporting them in any way.
All issues with the data is ignored as well as any request.

The supplied "CR-10 Schematic.pdf" does neither match the "CR-10 Motherboard.PCB" file,
nor is it the source-file but merely a picture.
For example, the controller is named U5 in the schematic but U8 in the board-file.
And the jumper J5 from the schematic to switch VCC between USB and the 5V regulator, it does not even exist
in the board-file.
Yes, there is an issue open for that: https://github.com/Creality3DPrinting/CR-10/issues/1

In that light the OSHWA certificate is nothing but a joke to me.
Even more so as Creality3D failed to update the also "certified" Ender3 repository with the correct files.
After more than six months there still is no schematic in the Ender3 repository and the supplied board-file is
not for the V1.1.3 the Ender3 is sold with.

I asked OSHWA to review the Ender-3 certificate objectivly in order to remind Creality3D of the requirements
for the certificate, but I did not even get a reply to acknowledge that OSHWA is more than a web-page with a
mostly ignored "community" forum.


So, why the fuss, why this repository?
Regardless of that what I see is Creality3D faling to fulfill the requirements of the GPL and OSHWA,
I still do care about the repairabilty of my CR-10 and Ender-3.
So I am trying to provide data for the V1.1.2 board as I believe Creality3D should have provided
when starting to sell the CR-10 at least.

This is a complete Altium Designer project now, saved with AD17.
Note: the "CR-10 Motherboard.PcbDoc" is not the same as "CR-10 Motherboard.PCB", it is based on that file but already
has a couple of bugfixes implemented. Not to change anything but to correct the faulty "CR-10 Motherboard.PCB".
The design-rule check still throws 618 rule violations, curtesy of Creality3D.





Original content of the README.md:

# CR10-Melzi-1.1.2
The CR10 Melzi 1.1.2 3D Printer Motherboard is now fully Open Source Hardware Association Certified.

UID:CN000004
https://certification.oshwa.org/list.html

Hardware and software licensed under the GPL v3 license, documentation licensed under CC BY-SA 4.0 International license.
