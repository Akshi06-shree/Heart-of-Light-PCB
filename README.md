# Heart-of-Light-PCB
My first electronics project – from hand-drawn circuit to fabricated PCB using KiCad.

# ❤️ Heart Of Light – My First PCB Project

My first electronics project, where I converted a hand-drawn circuit into a working, fabricated PCB.

## 🛠️ Components Used
- LEDs
- 220 Ω and 10 kΩ resistors
- NE555 Timer IC
- 10 µF capacitor
- CR2450 battery
- SPDT slide switch

  ## 📍 NE555 Timer IC – Pin Configuration

**IC:** LM555xN (DIP-8)

| Pin No. | Pin Name | Connection in My Circuit |
|---|---|---|
| 1 | GND | Connected to Ground (Battery −) |
| 2 | TRIG | Connected to timing capacitor junction |
| 3 | OUT | Connected to the LED and resistor network |
| 4 | RESET | Connected to +3V supply |
| 5 | CONT | Not connected |
| 6 | THRES | Connected to timing capacitor junction |
| 7 | DISCH | Connected to the junction of R17 and R18 |
| 8 | VCC | Connected to +3V supply |

### ⏱️ Timing Circuit Connections
- R17 – 10 kΩ
- R18 – 10 kΩ
- C1 – 100 µF
- Pin 2 and Pin 6 share the timing junction.
- Pin 7 connects between R17 and R18.

## 💻 Tools Used
- Tinkercad – Circuit simulation
- KiCad – Schematic and PCB design
- JLCPCB Viewer – Gerber and DFM review
- LionCircuits – PCB fabrication

## 🔄 Project Workflow
1. Hand-drawn circuit
2. Tinkercad simulation
3. Breadboard testing
4. KiCad schematic design
5. PCB layout and 3D view
6. Gerber generation and review
7. PCB fabrication and testing

## 🎯 Outcome
Successfully designed, fabricated and tested my first heart-shaped PCB.

This project helped me gain practical knowledge of electronic circuits and PCB design.

## 👩‍💻 Author
**Akshidha Shree G.R.**  
Biomedical Engineering Student

*Small project, big learning experience! ❤️*
