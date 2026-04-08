# NETGEAR_C6250

* [Manufacturer product sheet](https://www.downloads.netgear.com/files/GDC/datasheet/en/C6250.pdf)
* [Manual](https://www.downloads.netgear.com/files/GDC/R6250/R6250_UM_15April13.pdf)

![case_front.jpg](photos/case_front.jpg)

![case_rear.jpg](photos/case_rear.jpg)

![case_right.jpg](photos/case_right.jpg)

![case_bottom.jpg](photos/case_bottom.jpg)

## Checklist

- [x] Reference materials
    - [x] Manufacturer docs
    - [n/a] Firmware updates
    - [n/a] Third-party references
- [x] Factory reset
- [x] External documentation
- [x] Internal documentation
- [ ] Dumped ROM

## Critical Info

![case_bottom_label.jpg](photos/case_bottom_label.jpg)

External label:

```text
NETGEAR
AC1600 Wi-Fi Cable Modem Router
Model: C6250
WiFi Network Name (SSID): NETGEAR09
Network Key (Password): hungryflute369
DOCSIS 3.0
16 DS 4 US
SERIAL: 4BJ18C78A011D
MAC: 288088BE3EF0

12V 2.5A
-@+

```

## Reference material:

No open sources.

## Board
![board_top_1.jpg](photos/board_top_1.jpg)

![board_and_heatsink.jpg](photos/board_and_heatsink.jpg)

![board_top_2.jpg](photos/board_top_2.jpg)

![board_bottom_1.jpg](photos/board_bottom_1.jpg)

![board_bottom_2.jpg](photos/board_bottom_2.jpg)

Markings:

Top side, low:

![board_label_top.jpg](photos/board_label_top.jpg)

```text
U12C326
801840
REV.0 GP
```

Bottom side, high:

![board_label_bottom_1.jpg](photos/board_label_bottom_1.jpg)

```text
ZRV4JFJ
U12C326T00
2140008831-0a
```

Bottom side, low:

![board_label_bottom_2.jpg](photos/board_label_bottom_2.jpg)

```text
AVA94V-0 RU
E253117 ML1  H
RC4F23732DH  1338
```

### U101 Broadcom BCM33843 QAMLink DOCSIS 3.0 SoC

![photo](photos/chip_U101_Broadcom_BCM3384.jpg)

* [Manufacturer page](https://www.broadcom.com/products/broadband/cable/modems/bcm33843)
* Package: FCBGA with heat spreader
* Markings: 

```text
BROADCOM(R)
QAMLink(R)
BCM33843GKFSBG
CN1710 P20
633-23 N3A1 W
```

### U220 Samsung K4B2G16 2 Gib Parallel NAND Flash

![photo](photos/chip_U220_Samsung_K4B2G16.jpg)

* [Datasheet]()
* [Manufacturer page]()
* Package: FBGA-96
* Markings:

```text
K4B2G16
```

* 2 Gib = 256 MiB

### U304 Macronix MX25L4006E 4 Mib DSPI NOR Flash

![photo](photos/chip_U304_Macronix_MX25L4006E.jpg)

* [Datasheet]()
* [Manufacturer page]()
* Package: 
* Markings:

```text
MX25L4006E
```

### U370 Winbond W29N01HVSINA 1 Gib Parallel NAND Flash

![photo](photos/chip_U370_Winbond_W29N01HVSINA.jpg)

* [Datasheet](https://www.winbond.com/hq/support/documentation/downloadV2022.jsp?__locale=en&xmlPath=/support/resources/.content/item/DA00-W29N01HVXINA.html&level=1)
* [Manufacturer page](https://www.winbond.com/hq/product/code-storage-flash/onfi-nand/?__locale=en)
* Package: TSOP-48 (Type I)
* Markings:

```text
W29N01HVSINA
```

### U1189, U1190, U1195 Skyworks SKY85712-21 5 GHz Front-End Module

![photo](photos/chip_U1189_U1190_U1195_Broadcom_FMF5691.jpg)

* [Datasheet](https://www.skyworksinc.com/-/media/SkyWorks/Documents/Products/2001-2100/SKY85712-21_202994K_discontinued.pdf)
* [Manufacturer page](https://www.skyworksinc.com/Products/Front-end-Modules/SKY85712-21)
* Package: QFN-16
* Markings:

```text
FMF
4591
```

### U1192 Broadcom BCM4360 MIPS32 802.11ac SoC

![photo](photos/chip_U1192_Broadcom_BCM4360_1.jpg)

* [Datasheet]()
* [Manufacturer page]()
* Package: QFN-408
* Markings:

```text
BCM4360KMLG
```

### U1194 Broadcom BCM43217 MIPS32 802.11n SoC

![photo](photos/chip_U1194_Broadcom_BCM43217T.jpg)

* [Datasheet]()
* [Manufacturer page]()
* Package: QFN-68
* Markings:

```text
BCM43217TKMLG
```

### UA6 AME AME8816 1.5 A Voltage Regulator

![photo](photos/chip_UA6_AME8816.jpg)

* [Datasheet](https://www.ame.com.tw/datasheet/22-AME8816_20150909_I.01.pdf)
* [Manufacturer page]()
* Package: SOP-8
* Markings:

```text
AME8816
BEHAADJ
```

### UA8 Texas Instruments LM358 Dual Op Amp

![photo](photos/chip_UA8_TI_LM358.jpg)

* [Datasheet](https://www.ti.com/lit/ds/symlink/lm358.pdf)
* [Manufacturer page](https://www.ti.com/product/LM358)
* Package: SOIC-8
* Markings:

```text
LM358
AKKIV
```

I wonder what this one is for.
There doesn't seem to be any audio on this board.
It's on the flip-side of the power management area.

### UI2 Broadcom BCM54612E Gigabit Ethernet Transciever

![photo](photos/chip_UI2_Broadcom_BCM54612E.jpg)

* [Datasheet](https://datasheet.octopart.com/BCM54612EB1IMLG-Broadcom-datasheet-179056622.pdf)
* [Manufacturer page](https://www.broadcom.com/products/ethernet-connectivity/phy-and-poe/copper/gigabit/bcm54612e)
* Package: MLP-48
* Markings:

```text
BCM54612E
```

### J1 UART

![conn_J1.jpg](photos/conn_J1.jpg)

This one is closer to the QAMLink chip.

### J2 UART

![conn_J2.jpg](photos/conn_J2.jpg)

This one is closer to the BCM4360 SoC.

## Firmware

It probably uses eCos like the BCM3833 chips,
but I don't feel like pursuing it right now.

## Conclusion: ?
