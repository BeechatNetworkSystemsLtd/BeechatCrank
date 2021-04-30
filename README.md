# OpenCrank
## _The last charger you'll ever need_

![BNSLTD](https://beechat.network/wp-content/uploads/2021/02/powered-by-1.png)

OpenCrank is a human-powered, open-hardware, fully-waterproof, electricity generator.
The project was born out of the need to power electronics in all off-grid scenarios. We needed a way to power our devices in all weather conditions, and making a human-powered meant that problem could be solved. When we looked for a solution, we didn't find what we were looking for, so we decided to make it, and make it open source!

## Features

- High power (3A) USB-C IPX8 output
- 18650 battery 
- Charging times:
    - 2-3 hours to charge by hand
    - 25-35 minutes with the pedal assembly
- Overcharge protection

## Parts

1. OpenCrank is composed of the main device, which we call the _Heart_. It contains the battery, the generator and all the electronics (the handle is detachable) :
![Heart](https://beechat.network/wp-content/uploads/2021/04/Crank_1.png)

2. The _Pedal Case_ is an assembly which the _Heart_ can be attached in. which dramatically speeds up the charging from 2.5 hours to 25-30 minutes. This is achieved with reduction gears to, with the same revolutions per minute, generate more electricity.
![Heart](https://beechat.network/wp-content/uploads/2021/04/Pedal_1.png)




## _Heart_ parts


| Part no. | Part name | Quantity | Description | Link | Price |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 01 | Body | 1 | Injection molded ABS/PC |
| 02 |  Lid | 1 | Injection molded ABS/PC
| 03 | Handle | 1 | Injection molded ABS/PC
| 04 | Light pipe | 1 | Transparent injection molded PC
| 05 | Motor | 1 | | [Link](https://aliexpress.com/item/4000827045633.html?spm=a2g0o.productlist.0.0.23037dfaZSxbKX&algo_pvid=1a64035c-7bcb-481b-8e93-a88d612e990f&algo_expid=1a64035c-7bcb-481b-8e93-a88d612e990f-37&btsid=0bb0623916143291425175994eaa36&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_) | $11
| 06 | Bearing | 1 | | [Link](http://manufacturer.ketanbearing.in/70745-NSKF686ADD-Bearing/) | $0.5
| 07 | PCB | 1 | |  | $6
| 08 | Battery holder | 1 | | [Link](https://aliexpress.com/item/4001063295116.html) | $0.09
| 09 | Lid O-Ring | 1 | | [Link]() | $0.95
| 10 | Bearing O-ring | 1 | | [Link](https://www.oringsandmore.com/silicone-o-rings-11-5-x-1mm-minimum-10-pcs/) | $0.08
| 10 | Adhesive | 1 | | | $8.36
| 11 | 10 mm M2 screws | 6 | | |
| 12 | 10 mm M3 screw | 1 | | |
|Total cost (excl. plastic parts and adhesive) | | | | | $18.62 



## _Heart_ PCB parts


| Part no. | Part name | Value | Device | Package | 
| ------ | ------ | ------ | ------ | ------ | 
| T1 | PNP Transistor |  | [MMBT3906](https://lcsc.com/product-detail/Transistors-NPN-PNP_Shikues-MMBT3906_C111114.html) | SOT23-BEC
| C2, C3, C5, C6, C7, C8, C9, C10, C11 |  CAP CER 22uF 0805 | 22uF |  [CL21A226MPQNNNE](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21A226MPQNNNE_C29277.html) | C0805
| D1, D2, D3, D4 | LED |  | [ORH-W46G](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_Orient-ORH-W46G_C205448.html) | CHIPLED_0603
| D5, D6, D7, D8, D9, D10, D11, D12 | Diode |  | [1N5819W](https://lcsc.com/product-detail/Schottky-Barrier-Diodes-SBD_Shandong-Jingdao-Microelectronics-1N5819W_C169540.html) | SODFL3718X115
| R4 | RES SMD 100 OHM 1/10W 0603 | 100 | [RS-03K101JT](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FH-Guangdong-Fenghua-Advanced-Tech-RS-03K101JT_C86983.html) | RES_0603
| C14 | Aluminium Electrolytic Capacitors | 100 µF | [CS1C101M-CRE54](https://lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-SMD_ST-Semtech-CS1C101M-CRE54_C97805.html) | WCAP-ASNP_6.3X5.5
| R3 | RES SMD 100K OHM 1/10W 0603 | 100k | [0603WAJ0104T5E](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAJ0104T5E_C15458.html) | RES_0603 
| R2, R5, R6, R7, R8 | RES SMD 10K OHM 1/10W 0603 | 10k | [0603WAJ0103T5E](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAJ0103T5E_C15401.html) | RES_0603
| L1 |  SMD Power Inductor | 15uH | [MJC-0603T-1R0-M](https://lcsc.com/product-detail/Power-Inductors_Me-TECH-MJC-0603T-1R0-M_C501709.html) | WE-LHMI_7050 
| R1 | RES SMD 1K OHM  1/10W 0603 | 1k | [WR06X1001FTL](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Walsin-Tech-Corp-WR06X1001FTL_C112433.html) | RES_0603
| C1 | CAP CER 1nF 0603 | 1nF | [0603B102K160CT](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Walsin-Tech-Corp-0603B102K160CT_C163169.html) | CAP_0603
| C4 | CAP CER 1nF 0603 | 1uF | [CL10A105KO8NNNC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10A105KO8NNNC_C1592.html) | CAP_0603
| J1 | TYPE C Right Angle Sealable SMT IPX8 3.1 GEN 2 Wire to Board USB |  | [2305018-2](https://www.digikey.com/en/products/detail/te-connectivity-amp-connectors/2305018-2/8680920) | TE_2305018-2
| C12, C13 | CAP CER 4.7uF 10V  0603 | 4.7uF | [CL10A475KP8NNNC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10A475KP8NNNC_C1705.html) | CAP_0603
| D13, D14 | Zener Diode | 5.6v | [MMSZ5V6CW](https://lcsc.com/product-detail/Zener-Diodes_Tak-Cheong-MMSZ5V6CW_C248743.html) | SODFL3718X115
| U2 | M6 Washer |  | [IP3005](https://lcsc.com/product-detail/Battery-Protection-ICs_INJOINIC-IP3005A_C181685.html) | HSOP8
| U1 | IP5310 |  | [IP5310](https://lcsc.com/product-detail/PMIC-Battery-Management_INJOINIC-IP5310_C191176.html) | VQFN_32
| Q1, Q2 | P-Channel MOSFET - Generic |  | [NCE2333Y](https://lcsc.com/product-detail/MOSFET_Wuxi-NCE-Power-Semiconductor-NCE2333Y_C192664.html) | SOT23




## _Pedal Case_ parts

| Part no. | Part name | Quantity | Description | Link | Price |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 01 | Sheet metal stand | 1 | Stainless steel sheet metal bend |
| 02 |  Plastic cover | 1 | Injection molded ABS plastic cover
| 03 | 20 teeth spur gear | 1 | Hardened steel-with M3 thread (Custom made)
| 04 | 30/12 teeth double spur gear | 1 | Hardened steel (Custom made)
| 05 | 48 teeth spur gear | 1 | Hardened steel (Custom made)
| 06 | Left pedal crank Arm | 1 | Hardened steel with M8 thread (Custom made) | [Link](https://www.amazon.com/Electric-Bicycle-Conversion-Aluminum-crankset/dp/B083HWCMSR/ref=sr_1_2?dchild=1&keywords=Yosoo%2Bright%2Bcrank&qid=1618046572&sr=8-2&th=1)
| 07 | Right pedal crank Arm | 1 | Standard part
| 08 | UFL003 bearing | 2 | Standard part | [Link](https://es.aliexpress.com/item/1713738795.html?spm=a2g0o.productlist.0.0.2be33d737c2av2&algo_pvid=3cf454b2-064e-440d-981a-a02dd87b7819&algo_expid=3cf454b2-064e-440d-981a-a02dd87b7819-1&btsid=0bb47a1a16180471473202376e0cfd&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
| 09 | 6mm hollow rod | 1 | with M3 internal thread(Custom made)
| 10 | M6 Washer | 2 | Standard part
| 11 | M3 Washer | 1 | Standard part
| 12 | M7 bolt | 4 | Standard part
| 13 | M3 bolt 15 mm | 3 | Standard part
| 14 | M3 bolt 8 mm | 3 | Standard part
| 15 | M7 nut | 4 | Standard part
| 16 | M3 nut | 3 | Standard part
| 17 | Pedal crank bolt | 2 | Standard part | [Link](https://www.sportwheels.ca/mtb-crank-bolt-crank-nut.html)
| 18 | Pedal | 2 | Standard part | [Link](https://www.amazon.com/BV-Universal-Bicycle-16-Inch-Spindle/dp/B01LYOB0M6/ref=sr_1_6?dchild=1&keywords=bike+pedal&qid=1618046767&sr=8-6) 



## Development

Want to contribute? Great!


Make a change in the files and create a pull request!


## License

MIT

**Open Hardware, Hell Yeah!**
