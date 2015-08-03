#BAMBA-TV FIRMWARE

Contains firmware for the BambaTV decoder firmware used in kenya which runs a mips processor.The binary firmware is ./Firmware and the hex output with associated 
character representations is stored in ./hex_bamba.out.The strings in the firmware are shown in by the strings* or *strings* text documents in ./ .It uses a variant 
of the U-boot bootloader.The bootloaders environmental variables are stored in ./decoder-environmental-variables.The kernel was store as a compressed LZMA file
was uncompressed and contents kept in ./extracted-file-kernel/ folder.The Serial output at 115200 8N1 is kept in ./M-boot serial/
