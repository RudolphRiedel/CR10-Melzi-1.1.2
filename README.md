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
But I got tired of asking Creality3D and Naomi Wu to sort this out and just getting ignored.

So I did my own version of the schematic from scratch based on the Ender-3.PCB in the Ender-3 repository.
This is my try to provide data for the V1.1.2 board as I believe Creality3D should have provided themselves when starting to sell the CR-10 at least.

This is a complete Altium Designer project now, saved with AD17.
Note: the "CR-10 Motherboard.PcbDoc" is not the same as "CR-10 Motherboard.PCB", it is based on that file but already
has a couple of bugfixes implemented. Not to change anything, but to correct the faulty patched mess of the "CR-10 Motherboard.PCB".
The design-rule check still throws 618 rule violations, curtesy of Creality3D.


Here is a transcript of part of the sub-titles from Naomi WUs video on youtube called "Naomi Wu speaking at COSCon'18 (China Open-Source Conference)".
This was back in November 2018:

"I'm an Open Source evangelist."
"I am the person behind the first Open Source Hardware Association certified projects in China."
"Nice words but nothing gets done."
"Everyone talks about Open Source- show me the certification, not just a logo on a PCB."
"As I said, I think that doalog with the community is key to successful Open Source engagement."
"Every file you needed- CAD files, BOM, board schematics, firmware, everything to clone it was posted on GitHub."
"Creality3D has maintained their commitment to Open Source and have continuously released source files and maintained GPL compliance."

"You have to be relatable, not just a faceless company."
"Every successfule Open Source project has an online community."
"If your engineers are not an active participant in those communites, don't communicate with the community, the community will abandon you eventually."
"Just dumping a load of files on Github is not engagement."
"If your engineers can't manage pull requests, can't collaborate with Western developers, you aren't going to reap the full benefits of Open Source."
"Especially with Western developers."
"Then you get nothing."
"All of these things require open-minded thinking that Chinese tech companies might not be accustomed to."

What happened?
There have been no significant contributions to the Ender-3 repository after the first upload.
Almost none of the issues have been resolved.
There is no communication going on with anyone from Creality3D or Naomi Wu on their repositories.
All they do is dump, run and ignore.


Original content of the README.md:

# CR10-Melzi-1.1.2
The CR10 Melzi 1.1.2 3D Printer Motherboard is now fully Open Source Hardware Association Certified.

UID:CN000004
https://certification.oshwa.org/list.html

Hardware and software licensed under the GPL v3 license, documentation licensed under CC BY-SA 4.0 International license.
