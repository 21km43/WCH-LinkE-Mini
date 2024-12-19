# WCH-LinkE-Mini

This project is compatible with [WCH-LinkE](https://www.wch-ic.com/products/WCH-Link.html)

## Requirements
* [KiCAD 8.0](https://www.kicad.org/)
* [Fabrication-Toolkit (Optional)](https://github.com/bennymeg/Fabrication-Toolkit)

## Feature
* Change USB Connector to Type-C
* Optimize for ordering [JLCPCB](https://jlcpcb.com)

## LICENSE
[MIT LICENSE](/LICENSE)

## Parts List
[Parts List](/production/bom.csv)

## Schematic and Board image
[Board schematic](WCH-LinkE-Mini.pdf)  
![Board Image](WCH-LinkE-Mini.png)

IDC Connectors are available here
- [IDC-Header(socket)](https://www.digikey.jp/ja/products/detail/sullins-connector-solutions/SBH11-PBPC-D05-ST-BK/1990062)
- [IDC-Header(header)](https://www.digikey.jp/ja/products/detail/sullins-connector-solutions/SFH11-PBPC-D05-ST-BK/1990087)

## Previous version & Changelog

- v1.2.0 (latest)
  -  Add a resettable fuse for 5V output (Trip current is 750mA)
- v1.1.0
  - Fix fill zone
  - Fix trace width for 3.3V and 5V
  - Change 3.3V LDO from AMS1117-3.3 to XC6206P332MR-G
  - Change load switch structure
  - Change resistor value for LEDs
  - Minimize board size
- [v1.0.0](https://github.com/21km43/WCH-LinkE/tree/f1d92fe91850c45036395253008bbfae57f4c86a)
  - First release
