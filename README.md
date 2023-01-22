# GA-B75M-D3V-(or -D3H)

Based on the work of hnanoto (https://github.com/hnanoto/EFI-Desktop-Gigabayte-GA-B75m_D3H---i7-3770---RX-570-)

OpenCore 0.8.8 

Mac Os 12.6.2 (Monterey)


As always .... fill in platform info


Components

Intel i5-3570K Ivy Bridge Processor

Alpenfohn Sella CPU Cooler 

Gigabyte GA-B75M-D3V Motherboard

16GB  DDR3 1600MHz Memory 

ENERMAX 82 PRO 425 W PSU

SanDisk Ultra II 240GB SATA III 2.5-Inch SSD 

Western Digital Green 640GB HDD

Western Digital Green 800GB HDD

Sapphire RX 560 Pulse 2GB Graphics Card

NZXT Case (no data for model)

Tp-Link TL-WN722N WLAN USB (https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)


# PROBLEMS SO FAR
1. When loading OpenCore I get one ACPI error:
00:000 00:000 OC: Failed to drop ACPI 54445353 0074734930757043 0 (0) - Not Found

2. I am having restart and sleep issues.
a. Computer fails to wake from sleep. 
b. When restarting it show that the computer shut down due to an error. 

3. If when loging in the selected default sound output is headphones, then go in config.plist->DeviceProperties-> Add-> PciRoot(0x0)/Pci(0x1b,0x0) and change layout-id from 0B000000 to 05000000   
