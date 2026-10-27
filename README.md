This program runs on Windows 64 bit only and decodes SELCALs received via an audio device and displays an audio bandwidth waterfall display with a SELCAL tone overlay.

The user can select the audio device and adjust the waterfall contrast.

SELCALs that are decoded and displayed may have their associated airframe details looked up from a file called selcal_lookup.txt (included in the release).  The location of the file may be anywhere on the users PC so long as the app is pointed to it using the Browse option.  SELCALs received are saved to a file called selcal_decodes.txt in a directory of the users choice.

The main reason for this program is to display the SELCAL codes in line with the expected tone markings.  If the program does not decode and the tones are present but offset from the marker this may be attributable to one of two reasons:

a.  The receiver is not sufficiently aligned to within +/- 8-10Hz, or
b.  The transmitter (ground station) sending the SELCAL is not aligned

If you receive decoded SELCALs from a different ground station and the tones are aligned with the markers then it is likely your receiver is aligned but for the errant ground station you will need to retune your receiver to bring the tones in line with the marker.

A note about the SELCAL tones:

Those observant users will not that there are a total of 25 tones instead of the 32 tones for the latest iteration from ASRI.  The reason for this is an assumption on the authors part that the missing 7 tones (T - Z) would be difficult for the program to decipher as the minimum spacing between any new pair would likely cause miscodes and ambiguities.  Another reason for omitting these codes is that new SELCAL32 codes have so far only been observed using the numeric ranges of 2 - 9 thus perhaps, indicating ASRI will not issue T - Z tones until receiver/software technology can adequately defines these narrow spacings.

Any issues with this software please contact selcal@mail2world.com
