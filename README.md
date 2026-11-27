# M460L · Input Pre Amps

Ward-Beck Systems M460L, 1974|7. Wiki page: [M460L on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M460L.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 22 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 5 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 10 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 179 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 39 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [6 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1974 - M460L - OCR - M460L - P003 - 1-1.jpg](MANUALS/1974%20-%20M460L%20-%20OCR%20-%20M460L%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Sensitivities** |  |
| &nbsp;&nbsp;Line | Mic Pad: Mic: +10 dBm (ref 600 ohm source) dBm (ref _ 150 ohm source ~LO dBm (ref_ 150 ohm source) |
| **Frequency response** | +/ -0.25 dB irom Hz 20 kHz (Equalizer bypass position) |
| **Noise** | -125 dBm EIN maximum SENSITiViTY (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 25% THD from Hz 20 kHz +28 dBm less Less than at kHz +28 dBm output Source |
| **Load impedances** |  |
| &nbsp;&nbsp;Line | Mic 50_ 600 ohms, balanced/unbalanced 50 ohms balancedfunpalanced Input Impedances |
| &nbsp;&nbsp;Line | Mic OOO ohms 500 ohms Output |
| **Load impedance** | Less than 100 ohms (at outputs 8-109 8-109A amplifiers only) |
| **Load impedance** | 600 ohms balanced (at insertion point) |
| **Output level** | dBm nominal, +30 dBm maximum (at outputs 8-109 8-109A amplifiers only) |
| **Phasing** | Input and output terminals designated by numbers are phase. |
| **Power requirements** | +/ -25 volts dc, 90 MA nominal, 250 mA maximum |

## Circuit description

From [1974 - M460L - OCR - M460L - P006 - 2-2.jpg](MANUALS/1974%20-%20M460L%20-%20OCR%20-%20M460L%20-%20P006%20-%202-2.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

isolate the filter networks from each other and Additionally, they interaction between them, resulting accurate and reprevent peatable equa izing performance cut/boosT controls R21 = R22 and R23 feed an in-phase outThe the buffer amplifiers 25, 26 and 28 of-phase proportional ignal The level the signal fed the buffers is dependent respectively cut/boost control setting with maximum level occurring on the end the potentiometer and null setting the potentioeither mid-position Full clockwise for full counterclockwise potentiometer settings will result the maximum equalization +15 dB and meter -15 dB respectively The buffer amplifiers 25, 26 and Z8 are routed the outputs 4-126 printed circuit board which contains three bandpass filters corresponding each the three sections the equalizer Each bandpass filter passes only portion the signal delivered from the buffer with the center frequency and bandwidth determined by the FREQUENCY, &quot;Q&quot; and PEAK/SHELF controls. The hIGH FREQUENCY equalization continuously adjustable from 25 kHz and controlled by RI/R2 R2I determines the amount cut BOOST _ total range from -15 +15 dBm provided. With Sw1 depressed the unit wili produce high frequency SHELVING characterisic_ When SWI released, both positive negative PEAKING be obtained The control R3 effective only with can SW1 the PEAKING mode and covers O-factor range 10 _ The MId FREQUENCY equalization adjusted by RL/R5, covering from 0.4 6.4 kHz. cuT/Boost controlled by R22 frequency range R6 adjusts the O-factor _ Positive negative bell-shaped PEAKING equalization applicable in the mid-frequency range. The LoW FREQUENCY equalization operates similarly the high section R7/R8 adjusts the frequency range from 25 400 frequency Hz cut BOOST are controlled by R23 by R9 and SW12 determines the choice either SHELVING PEAKING characteristics. The three signals which leave the 4-126 filter are &quot;correction signals&quot; either in-phase 180 degrees out-of-phase with the equalizer input and bandpass limited as determined by the equalizer section and control settings These correction signals&quot; are then summed together signal by the operational amplifiers Z1, 22 with the primary (input) and 24, thus forming the equalized output signal

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRkxKaWhTbWRTVWc/view?resourcekey=0-JgBF7s3Av4GKoGJGMcnvHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRkxKaWhTbWRTVWc&resourcekey=0-JgBF7s3Av4GKoGJGMcnvHQ" width="240" alt="1974 - M460L - 460-04-023 - INPUT MODULE FRONT PANEL.jpg"></a><br><sub>1974|7 · 460-04-023 - INPUT MODULE FRONT PANEL · <a href="MECHANICAL/1974%20-%20M460L%20-%20460-04-023%20-%20INPUT%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M460L.stl`](MECHANICAL/M460L.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M460L)

- **Size:** 69.52 × 429.21 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 31 holes and cut-outs, 1 knobs (front panel: `MECHANICAL/M460L - front panel.svg`)
- the drawn panel is 0.11 wide to high, the size 0.16: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M460L.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMnhBVUxBOXpBaDA/view?resourcekey=0-YF3aWHG0yMJX1AojLYbpNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMnhBVUxBOXpBaDA&resourcekey=0-YF3aWHG0yMJX1AojLYbpNA" width="240" alt="1974 - M460L - 4-110 Pre-Amp_HP Filter Schematic.jpg"></a><br><sub>1974|7 · 4-110 Pre-Amp_HP Filter Schematic</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ2FFdWhRVHhHQlk/view?resourcekey=0-uDqSqAXCVSNWvg7a23I2RA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ2FFdWhRVHhHQlk&resourcekey=0-uDqSqAXCVSNWvg7a23I2RA" width="240" alt="1974 - M460L - 4-110-06-001 - PRE-AMP-HP FILTER COMPONENT LAYOUT.jpg"></a><br><sub>1974|7 · 4-110-06-001 - PRE-AMP-HP FILTER COMPONENT LAYOUT · <a href="SCHEMATICS/1974%20-%20M460L%20-%204-110-06-001%20-%20PRE-AMP-HP%20FILTER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWDJEcFlmeGNlc3c/view?resourcekey=0-_9-B1F8SDCGSRG2PXKAV7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWDJEcFlmeGNlc3c&resourcekey=0-_9-B1F8SDCGSRG2PXKAV7g" width="240" alt="1974 - M460L - 4-126-06-001 - EQUALIZER FILTER COMPONENT ASSEMBLY.jpg"></a><br><sub>1974|7 · 4-126-06-001 - EQUALIZER FILTER COMPONENT ASSEMBLY · <a href="SCHEMATICS/1974%20-%20M460L%20-%204-126-06-001%20-%20EQUALIZER%20FILTER%20COMPONENT%20ASSEMBLY%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFBJbHlMWE1nWG8/view?resourcekey=0-bAMWla_VX4Znqc1y90vYOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFBJbHlMWE1nWG8&resourcekey=0-bAMWla_VX4Znqc1y90vYOQ" width="240" alt="1974 - M460L - 460-01-010 - CONTROL SOLO SOLO CONTROL.jpg"></a><br><sub>1974|7 · 460-01-010 - CONTROL SOLO SOLO CONTROL · <a href="SCHEMATICS/1974%20-%20M460L%20-%20460-01-010%20-%20CONTROL%20SOLO%20SOLO%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc1VNemNCckU2enc/view?resourcekey=0-PrrvGS189zRD66yAiC1wgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc1VNemNCckU2enc&resourcekey=0-PrrvGS189zRD66yAiC1wgg" width="240" alt="1974 - M460L - Componenet layout.jpg"></a><br><sub>1974|7 · Componenet layout</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1efQYDGn_DRi8bGhMx6jCiGczix-eIyPX/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1efQYDGn_DRi8bGhMx6jCiGczix-eIyPX" width="240" alt="1974 - M460L - Input Module Schematic.jpg"></a><br><sub>1974|7 · Input Module Schematic</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOG8wQU83bUFvaVU/view?resourcekey=0-fWNB-IlX4bOcEPMbNTQzDw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOG8wQU83bUFvaVU&resourcekey=0-fWNB-IlX4bOcEPMbNTQzDw" width="240" alt="1974 - M460L - Schematic.jpg"></a><br><sub>1974|7 · Schematic</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0JNRkQtQUtHdlk/view?resourcekey=0-nl0VaqFmukt7xiiXhwynOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0JNRkQtQUtHdlk&resourcekey=0-nl0VaqFmukt7xiiXhwynOw" width="240" alt="1976 - M460L - 4-126-02-001 - EQUALIZER FILIER AMPLIFIER SCHEMATHC.jpg"></a><br><sub>1976|9 · 4-126-02-001 - EQUALIZER FILIER AMPLIFIER SCHEMATHC · <a href="SCHEMATICS/1976%20-%20M460L%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20AMPLIFIER%20SCHEMATHC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M460L - Block Diagram(1).jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWZPY3J0eE9EaDQ/view?resourcekey=0-GSKb3pEGuPcyD3-OJ1AOTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWZPY3J0eE9EaDQ&resourcekey=0-GSKb3pEGuPcyD3-OJ1AOTQ" width="240" alt="1974 - M460L - 460-04-622 - INPUT MODULE CONNECTOR REAR VIEW.jpg"></a><br><sub>1974|7 · 460-04-622 - INPUT MODULE CONNECTOR REAR VIEW · <a href="PINOUTS/1974%20-%20M460L%20-%20460-04-622%20-%20INPUT%20MODULE%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M460L - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 38 of 38 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- insert guessed: Whether PRE OUT/BOOSTER IN are normalled on the module is not shown PRE OUT (Z/22) to BOOSTER IN (W/19) is read as the preamp-to-booster patch point (insert). (M460L: 1974 - M460L - 460-04-622 - INPUT MODULE CONNECTOR REAR VIEW.jpg)

**Inserts:** PRE / BOOSTER INSERT: PRE OUT → BOOSTER IN

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | MIC IN | in | MIC IN | high |
| P1-2 | MIC SHIELD | shield | MIC IN shield | high |
| P1-3 | PA BUS | bus | PA | high |
| P1-4 | RS2 BUS | bus | RS2 | high |
| P1-5 | RS1 BUS | bus | RS1 | high |
| P1-6 | FB4 BUS | bus | FB4 | high |
| P1-7 | FB3 BUS | bus | FB3 | high |
| P1-8 | FB2 BUS | bus | FB2 | high |
| P1-9 | FB1 BUS | bus | FB1 | high |
| P1-10 | PFL BUS | bus | PFL | high |
| P1-11 | N/C | nc |  | high |
| P1-12 | SOLO BUS | bus | SOLO | high |
| P1-13 | N/C | nc |  | high |
| P1-14 | N/C | nc |  | high |
| P1-15 | N/C | nc |  | high |
| P1-16 | ATT IN SHIELD TIE | shield | ATT IN shield | high |
| P1-17 | LINE IN | in | LINE IN | high |
| P1-18 | ATT OUT SHIELD TIE | shield | ATT OUT shield | high |
| P1-19 | BOOSTER IN | insert_return | BOOSTER IN | high |
| P1-20 | CH ON OUT | control_out | CH ON OUT | high |
| P1-21 | CH ON IN | control_in | CH ON IN | high |
| P1-22 | PRE OUT | insert_send | PRE OUT | high |
| P1-A | MIC IN | in | MIC IN | high |
| P1-B | N/C | nc |  | high |
| P1-C | PA BUS | bus | PA | high |
| P1-D | RS2 BUS | bus | RS2 | high |
| P1-E | RS1 BUS | bus | RS1 | high |
| P1-F | FB4 BUS | bus | FB4 | high |
| P1-H | FB3 BUS | bus | FB3 | high |
| P1-J | FB2 BUS | bus | FB2 | high |
| P1-K | FB1 BUS | bus | FB1 | high |
| P1-L | PFL BUS | bus | PFL | high |
| P1-M | N/C | nc |  | high |
| P1-N | SOLO BUS | bus | SOLO | high |
| P1-P | N/C | nc |  | high |
| P1-R | N/C | nc |  | high |
| P1-S | N/C | nc |  | high |
| P1-T | ATT IN SHIELD TIE | shield | ATT IN shield | high |
| P1-U | LINE IN | in | LINE IN | high |
| P1-V | ATT OUT SHIELD TIE | shield | ATT OUT shield | high |
| P1-W | BOOSTER IN | insert_return | BOOSTER IN | high |
| P1-X | CH ON OUT | control_out | CH ON OUT | high |
| P1-Y | CH ON IN | control_in | CH ON IN | high |
| P1-Z | PRE OUT | insert_send | PRE OUT | high |
| P2-1 | N/C | nc |  | high |
| P2-2 | GND | ground |  | high |
| P2-3 | LEFT OUT | out | PROGRAM OUT L | high |
| P2-4 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-5 | RIGHT OUT | out | PROGRAM OUT R | high |
| P2-6 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-7 | GND | ground |  | high |
| P2-8 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-9 | N/C | nc |  | high |
| P2-10 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-11 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-12 | DIRECT OUT | out | DIRECT OUT | high |
| P2-13 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-14 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-15 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-16 | PFL CONTROL | control_in | PFL CONTROL | high |
| P2-17 | MUTE CONTROL | control_in | MUTE CONTROL | high |
| P2-18 | CONTROL COMMON | ground |  | high |
| P2-19 | -25 V | power |  | high |
| P2-20 | 25 V COMMON | ground |  | high |
| P2-21 | +25 V | power |  | high |
| P2-22 | CHASSIS | ground |  | high |
| P2-A | N/C | nc |  | high |
| P2-B | GND | ground |  | high |
| P2-C | LEFT OUT | out | PROGRAM OUT L | high |
| P2-D | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-E | RIGHT OUT | out | PROGRAM OUT R | high |
| P2-F | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-H | GND | ground |  | high |
| P2-J | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-K | N/C | nc |  | high |
| P2-L | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-M | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-N | DIRECT OUT | out | DIRECT OUT | high |
| P2-P | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-R | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-S | N/C | nc |  | high |
| P2-T | RS CONTROL | control_in | RS CONTROL | high |
| P2-U | MUTE CONTROL | control_in | MUTE CONTROL | high |
| P2-V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| P2-W | CH ON | control_out | CH ON | high |
| P2-X | CONTROL COMMON | ground |  | high |
| P2-Y | +24 V | power |  | high |
| P2-Z | CH ON LAMP | control_out | CH ON LAMP | high |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.X.18: P2-X P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.3: P2-20 P2-18 · JMP.22.21: P1-22 P1-21 · JMP.Z.Y: P1-Z P1-Y · JMP.20.19: P1-20 P1-19 · JMP.X.W: P1-X P1-W

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWmNiYnU2MkpSdEU/view?resourcekey=0-by6QAlQAofW-pbUbu3eQXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWmNiYnU2MkpSdEU&resourcekey=0-by6QAlQAofW-pbUbu3eQXQ" width="240" alt="1974 - M460L - HF EQ Curves.jpg"></a><br><sub>1974|7 · HF EQ Curves</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVktmZGFpUU5Bdnc/view?resourcekey=0-Ir6n9-QekExeUDjJ5CuYTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVktmZGFpUU5Bdnc&resourcekey=0-Ir6n9-QekExeUDjJ5CuYTg" width="240" alt="1974 - M460L - Input Module (2).pdf"></a><br><sub>1974|7 · Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHdzMkpib0hIWWM/view?resourcekey=0-p4UAUS7EDD4XwTPdNtJD-A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHdzMkpib0hIWWM&resourcekey=0-p4UAUS7EDD4XwTPdNtJD-A" width="240" alt="1974 - M460L - Input Module.pdf"></a><br><sub>1974|7 · Input Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSS1FTHBTb3p4THc/view?resourcekey=0-XM8hopMBNu9RNVXcta8YQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSS1FTHBTb3p4THc&resourcekey=0-XM8hopMBNu9RNVXcta8YQA" width="240" alt="1974 - M460L - LF EQ Curves.jpg"></a><br><sub>1974|7 · LF EQ Curves</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVZ3X1RoNENpNjA/view?resourcekey=0-t7qO9RYupea4M0WbEiXrDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVZ3X1RoNENpNjA&resourcekey=0-t7qO9RYupea4M0WbEiXrDA" width="240" alt="1974 - M460L - Mid EQ Curves.jpg"></a><br><sub>1974|7 · Mid EQ Curves</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmpoWndDTG1zdXM/view?resourcekey=0-aaZIZmC4U3ifNRmDybXqOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmpoWndDTG1zdXM&resourcekey=0-aaZIZmC4U3ifNRmDybXqOg" width="240" alt="1974 - M460L - OCR - M460L - P003 - 1-1.jpg"></a><br><sub>1974|7 · OCR - M460L - P003 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0IwNXYtY1Vlc3M/view?resourcekey=0-RijnHNMmq_sEyUHvEWA-Fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0IwNXYtY1Vlc3M&resourcekey=0-RijnHNMmq_sEyUHvEWA-Fw" width="240" alt="1974 - M460L - OCR - M460L - P004 - 1-2.jpg"></a><br><sub>1974|7 · OCR - M460L - P004 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMF9vRi1RMmx5RG8/view?resourcekey=0-9lvm6tDEPEiGkesRN-sk2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMF9vRi1RMmx5RG8&resourcekey=0-9lvm6tDEPEiGkesRN-sk2g" width="240" alt="1974 - M460L - OCR - M460L - P005 - 2-1.jpg"></a><br><sub>1974|7 · OCR - M460L - P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGp1SUJBeld0Qnc/view?resourcekey=0-3n_rLstROTLOnCjDqIb6Dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGp1SUJBeld0Qnc&resourcekey=0-3n_rLstROTLOnCjDqIb6Dg" width="240" alt="1974 - M460L - OCR - M460L - P006 - 2-2.jpg"></a><br><sub>1974|7 · OCR - M460L - P006 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGprQUJKcmRYMlk/view?resourcekey=0-p3C5PNHu6J43uJDKVRIzcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGprQUJKcmRYMlk&resourcekey=0-p3C5PNHu6J43uJDKVRIzcA" width="240" alt="1974 - M460L - OCR - M460L - P007 - 2-3.jpg"></a><br><sub>1974|7 · OCR - M460L - P007 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVlndTRwdlYzSWs/view?resourcekey=0-CpGQDzRlCoZDaHsZphnTDw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVlndTRwdlYzSWs&resourcekey=0-CpGQDzRlCoZDaHsZphnTDw" width="240" alt="1974 - M460L - OCR - M460L - P008 - 2-4.jpg"></a><br><sub>1974|7 · OCR - M460L - P008 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM19iOUtKSWJ3bjg/view?resourcekey=0-FnumC0cKeqGv_uBge3NlDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM19iOUtKSWJ3bjg&resourcekey=0-FnumC0cKeqGv_uBge3NlDA" width="240" alt="1974 - M460L - OCR - M460L - P029 - 4-110-1-1.jpg"></a><br><sub>1974|7 · OCR - M460L - P029 - 4-110-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjZVSWVRSVRYczA/view?resourcekey=0-kamRw63cppr8Cm3nWkCtZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjZVSWVRSVRYczA&resourcekey=0-kamRw63cppr8Cm3nWkCtZA" width="240" alt="1974 - M460L - OCR - M460L - P034 - 4-126 1-1.jpg"></a><br><sub>1974|7 · OCR - M460L - P034 - 4-126 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDk0NHZFd19qZWc/view?resourcekey=0-mfszEbvbm_3RIPrXi-TwtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDk0NHZFd19qZWc&resourcekey=0-mfszEbvbm_3RIPrXi-TwtA" width="240" alt="1974 - M460L - OCR - M460L - P038 - 6-1.jpg"></a><br><sub>1974|7 · OCR - M460L - P038 - 6-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOTlVVTluaXZfWVU/view?resourcekey=0-buNlXYUEphi7bExbKkiARQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOTlVVTluaXZfWVU&resourcekey=0-buNlXYUEphi7bExbKkiARQ" width="240" alt="1974 - M460L - OCR - M460L - P039 - 6-2.jpg"></a><br><sub>1974|7 · OCR - M460L - P039 - 6-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS1djQ1oxYnYzMDg/view?resourcekey=0-x2L7xBjBKB5gKh9vH0p5Ww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS1djQ1oxYnYzMDg&resourcekey=0-x2L7xBjBKB5gKh9vH0p5Ww" width="240" alt="1974 - M460L - OCR - M460L - P040 - 6-3.jpg"></a><br><sub>1974|7 · OCR - M460L - P040 - 6-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXNyOEQ1eTNFRkU/view?resourcekey=0-hHWEiRi7el2Q_m2au6srtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXNyOEQ1eTNFRkU&resourcekey=0-hHWEiRi7el2Q_m2au6srtA" width="240" alt="1974 - M460L - P030 - 4-110-2-1.jpg"></a><br><sub>1974|7 · P030 - 4-110-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa2FQVkMxTjBKT00/view?resourcekey=0-df2ihVMhst17Eni4DzECyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa2FQVkMxTjBKT00&resourcekey=0-df2ihVMhst17Eni4DzECyA" width="240" alt="1974 - M460L - Panel.jpg"></a><br><sub>1974|7 · Panel</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFdfRmZPcFJDWWs/view?resourcekey=0-dj5NgoZETnr8sYZERxVUFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFdfRmZPcFJDWWs&resourcekey=0-dj5NgoZETnr8sYZERxVUFQ" width="240" alt="1974 - M460L - WBS test procedures 0.jpeg"></a><br><sub>1974|7 · WBS test procedures 0</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0ZjcVpUcjJNUWs/view?resourcekey=0-x4sX1fd3EhZeEWeIKCnU8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0ZjcVpUcjJNUWs&resourcekey=0-x4sX1fd3EhZeEWeIKCnU8g" width="240" alt="1974 - M460L - WBS test procedures 1.jpeg"></a><br><sub>1974|7 · WBS test procedures 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUQ4MzVMd3gxUVU/view?resourcekey=0-i6Woy3AE3SI9w_HbFl2wuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUQ4MzVMd3gxUVU&resourcekey=0-i6Woy3AE3SI9w_HbFl2wuQ" width="240" alt="1974 - M460L - WBS test procedures 2.jpeg"></a><br><sub>1974|7 · WBS test procedures 2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcFJPbF80Q1pGb3c/view?resourcekey=0-VkYlTiC4UbvVP3ZBX0bxEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcFJPbF80Q1pGb3c&resourcekey=0-VkYlTiC4UbvVP3ZBX0bxEg" width="240" alt="1974 - M460L - WBS test procedures 3.jpeg"></a><br><sub>1974|7 · WBS test procedures 3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjBCOUNwSFg3M2s/view?resourcekey=0-6S0LEyIW2XhFAw2ckveHCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjBCOUNwSFg3M2s&resourcekey=0-6S0LEyIW2XhFAw2ckveHCw" width="240" alt="1974 - M460L - WBS test procedures 4.jpeg"></a><br><sub>1974|7 · WBS test procedures 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmRMWUplNnZIYWs/view?resourcekey=0-KvDfx8Auz8sADx2rLUKxPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmRMWUplNnZIYWs&resourcekey=0-KvDfx8Auz8sADx2rLUKxPA" width="240" alt="1974 - M460L - WBS test procedures 5.jpeg"></a><br><sub>1974|7 · WBS test procedures 5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlNzOGt4M1FyVW8/view?resourcekey=0-df8ssgDkn3H4zIBdcZFh_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlNzOGt4M1FyVW8&resourcekey=0-df8ssgDkn3H4zIBdcZFh_Q" width="240" alt="1974 - M460L - WBS test procedures 6.jpeg"></a><br><sub>1974|7 · WBS test procedures 6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKel9fc3JSZ2d0cmM/view?resourcekey=0-mzxhTlQt9ipOIU-LmOsjBQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKel9fc3JSZ2d0cmM&resourcekey=0-mzxhTlQt9ipOIU-LmOsjBQ" width="240" alt="1974 - M460L - WBS test procedures 7.jpeg"></a><br><sub>1974|7 · WBS test procedures 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN250Um9oR3FnRVk/view?resourcekey=0-x83qMkw6bYrFpOYHNA8e5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN250Um9oR3FnRVk&resourcekey=0-x83qMkw6bYrFpOYHNA8e5w" width="240" alt="1974 - M460L - WBS test procedures 8.jpeg"></a><br><sub>1974|7 · WBS test procedures 8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdm5mM2RkWndWMlk/view?resourcekey=0-9MIWEGt9lqSQ0cFz35W9Nw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdm5mM2RkWndWMlk&resourcekey=0-9MIWEGt9lqSQ0cFz35W9Nw" width="240" alt="1974 - M460L - WBS test procedures 9.jpeg"></a><br><sub>1974|7 · WBS test procedures 9</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1974 - M460L - 460-01-010 - CONTROL SOLO SOLO CONTROL.kicad_sch](KICAD/1974%20-%20M460L%20-%20460-01-010%20-%20CONTROL%20SOLO%20SOLO%20CONTROL.kicad_sch)
- [1974 - M460L - Input Module (2) p16.kicad_sch](KICAD/1974%20-%20M460L%20-%20Input%20Module%20(2)%20p16.kicad_sch)
- [1974 - M460L - Input Module p16.kicad_sch](KICAD/1974%20-%20M460L%20-%20Input%20Module%20p16.kicad_sch)
- [1976 - M460L - 4-126-02-001 - EQUALIZER FILIER AMPLIFIER SCHEMATHC.kicad_sch](KICAD/1976%20-%20M460L%20-%204-126-02-001%20-%20EQUALIZER%20FILIER%20AMPLIFIER%20SCHEMATHC.kicad_sch)
- [M460L.kicad_sym](KICAD/M460L.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
