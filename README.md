# 120wd
file factory.bin chính là phân vùng mtd chứa mac và cấu hình wifi
bootloader.bin là bootloeader gốc 

# firmware openwrt
openwrt-ramips-mt7621-viettel_vap-120wd-squashfs-sysupgrade.bin


Hardware Specification:
```
SoC: Mediatek MT7621AT (MIPS1004Kc 880 MHz, dual core)
RAM: 128 MB
Storage: 128 MB NAND flash
Ethernet: 3x 10/100/1000 Mbps LAN1,LAN2 & WAN
Wireless: 1x 2.4GHz & 5GHz: Mediatek MT7615DN up to 1300Mbps 
          (802.11b/g/n/ac MIMO 2x2)
LEDs: 5x North (Blue), East (Blue & Red), West (Blue & Red)
Buttons: 1x WPS/Reset
UART: yes

```
Flash Instructions:
```
1. Prepare OpenWRT factory image & TFTP server
2. Connect UART
3. Press 2 to get into bootloader firmware download mode -> press 'y'
4. Enter device's IP / TFTP server's IP / Factory image name when asked
5. Wait for device to reboot
```
