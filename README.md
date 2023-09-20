# Build DAO

 - [ ] Order PCB (jlcpcb)
 - [ ] Order all components needed for build (aliexpress)
 - [ ] Receive PCB
 - [ ] Receive all components
 
### PCB

| Reference    | Name                      | Package  | Value           | AliExpress                                                                                                                                                                      | LCSC    | Qty |
|--------------|---------------------------|----------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|-----|
| BT1          | JST                       | ?        | 1.25mm 2pin 90° | [1.25mm 2pin 90° 50 pcs](https://aliexpress.com/item/10000064127272.html?sku_id=20000000117379413)                                                                              | ?       | 2   |
| C1-C2, C4-C5 | Capacitor                 | 0603     | 10uF            | [10uF - 100 pcs](https://aliexpress.com/item/32966526545.html?sku_id=66569661174)                                                                                               | C19702  | 8   |
| C3           | Capacitor                 | 0603     | 1nF             | [1nF - 100 pcs](https://aliexpress.com/item/32966526545.html?sku_id=66569661147)                                                                                                | C1588   | 2   |
| C6-C7        | Capacitor                 | 0603     | 4.7uF           | [4.7uF 100 pcs](https://aliexpress.com/item/32966526545.html?sku_id=66569661173)                                                                                                | C19666  | 4   |
| D1-D22       | Diode                     | SOD-323  | 1N4148WS        | [1N4148WS SOD-323 - 100 pcs](https://aliexpress.com/item/32849879904.html?sku_id=65195962305)                                                                                   | C57759  | 44  |
| D23          | Diode                     | SOD-123  | 1N5819W         | [1N5819W SOD-123 - 100 pcs](https://aliexpress.com/item/32849879904.html?sku_id=65195962304)                                                                                    | C169540 | 2   |
| D24          | LED                       | 0603     | RED             | [0603 RED - 100 pcs](https://aliexpress.com/item/1206456185.html?sku_id=65106628406)                                                                                            | C2286   | 2   |
| D25          | LED                       | 0603     | BLUE            | [0603 BLUE - 100 pcs](https://aliexpress.com/item/1206456185.html?sku_id=65106628409)                                                                                           | C72041  | 2   |
| F1           | Fuse                      | 1206     | 500mA           | [1206 500mA - 50 pcs](https://aliexpress.com/item/32907456681.html?sku_id=12000033093354867)                                                                                          | C355568 | 2   |
| J1           | USB Receptacle            | ?        | ?               | [1.6mm - 10 pcs](https://aliexpress.com/item/32998900371.html?sku_id=12000021526913497) [0.8mm - 10 pcs](https://aliexpress.com/item/32998900371.html?sku_id=12000021526913496) | C168688 | 2   |
| K1-K22       | Kailh Choc Hotswap Socket | ?        | ?               | [90 pcs](https://aliexpress.com/item/33023283633.html?sku_id=10000000883911874)                                                                                                 | ?       | 44  |
| Q1           | P-Mosfet                  | SOT-23   | AO3401A         | [50 pcs](https://aliexpress.com/item/32990534792.html)                                                                                                                          | C15127  | 2   |
| R1-R2        | Resistor                  | 0603     | 5.1k            | [5.1K - 100 pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475028)                                                                                    | C23186  | 4   |
| R3           | Resistor                  | 0603     | 4.7             | [4.7R - 100 pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109357956)                                                                                    | C23164  | 2   |
| R4           | Resistor                  | 0603     | 1M              | [1M - 100 pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475082)                                                                                      | C22935  | 2   |
| R5           | Resistor                  | 0603     | **806k***       | [820K - 100pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475080)                                                                                     | C103828 | 2   |
| R6-R7        | Resistor                  | 0603     | 1k              | [1K - 100pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475011)                                                                                       | C21190  | 4   |
| R8           | Resistor                  | 0603     | 2M              | [2M - 100pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475089)                                                                                       | C22976  | 2   |
| R9           | Resistor                  | 0603     | **RPROG****     | [3.3K - 100pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475023)                                                                                     | C22978  | 2   |
| R10          | Resistor                  | 0603     | 100k            | [100K - 100pcs](https://aliexpress.com/item/1005001436923851.html?sku_id=12000016109475058)                                                                                     | C25803  | 2   |
| SW1          | SPDT Switch               | ?        | MSK-12C02       | [50 pcs](https://aliexpress.com/item/4000685483225.html?sku_id=12000020983019153)                                                                                               | C431541 | 2   |
| SW2          | Tactile Button            | ?        | TS-1086E        | [100 pcs](https://aliexpress.com/item/1005001846404680.html)                                                                                                                    | C455276 | 2   |
| U1           | MCU                       | ?        | MINEW MS88SF2   | [1 pcs](https://aliexpress.com/item/4000101935456.html)                                                                                                                      | ?       | 2   |
| U2           | ESD Protection IC         | SOT-23-6 | USBLC6-2SC6     | [USBLC6-2SC6 - 10 pcs](https://aliexpress.com/item/32523780535.html?sku_id=12000027513378590)                                                                                   | C558442 | 2   |
| U3           | Voltage Regulator IC      | SOT-23-5 | XC6220          | [30 pcs](https://aliexpress.com/item/4000271612572.html)                                                                                                                        | C86534  | 2   |
| U4           | Battery Charging IC       | SOT-23-5 | MCP73831        | [10 pcs](https://aliexpress.com/item/32714249253.html)                                                                                                                          | C14879  | 2   |

**806k*** You can replace it with 820k resistor, but voltage sensing circuit (for battery status) will give somewhat invalid values

**RPROG**** Value depends on your battery capacity. For 300mAh battery should be 3.3K

### Other hardware

| Name                           | Qty  | AliExpress                                                                                                                                                 |
|--------------------------------|------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| LiPo Battery 502035            |    2 | [Global - 2 pcs](https://aliexpress.com/item/1005003717206039.html?sku_id=12000026915285813) [RU - 1 pcs](https://www.chipdip.ru/product/robiton-lp502035) |
| Standoff M2x5mm                |   10 | [M2x5mm - 20 pcs](https://aliexpress.com/item/32597776358.html?sku_id=67114100494)                                                                         |
| Standoff M2x8mm                |    6 | [M2x8mm - 20 pcs](https://aliexpress.com/item/32597776358.html?sku_id=67114100497)                                                                         |
| Screw M2x4mm                   |   32 | [Black M2x4mm - 50 pcs](https://aliexpress.com/item/32806166548.html?sku_id=66702152887)                                                                   |
| Connector JST 1.25mm 2pin Male |    2 | [20 pcs](https://aliexpress.com/item/4000076660477.html)                                                                                                   |
| Silicone Bumpers               | 8-10 | [100 pcs](https://aliexpress.com/item/32912066603.html)                                                                                                    |

 ### Assembly 
Use ibom files provided in dao-chob-ble repo [dao-choc-ble](https://github.com/yumagulovrn/dao-choc-ble)  


#### Left

| Sourced | Placed | References  | Value           | Quantity |
|---------|--------|-------------|-----------------|----------|
|   [ ]   |   [ ]  | BT1         | 1.25mm 2pin 90° |     1    |
|   [ ]   |   [ ]  | C1,C2,C4,C5 | 10uF            |     4    |
|   [ ]   |   [ ]  | C3          | 1nF             |     1    |
|   [ ]   |   [ ]  | C6-C7       | 4.7uF           |     2    |
|   [ ]   |   [ ]  | D1-D22      | 1N4148WS        |     21   |
|   [ ]   |   [ ]  | D23         | 1N5819W         |     1    |
|   [ ]   |   [ ]  | D24         | RED             |     1    |
|   [ ]   |   [ ]  | D25         | BLUE            |     1    |
|   [ ]   |   [ ]  | F1          | 500mA           |     1    |
|   [ ]   |   [ ]  | J1          | ?               |     1    |
|   [ ]   |   [ ]  | K1-K22      | ?               |     21   |
|   [ ]   |   [ ]  | Q1          | AO3401A         |     1    |
|   [ ]   |   [ ]  | R1-R2       | 5.1k            |     2    |
|   [ ]   |   [ ]  | R3          | 4.7             |     1    |
|   [ ]   |   [ ]  | R4          | 1M              |     1    |
|   [ ]   |   [ ]  | R5          | **806k***       |     1    |
|   [ ]   |   [ ]  | R6-R7       | 1k              |     2    |
|   [ ]   |   [ ]  | R8          | 2M              |     1    |
|   [ ]   |   [ ]  | R9          | **RPROG****     |     1    |
|   [ ]   |   [ ]  | R10         | 100k            |     1    |
|   [ ]   |   [ ]  | SW1         | MSK-12C02       |     1    |
|   [ ]   |   [ ]  | SW2         | TS-1086E        |     1    |
|   [ ]   |   [ ]  | U1          | MINEW MS88SF2   |     1    |
|   [ ]   |   [ ]  | U2          | USBLC6-2SC6     |     1    |
|   [ ]   |   [ ]  | U3          | XC6220          |     1    |
|   [ ]   |   [ ]  | U4          | MCP73831        |     1    |


#### Rigth

| Sourced | Placed | References  | Value           | Quantity |
|---------|--------|-------------|-----------------|----------|
|   [ ]   |   [ ]  | BT1         | 1.25mm 2pin 90° |     1    |
|   [ ]   |   [ ]  | C1,C2,C4,C5 | 10uF            |     4    |
|   [ ]   |   [ ]  | C3          | 1nF             |     1    |
|   [ ]   |   [ ]  | C6-C7       | 4.7uF           |     2    |
|   [ ]   |   [ ]  | D1-D22      | 1N4148WS        |     21   |
|   [ ]   |   [ ]  | D23         | 1N5819W         |     1    |
|   [ ]   |   [ ]  | D24         | RED             |     1    |
|   [ ]   |   [ ]  | D25         | BLUE            |     1    |
|   [ ]   |   [ ]  | F1          | 500mA           |     1    |
|   [ ]   |   [ ]  | J1          | ?               |     1    |
|   [ ]   |   [ ]  | K1-K22      | ?               |     21   |
|   [ ]   |   [ ]  | Q1          | AO3401A         |     1    |
|   [ ]   |   [ ]  | R1-R2       | 5.1k            |     2    |
|   [ ]   |   [ ]  | R3          | 4.7             |     1    |
|   [ ]   |   [ ]  | R4          | 1M              |     1    |
|   [ ]   |   [ ]  | R5          | **806k***       |     1    |
|   [ ]   |   [ ]  | R6-R7       | 1k              |     2    |
|   [ ]   |   [ ]  | R8          | 2M              |     1    |
|   [ ]   |   [ ]  | R9          | **RPROG****     |     1    |
|   [ ]   |   [ ]  | R10         | 100k            |     1    |
|   [ ]   |   [ ]  | SW1         | MSK-12C02       |     1    |
|   [ ]   |   [ ]  | SW2         | TS-1086E        |     1    |
|   [ ]   |   [ ]  | U1          | MINEW MS88SF2   |     1    |
|   [ ]   |   [ ]  | U2          | USBLC6-2SC6     |     1    |
|   [ ]   |   [ ]  | U3          | XC6220          |     1    |
|   [ ]   |   [ ]  | U4          | MCP73831        |     1    |

 - [ ] Assembly board 1
 - [ ] Assembly board 2
 - [ ] Assembly FR4 case for boards
 - [ ] Flash bootloader with programator
 [Flash bootloader guide](https://github.com/Ladniy/jiran-ble-lite/wiki/Firmware)
 - [ ] Generate ZMK firmware for left and right PCB's
 - [ ] Print ZMK configuration on paper for hints
 - [ ] Place ZMK files on boards
 - [ ] Press reset btn on both boards simultaneously to read firmware and connect two sides with each other and make left visible for connecting
 - [ ] Connect to a device and test keyboard for work
