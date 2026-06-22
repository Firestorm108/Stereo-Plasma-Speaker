# Stereo-Plasma-Speaker
A dual-flyback setup that can produce stereo audio through plasma arcs.

Two CRT flyback transformers are driven by a 555 oscillator based circuit, The frequency of these oscillations is modulated through an audio input, from a laptop into an RCA jack. However, by splitting the AUX output into left and right RCA, we can get stereo output.
This should produce long arcs at a 24V primary (base, should spike higher). To the grounded metal case of the power supply (inspired by Franzioli Electronis).

# Warning

Please do NOT make this under any circumstances unless you are experienced in the field. While this is lowish power, it can create insane voltages and currents and is lethal to anyone who doesn't know what they are doing. I recommened starting with a simple slayer exciter circuit or small flyback kits. I do not hold any responsibility for what you choose to do with this information.

## Main Features:

 - Integrated 12V supply
 - 555 timer interrupter
 - Plasma arc frequency modulation
 - Stereo audio output
 - IRFP460 based

## Pictures:

<img width="475" height="502" alt="Screenshot 2026-06-22 at 12 16 09 PM" src="https://github.com/user-attachments/assets/5fc0e292-0517-49e8-9726-6c94ecd284fa" />
<img width="583" height="653" alt="Screenshot 2026-06-22 at 12 15 56 PM" src="https://github.com/user-attachments/assets/87844db4-f341-42e8-830e-ce0375bcfa9c" />
<img width="644" height="700" alt="Screenshot 2026-06-22 at 12 15 41 PM" src="https://github.com/user-attachments/assets/94717f21-1345-4adc-8b47-50a65575e1f0" />

<img width="1247" height="645" alt="Screenshot 2026-06-22 at 1 17 59 PM" src="https://github.com/user-attachments/assets/0ca0ee18-2ec8-4ee9-9154-85466bb5bd53" />


# Bill of Materials (BOM)

Spreadsheet: https://docs.google.com/spreadsheets/d/1otGum9Sx6bZxCgRWKGgvt_wOPlaQsT0GzGbc5mcCbH8/edit?gid=0#gid=0

## Components

| Item | Price | Link |
|------|------:|------|
| (2) Flyback Transformer | $46 | https://www.amazon.com/TEAMWILL-Transformer-BSC24-39202-BSC26-N2137-BSC26-N2138/dp/B09P2Y9X9F/ |
| 24V 25A Power Supply | $30 | https://www.amazon.com/BOSYTRO-Upgraded-Switching-Universal-Transformers/dp/B0DPB51MB6/r |
| PCB | $33 | JLCPCB |
| Dual RCA to 3.5mm Cable | $5 | https://www.amazon.com/Headphone-Adapter-Splitter-Connects-Smartphone/dp/B09GW6JHY6 |
| AC Mains Cable | $6 | https://www.amazon.com/Standard-Electronics-Computer-Printer-Monitor/dp/B09VRLJD7J |
| 33K Resistors | $0.30 | https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CFM14JT33K0/1742191 |
| 16V 1000uF Capacitors | $1 | https://www.digikey.com/en/products/detail/rubycon/16YXJ1000MT810X16/3134825 |
| 35V 3300uF Capacitors | $9 | https://www.digikey.com/en/products/detail/nichicon/UHE1V332MHD/589341 |
| 2N3904 | $1 | https://www.digikey.com/en/products/detail/diotec-semiconductor/2N3904/13164701 |
| 100nF Capacitors | $1.62 | https://www.digikey.com/en/products/detail/vishay-beyschlag-draloric-bc-components/K104K15X7RF5TL2/286538 |
| 10K Resistors | $0.40 | https://www.digikey.com/en/products/detail/yageo/MFR-25FRF52-10K/14626 |
| NE555 | $1.12 | https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277057 |
| 1uF Film Caps | $4 | https://www.digikey.com/en/products/detail/tdk/B32672P6105K000/6160336 |
| IRFP460APBF | $13 | https://www.digikey.com/en/products/detail/vishay-siliconix/IRFP460APBF/811589 |
| IRFP460 Subs | $14 | https://www.amazon.com/PMMCON-IRFP460-MOSFET-N-Channel-Transistor/dp/B0C2W6KSV4/r |
| 7812 Regulator | $2 | https://www.digikey.com/en/products/detail/stmicroelectronics/L7812CV/585973 |
| RCJ-044 RCA Jack | $7 | https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/RCJ-044/408508 |
| TO-220 Heatsinks | $8 | https://www.amazon.com/Awxlumv-Heatsink-30mmx34mmx12mm-Regulator-Transistor/dp/B0DK372ZWT |
| Screw Terminals | $9 | https://www.amazon.com/Tugermoola-Terminal-Connector-Connectors-Terminals/dp/B0D1GSBQWF/ |

---

## Cost Summary

- Digikey Total: **$65**
- Amazon Total: **$118**
- JLCPCB: **$33**

### Total Cost: **$216**
