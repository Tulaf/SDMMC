/*!
    \file  README.TXT
    \brief description of the sdio copy from SDCard
    \version 2021-3-18, v1.0.1
*/

Function description:
    This demo shows copy files on the SD card through SDIO.
    NOTE: An SDCard in FAT32 format should be prepared first, store a file named fatfs.txt on the SD card.

Test result:
    If the terminal displays the desired print, the execution succeeds.

IO Connection information:
    Connect SDIO0 SDIO0_SDCLK      to SDCard CLK
    Connect SDIO0 SDIO0_SDCMD      to SDCard CMD
    Connect SDIO0 SDIO0_SDDATA0    to SDCard DAT0
    Connect SDIO0 SDIO0_SDDATA1    to SDCard DAT1
    Connect SDIO0 SDIO0_SDDATA2    to SDCard DAT2
    Connect SDIO0 SDIO0_SDDATA3    to SDCard DAT3
