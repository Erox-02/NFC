[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]

# NFC

A basic nfc card with custom antenna .

## Design 

The integrated planar antenna harvests power from the phone's magnetic field to  light up the led placed in front side pcb layer while simltaniously doing nfc connection with phone/other device . Also i have left some traces for later i2c uses .

### Back 

![](assets/l.png)

### Front

![](assets/back.png)

## How to make your own?

Check my project's build video's on forge 

[Forge](https://forge.hackclub.com/projects/2851)

you can re use my antenna and add custom footprint for others , or you can swap my name and qr with your own :D .

## Building it 

I will use pcba on jlc pcb to order it because the parts are kinda rare in india and if i order frm lcsc , it will cost me more for shipping and moq .

But if you wanna solder/rework on your own , order the parts frm given links in bom and solder the components on the designated places as cpl.xlsx says , then connect the card with your nfc enabled phone and bind a url . Or you can use a esp 32/other mpu and rewrite the eeprom with i2c , **REMINDER : USE 2.2-3v POWER SUPPLY **

## Credits 

- > [LINK]{https://neurotech-hub.github.io/KiCad-Antenna-Generator/}

- Kicad

## Author 

me , mineself Erox aka Dipanjan  

## Bom 

# BOM 

| Designator | Comment | Footprint | Qty | LCSC Part # | Manufacturer / MPN | Unit Price* | MOQ |
|---|---|---|---:|---|---|---:|---:|
| Cap1 | 180 nF | Capacitor_SMD:C_0603_1608Metric | 1 | C519440 | YAGEO CC0603KRX7R6BB184 | $0.0114 | 50 |
| D1 | LED | LED_0603_1608Metric | 1 | C19171394 | YONGYUTAI YLED0603B | $0.0055 | 100 |
| R1 | 5 kΩ | Resistor_SMD:R_0603_1608Metric | 1 | C862232 | YAGEO RT0603BRE075KL | $0.0241 | 20 |
| R2 | 5 kΩ | Resistor_SMD:R_0603_1608Metric | 1 | C862232 | YAGEO RT0603BRE075KL | $0.0241 | 20 |
| R3 | 5 kΩ | Resistor_SMD:R_0603_1608Metric | 1 | C862232 | YAGEO RT0603BRE075KL | $0.0241 | 20 |
| U1 | NT3H2111W0FHKH | XQFN-8_L1.6-W1.6-P0.50-BL_NT3H2111W0FHKH | 1 | C710403 | NXP NT3H2111W0FHKH | $0.6224 | 1 |
