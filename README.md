# M497A · Summing

Ward-Beck Systems M497A, 1978|11. Wiki page: [M497A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M497A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 47 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 5 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 9 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 195 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 12 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 35 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [5 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M497A - Dual Master Module (2).pdf](MANUALS/1978%20-%20M497A%20-%20Dual%20Master%20Module%20(2).pdf) page 2 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 8 dB ±0.5 dB nominal, 18 dB ±1 dB maximum. |
| **Frequency response** | +0 -1 dB from 20 Hz to 20 kHz (tailored frequency response). |
| **Noise** | 72 dB below +8 dBm nominal output level (20 Hz to 20 kHz). |
| **Harmonic distortion** | Less than 0.25% THD, from 30 Hz to 20 kHz at +24 dBm output or less. Less tnan 0.1% at 1 kHz at +24 dBm output. |
| **Source impedances** |  |
| &nbsp;&nbsp;Summing | 30,000 ohms,. balanced. |
| &nbsp;&nbsp;External | 600 ohms maximum, balanced. |
| **Input impedances** |  |
| &nbsp;&nbsp;Summing | Less than 5 ohms. |
| &nbsp;&nbsp;External | 30,000 ohms. |
| &nbsp;&nbsp;Input level |  |
| &nbsp;&nbsp;External | o dBm nominal, +16 dBm maximum. |
| **Output impedances** | Program 600 ohms, balanced. Monitor 600 ohms, ba1anced. Mono 75,000 ohms, balanced. |
| **Load impedances** | Program 600 ohms, ba 1 anced. Monitor Bridging, balanced (5kohms minimum). Mono Summing, less than 5 ohms,balanced. |

## Circuit description

From [1978 - M497A - P004 - 2-1.jpg](MANUALS/1978%20-%20M497A%20-%20P004%20-%202-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M497 accommodates two separates igna / channels. It is9 2 A designed to receive the mixed feeds from the Teft and right e#M mixer buses of a console _ The two signa ] $ are independently Vv processed and amp] ified to standard Tine Levels _ The outputs of the M497A supply the main program outputs of the console 214 system_ Both channels operate in as similar manner The following description refers specifically to the LEFT channel. svods bediaesb 25 [900643 '€ An of Input 69996 602 benidmo? 976 2 9n643 iJod Juquo DMOM 6.1 407 The s igna 1 originating from the externa 1 mixing network enters the module at Pins 1/A and is app] ied to the summing current AM nodes of 21 and 22 _ 9df nttw RJb 8 + to Juqjvo 05 9Jubo7q 21 through 23 _ with their associated components, provide an 90+ actively balanced input a $ well a$ a balanced output _ The output operates at a nomina 7 level of 0 dBm and appears at 19404 Pins 6/F _ to to eaff2f2no? 4towjen eafiquo3sb KTaqu 2 Towod 9v1f36 O Insert 9+606 9 (bbom 90] naswisd noffel62t z9bfv0*q 80 deuotif Gqu2 91f Toftaom 00 bn5 Ep 270f2/2087T e[tsj klqqu? f(ov A balanced INSERT point is provided between Pins 6 / F and 8 /J,) permitting the insertion of an externa1 equa ]izer, filter or compressor, either using an M499 insert switcher or by direct _ wiring Level Adjustment From the INSERT point, the s igna ] is returned to the module at pins 8 /J and fed to the 8-109E output amp] ifier via an attenuator network _ R42 serves asama ster level adjustment, located at the module front panel and operating with a nomina ] 10 dB &quot;in-hand&quot; setting. Output The 8-109E output amp] ifier operates with again of 29 dB _ It recovers the Toss of the input network and provides additiona ] gain to produce a nomina ] Tine level of +8 dBm at the output of the module _ A 600 ohm resistive dividing network, having a oss of 6 dB_ is inserted between the 8-109E and the two module outputs at pins 12/N and 13/P _ Each of the two outputs has a maximum drive capability of +24 dBm into a 600 ohm Toad

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ183alI1U0tFQnc/view?resourcekey=0-GzBN-W8qISWkKbb_w0kaag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ183alI1U0tFQnc&resourcekey=0-GzBN-W8qISWkKbb_w0kaag" width="240" alt="1978 - M497A - 497-04-004 - ENG DUAL MASTER MODULE.jpg"></a><br><sub>1978|11 · 497-04-004 - ENG DUAL MASTER MODULE · <a href="MECHANICAL/1978%20-%20M497A%20-%20497-04-004%20-%20ENG%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUR3a1g2QklsLTQ/view?resourcekey=0-_Q9y66MxmCYCRsqf_Tsmkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUR3a1g2QklsLTQ&resourcekey=0-_Q9y66MxmCYCRsqf_Tsmkw" width="240" alt="1978 - M497A - 497-01-002 - DESIGNATION REVISION GEB.jpg"></a><br><sub>1978|11 · 497-01-002 - DESIGNATION REVISION GEB · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-01-002%20-%20DESIGNATION%20REVISION%20GEB%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFA3Yzc5dkd6dXc/view?resourcekey=0-_ly01216RRSoBLzh6Tx95w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFA3Yzc5dkd6dXc&resourcekey=0-_ly01216RRSoBLzh6Tx95w" width="240" alt="1978 - M497A - 497-01-002 - OHM LEFT LEVEL INSERT.jpg"></a><br><sub>1978|11 · 497-01-002 - OHM LEFT LEVEL INSERT · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-01-002%20-%20OHM%20LEFT%20LEVEL%20INSERT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1Fpb25PUXROTTQ/view?resourcekey=0-hpSsOB5_R2qSG34uJdSIAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1Fpb25PUXROTTQ&resourcekey=0-hpSsOB5_R2qSG34uJdSIAw" width="240" alt="1978 - M497A - 497-02-001 - IIK IOOP CII CIS.jpg"></a><br><sub>1978|11 · 497-02-001 - IIK IOOP CII CIS · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-02-001%20-%20IIK%20IOOP%20CII%20CIS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeVB6WEhDN0xCVVU/view?resourcekey=0-QoclWJOJwvSnslC4skganQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeVB6WEhDN0xCVVU&resourcekey=0-QoclWJOJwvSnslC4skganQ" width="240" alt="1978 - M497A - 497-02-001 - VERSION RARR ARE FRONT PANEL LEVEL CONTROLS.jpg"></a><br><sub>1978|11 · 497-02-001 - VERSION RARR ARE FRONT PANEL LEVEL CONTROLS · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-02-001%20-%20VERSION%20RARR%20ARE%20FRONT%20PANEL%20LEVEL%20CONTROLS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUlMQURad2NiblE/view?resourcekey=0-ew2OHXC_X1rtS0z-7gIrAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUlMQURad2NiblE&resourcekey=0-ew2OHXC_X1rtS0z-7gIrAQ" width="240" alt="1978 - M497A - 497-06-002 - DUAL MASTER MODULE.jpg"></a><br><sub>1978|11 · 497-06-002 - DUAL MASTER MODULE · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-06-002%20-%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa2p5ZHhnTFU1SU0/view?resourcekey=0-w2Li2DSIyxjU0FtJ_dRIwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa2p5ZHhnTFU1SU0&resourcekey=0-w2Li2DSIyxjU0FtJ_dRIwQ" width="240" alt="1978 - M497A - 497-06-002 - WET TIPGOE.jpg"></a><br><sub>1978|11 · 497-06-002 - WET TIPGOE · <a href="SCHEMATICS/1978%20-%20M497A%20-%20497-06-002%20-%20WET%20TIPGOE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTBsQU95SWdpNU0/view?resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTBsQU95SWdpNU0&resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" width="240" alt="1978 - M497A - 8-109-02-006 - REVISION NOMINAL VALUE.jpg"></a><br><sub>1978|11 · 8-109-02-006 - REVISION NOMINAL VALUE · <a href="SCHEMATICS/1978%20-%20M497A%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0JLM1gyVmVSd0k/view?resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0JLM1gyVmVSd0k&resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" width="240" alt="1978 - M497A - 8-109-02-006 - RII RIZ.jpg"></a><br><sub>1978|11 · 8-109-02-006 - RII RIZ · <a href="SCHEMATICS/1978%20-%20M497A%20-%208-109-02-006%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanRZZ1Jnd28yUHc/view?resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanRZZ1Jnd28yUHc&resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" width="240" alt="1978 - M497A - 8-109-06-006 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1978|11 · 8-109-06-006 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1978%20-%20M497A%20-%208-109-06-006%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3dMLWNLV3FBTWc/view?resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3dMLWNLV3FBTWc&resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" width="240" alt="1978 - M497A - 8-109-06-006.jpg"></a><br><sub>1978|11 · 8-109-06-006 · <a href="SCHEMATICS/1978%20-%20M497A%20-%208-109-06-006%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1xrvNp0WOHs6CsxncuCMRbW1CNLy4iHDY/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1xrvNp0WOHs6CsxncuCMRbW1CNLy4iHDY" width="240" alt="19xx - M497A - DOC - 497-02-001 - DUAL MASTER MODULE SCHEMATIC.jpg"></a><br><sub>19xx - M497A - DOC - 497-02-001 - DUAL MASTER MODULE SCHEMATIC</sub></td></tr>
</table>

Not on Google Drive yet: `1978 - 8-109-02-006 - 8-109E BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMDI3ZnlXaG9Razg/view?resourcekey=0-cY16h-VWqGam_3mvUC_lIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMDI3ZnlXaG9Razg&resourcekey=0-cY16h-VWqGam_3mvUC_lIQ" width="240" alt="1978 - M497A - 497-04-002 - CONNECTOR REAR VIEW.jpg"></a><br><sub>1978|11 · 497-04-002 - CONNECTOR REAR VIEW · <a href="PINOUTS/1978%20-%20M497A%20-%20497-04-002%20-%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M497A - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts, 21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT | other |  | medium |
| 1 | LEFT SUM IN | in | A1 + | high |
| 2 | RIGHT | other |  | medium |
| 2 | RIGHT SUM IN | in | A2 + | high |
| 3 | SHIELD | ground |  | medium |
| 4 | LEFT LINE IN | in | B1 + | high |
| 5 | RIGHT | other |  | medium |
| 5 | RIGHT LINE IN | in | B2 + | high |
| 6 | LEFT | other |  | medium |
| 7 | RIGHT | other |  | medium |
| 8 | LEFT | other |  | medium |
| 9 | RIGHT | other |  | medium |
| 10 | SHIELD | ground |  | medium |
| 11 | MONO | other |  | medium |
| 12 | LEFT | other |  | medium |
| 12 | OUT LEFT | out | A3 + | high |
| 13 | LEFT | other |  | medium |
| 14 | LEFT | other |  | medium |
| 14 | VU OUT LEFT | out | B3 + | high |
| 15 | RIGHT | other |  | medium |
| 15 | OUT RIGHT | out | A4 + | high |
| 16 | RIGHT | other |  | medium |
| 17 | RIGHT | other |  | medium |
| 17 | VU OUT RIGHT | out | B4 + | high |
| 18 | NC | nc |  | medium |
| 19 | 25V | other |  | medium |
| 19 | -25 V | power |  | high |
| 20 | 25V | other |  | medium |
| 20 | COMMON | ground |  | high |
| 21 | +25V | power |  | medium |
| 21 | +25 V | power |  | high |
| A | RIGHT OUT | out |  | medium |
| A | LEFT SUM IN | in | A1 - | high |
| B | RIGHT OUT | out |  | medium |
| B | RIGHT SUM IN | in | A2 - | high |
| D | LEFT LINE IN | in | B1 - | high |
| E | RIGHT LINE IN | in | B2 - | high |
| N | OUT LEFT | out | A3 - | high |
| R | VU OUT LEFT | out | B3 - | high |
| S | OUT RIGHT | out | A4 - | high |
| U | VU OUT RIGHT | out | B4 - | high |

**Straps:** Insert LEFT +: JMP.8.6 · Insert LEFT -: JMP.F.J · Insert Right +: JMP.7.9 · Insert Right -: JMP.H.K

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVpIYTVfaTlwLUE/view?resourcekey=0-WaJun1ULRhJ8_Rl79LEqIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVpIYTVfaTlwLUE&resourcekey=0-WaJun1ULRhJ8_Rl79LEqIg" width="240" alt="1978 - M497A - Dual Master Module (2).pdf"></a><br><sub>1978|11 · Dual Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnByejltREhtclk/view?resourcekey=0-7ogOdAxF1zn6cC4NAV2Czw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnByejltREhtclk&resourcekey=0-7ogOdAxF1zn6cC4NAV2Czw" width="240" alt="1978 - M497A - Dual Master Module.pdf"></a><br><sub>1978|11 · Dual Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3NNRnB0UGdvbEE/view?resourcekey=0-Sq3sJ9vk38k37Qw6SwT35A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3NNRnB0UGdvbEE&resourcekey=0-Sq3sJ9vk38k37Qw6SwT35A" width="240" alt="1978 - M497A - P001 - Title Page.jpg"></a><br><sub>1978|11 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2hoZVlWNURSd00/view?resourcekey=0-GJ2yP3KvI_EfLVEY8IqweQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2hoZVlWNURSd00&resourcekey=0-GJ2yP3KvI_EfLVEY8IqweQ" width="240" alt="1978 - M497A - P002 - 1-1.jpg"></a><br><sub>1978|11 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaXpoQ05vMDQ4LTQ/view?resourcekey=0-OjcWoCmHehafh0vsqILa7Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaXpoQ05vMDQ4LTQ&resourcekey=0-OjcWoCmHehafh0vsqILa7Q" width="240" alt="1978 - M497A - P003 - 1-2.jpg"></a><br><sub>1978|11 · P003 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHpjcDhyUzBqalU/view?resourcekey=0-TN5-7PcPrO3O6kpSorD90A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHpjcDhyUzBqalU&resourcekey=0-TN5-7PcPrO3O6kpSorD90A" width="240" alt="1978 - M497A - P004 - 2-1.jpg"></a><br><sub>1978|11 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMnJoX00zRUdqNEk/view?resourcekey=0-Dso0RLm7cuGJe5W3Fk2Nrw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMnJoX00zRUdqNEk&resourcekey=0-Dso0RLm7cuGJe5W3Fk2Nrw" width="240" alt="1978 - M497A - P005 - 2-2.jpg"></a><br><sub>1978|11 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHRfNm1hOGhubEE/view?resourcekey=0-dkGYMRHsm3t_uAX2wDza2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHRfNm1hOGhubEE&resourcekey=0-dkGYMRHsm3t_uAX2wDza2A" width="240" alt="1978 - M497A - P006 - 3-1.jpg"></a><br><sub>1978|11 · P006 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVBNWjJCbGtsUUE/view?resourcekey=0-bKUmlUar9y3tc-4aiJBE3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVBNWjJCbGtsUUE&resourcekey=0-bKUmlUar9y3tc-4aiJBE3w" width="240" alt="1978 - M497A - P007 - 3-2.jpg"></a><br><sub>1978|11 · P007 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHFXMk82Z2FVRXc/view?resourcekey=0-s8MZJMu6tI8bGlyz1GkHtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHFXMk82Z2FVRXc&resourcekey=0-s8MZJMu6tI8bGlyz1GkHtA" width="240" alt="1978 - M497A - P008 - 3-3.jpg"></a><br><sub>1978|11 · P008 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd1pBamNIN2pJc1U/view?resourcekey=0-_Xmd2BuzBwb7phezM0VHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd1pBamNIN2pJc1U&resourcekey=0-_Xmd2BuzBwb7phezM0VHmw" width="240" alt="1978 - M497A - P009 - 3-4.jpg"></a><br><sub>1978|11 · P009 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWcxNTgzZzdHWDQ/view?resourcekey=0-GeEKjGLG9ETbLJODwyAmcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWcxNTgzZzdHWDQ&resourcekey=0-GeEKjGLG9ETbLJODwyAmcA" width="240" alt="1978 - M497A - P010 - 3-5.jpg"></a><br><sub>1978|11 · P010 - 3-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1978 - M497A - P011 - 8-109-1-1.jpg"></a><br><sub>1978|11 · P011 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1978 - M497A - P012 - 8-109-1-2.jpg"></a><br><sub>1978|11 · P012 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1978 - M497A - P013 - 8-109-2-1.jpg"></a><br><sub>1978|11 · P013 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1978 - M497A - P014 - 8-109-2-2.jpg"></a><br><sub>1978|11 · P014 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1978 - M497A - P015 - 8-109-2-3.jpg"></a><br><sub>1978|11 · P015 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1978 - M497A - P016 - 8-109-2-4.jpg"></a><br><sub>1978|11 · P016 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1978 - M497A - P017 - 8-109-2-5.jpg"></a><br><sub>1978|11 · P017 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M497A - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M497A - DOC - R1400-R2400 - 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmxvZGRGcWFZV0E/view?resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmxvZGRGcWFZV0E&resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" width="240" alt="19xx - M497A - DOC - R1400-R2400 - 012.jpg"></a><br><sub>19xx - M497A - DOC - R1400-R2400 - 012</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - 8-109-02-006 - 8-109E BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-006%20-%208-109E%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1978 - M497A - 497-01-002 - DESIGNATION REVISION GEB.kicad_sch](KICAD/1978%20-%20M497A%20-%20497-01-002%20-%20DESIGNATION%20REVISION%20GEB.kicad_sch)
- [1978 - M497A - 497-01-002 - OHM LEFT LEVEL INSERT.kicad_sch](KICAD/1978%20-%20M497A%20-%20497-01-002%20-%20OHM%20LEFT%20LEVEL%20INSERT.kicad_sch)
- [1978 - M497A - 497-02-001 - IIK IOOP CII CIS.kicad_sch](KICAD/1978%20-%20M497A%20-%20497-02-001%20-%20IIK%20IOOP%20CII%20CIS.kicad_sch)
- [1978 - M497A - 497-02-001 - VERSION RARR ARE FRONT PANEL LEVEL CONTROLS.kicad_sch](KICAD/1978%20-%20M497A%20-%20497-02-001%20-%20VERSION%20RARR%20ARE%20FRONT%20PANEL%20LEVEL%20CONTROLS.kicad_sch)
- [1978 - M497A - 8-109-02-006 - REVISION NOMINAL VALUE.kicad_sch](KICAD/1978%20-%20M497A%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE.kicad_sch)
- [1978 - M497A - 8-109-02-006 - RII RIZ.kicad_sch](KICAD/1978%20-%20M497A%20-%208-109-02-006%20-%20RII%20RIZ.kicad_sch)
- [1978 - M497A - Dual Master Module (2) p20.kicad_sch](KICAD/1978%20-%20M497A%20-%20Dual%20Master%20Module%20(2)%20p20.kicad_sch)
- [1978 - M497A - Dual Master Module p20.kicad_sch](KICAD/1978%20-%20M497A%20-%20Dual%20Master%20Module%20p20.kicad_sch)
- [1978 - M497A - Dual Master Module p22.kicad_sch](KICAD/1978%20-%20M497A%20-%20Dual%20Master%20Module%20p22.kicad_sch)
- [1978 - M497A - Dual Master Module p27.kicad_sch](KICAD/1978%20-%20M497A%20-%20Dual%20Master%20Module%20p27.kicad_sch)
- [M497A.kicad_sym](KICAD/M497A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
