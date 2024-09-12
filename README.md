# CPS3 SIMM/CARTRIDGE PORT ADAPTER for OSCR

![system](CPS3-OSCR.png)

The purpose of this adapter is to provide additional methods for reading and writing CP System III cartridges and SIMM memories, utilizing the excellent open-source project [Open Source Cartridge Reader (OSCR)](https://github.com/herzmx/cartreader/).

You can test it through my fork on GitHub: https://github.com/herzmx/cartreader/tree/cps3. While the R/W implementation in OSCR is not as fast as standard flash memory programmers, it allows you to dump and flash new data without needing to desolder the flash memories from the cartridge or SIMMs.

In this version, patches have been added to change the region and CD/NOCD options, based on documented dumps from MAME.


## Disclaimer!!!

**I am not responsible for any damage to your CPS3 cartridges or SIMMs. At this time, not tested the adapter on alive cartridges, so use it at your own risk!**

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. You are able to copy and redistribute the material in any medium or format, as well as remix, transform, or build upon the material for any purpose (even commercial) - but you **must** give appropriate credit, provide a link to the license, and indicate if any changes were made.
