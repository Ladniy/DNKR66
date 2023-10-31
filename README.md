# DNKR66

## Software

DNKR66 is powered by [ZMK firmware](https://zmk.dev/)

You can download firmware [here](https://github.com/Ladniy/dnkr66-zmk-config)

## BOM

| Name               | Qty | Package  | Value       | Aliexpress                                                   | Mark               |
| ------------------ | --- | -------- | ----------- | ------------------------------------------------------------ | ------------------ |
| Holyiot            | 1   | SMD      | YJ-18010    | [Link](https://aliexpress.com/item/32868365660.html)         | Unshilded version  | 
| Diode              | 67  | SOD-123  | 1N5819      | [Link](https://aliexpress.com/item/32849879904.html)         |                    |
| Resistor           | 1   | SMD 0603 | 2M          | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 1   | SMD 0603 | 820k        | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 1   | SMD 0603 | 3.3k        | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 1   | SMD 0603 | 100k        | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 2   | SMD 0603 | 5.1k        | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 3   | SMD 0603 | 1k          | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Resistor           | 2   | SMD 0603 | 100R        | [Link](https://aliexpress.com/item/32847135098.html)         |                    |
| Capacitor          | 1   | SMD 0603 | 0.1uF       | [Link](https://aliexpress.com/item/33015056650.html)         |                    |
| LED                | 1   | SMD 0603 | Red         | [Link](https://aliexpress.com/item/32798686869.html)         |                    |
| LED                | 1   | SMD 0603 | Blue        | [Link](https://aliexpress.com/item/32798686869.html)         |                    |
| Charger            | 1   | SOT-23-5 | MCP73831    | [Link](https://aliexpress.com/item/32714249253.html)         |                    |
| P-MOSFET           | 1   | SOT-23   | AO3407      | [Link](https://aliexpress.com/item/32491247912.html)         |                    |
| VCC Regulator      | 1   | SOT-23-5 | AP2112K     | [Link](https://aliexpress.com/item/32884059737.html)         |                    |
| Battery Protection | 1   | SOT-23-6 | DW01A       | [Link](https://aliexpress.com/item/32495092590.html)         |                    |
| Transistor         | 1   | SOT-23-6 | FS8205A     | [Link](https://aliexpress.com/item/32495092590.html)         |                    |
| USB Connector      | 1   | SMD      | 1.6mm       | [Link](https://aliexpress.com/item/32998900371.html)         |                    |
| Power Switch       | 1   | SMD      | MSK12C02    | [Link](https://aliexpress.com/item/32856542440.html)         |                    |
| Reset Switch       | 1   | SMD      | 5.2x5.2x1.5 | [Link](https://aliexpress.com/item/32989610390.html)         |                    |
| Hotswap Sockets    | 66  | SMD      | MX          | [Link](https://aliexpress.com/item/1005001774166274.html)    |                    |
| Battery Connector  | 1   | THT      | 18650       | [Link](https://aliexpress.com/item/1005001865922427.html)    |                    |
| Battery            | 1   | 18650    |             | -                                                            | Without protection |

* Instead of AP2112K VCC Regulator you can use [XC6220](https://aliexpress.ru/item/4000271612572.html). It's more expensive, but have leaks around 8uA vs 55uA at AP2112K. Using XC6220 will help save battery charge.
* Power switch also name as a PCM12, thats can help you to find them in other places.
