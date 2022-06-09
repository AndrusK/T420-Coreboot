***ONLY USE WITH IVYBRIDGE CPUS***

Vast majority of all of this was made possible by https://github.com/linguine2552/ and his T420 coreboot repo (https://github.com/linguine2552/t420_coreboot_rom). The  .rom files in t420/ were all taken from his repo mentioned previously, as well as the ivy.config. When building this in the docker container put out by the coreboot team, I had no issues and was able to get things up and running right away with linquine2552’s config file for running IvyBridge CPUs on the T420.

In regards to the other .roms outside of the t420/ folder
- t420_stock.rom is the factory BIOS read from my personal T420. (this ROM is specifically for Sandy Bridge CPUs)
- t420_ivy.rom is a fresh build of the latest version of Coreboot (4.17 as of 06/07/2022) made using linquine's config.
- t420_ivy_cleaned.rom is the same as above, but ran through me_cleaner with the -S flag.
