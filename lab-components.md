# Electronics Lab
```
### Tools
- Multimeter
    - Budget
        - Basic     : DT-830 (200uA and buzzer) / Mastech MAS830L / Uni-T UT33D+
        - Auto Range: Mextech D115 / Uni-T UT136A/B/ UT61D / ANENG AN8002 / Meco / HTC
    - High-End      : Extech / Fluke 101 / Metrahit / Agilent
- Breadboard        : MB102 830 tie points with power bus
- Breadboard PSU    : MB102 (2x LDO, headers, USB port, barrel jack, filters caps and switch)
- Helping hands / PCB holder
- Soldering Station : KSGER T12 / PINECIL / Mini TS100 / Hako 936 / Any chinese 936 clone
- Solder            : Flux-cored 0.6 - 1.2 mm
- Isopropyl Alchohol
- Soldering Desk Mat
- Oscilloscope
    - Budget        : OWON or Hantex USB Scope / DSO138mini (has vlow BW)
    - Entry-level   : Siglent SDS1052DL / RIGOL DS1054Z / Hantek DSO5102P / Keysight 1000X Series
    - DMM combo     : OWON HDS272S
- Isolation Transformer
- LCR Tester        : M-Tester M328 (Multifunction Tester)
- Voltmeter
- Ammeter           : Micro Systems and Controls (MS Controls) / Eltrac / Yokins
- Crimptool         : IWISS-I3220 (32 - 20 AWG) / IWISS-I2420 (24 - 20 AWG)
- Programmer
    - Universal     : TL866
    - STM           : ST-Link v2 (SWIM / SWD Debugger)
    - ATMEL AVR     : USB ASP
    - MCS8051       : Universal or USB ASP with 8051 support

### Devices
- MCB : D Curve (Suitable for electronics. B for household, C for inductive loads)
- Battery
    - Hi-Watt / 21700 / 18650 / 32700
- Solar Panel       : 80 sq.cm/W (>3W Panels) / 160 sq.cm/W (<1W Panels)
- Power supply
    - Meanwell / Morsun / Hi-Tech
- Power module
    - RIDEN 3003 / 6006 / 6018
    - Buck
        - CV
            - Low Power : MP1584 / MP2307 / XL7015
            - Hi Current: LM2596 / XL4009 / XL4005
        - CC-CV         : LM2596 (CentIoT) / XL4016 / XL4015
    - Boost
        - CV            : MT3608 / XL6009 / XL6018
    - Buck Boost
        - CV            : XL6009
        - CC-CV         : LTC3780 / LTC1871 / XL6009 / LM2596 + LM2577
    - Hi-link
- Inverter module       : Electrogreen EG002
- USB-C PD Trigger Board: ZY12PDN (https://www.youtube.com/watch?v=aIHj3qMRqqE)

### ICs
- Microcontroller       : STM8S devboard
- Timer:
    - CMOS (low power)  : TLC555 / 7555
    - TTL               : NE555 / NE556 (Dual)
- Op-amp                : MCP602 (CMOS) / LM741 / LM358 / LM148 / LM248 / LM348
- Comparator            : LM393 (dual) / LM311
- LED Driver            : TLC5940NT / MP3302 / AMC7135
- Current sensing (hall effect)
    - Inbuild sensor    : ACS712
    - External CT sensor: INA210 / INA250
- Charger
    - Charger
        - Li-Ion (4.2V) : TP4056 / TP5100
    - MPPT Charger (Solar)
        - High Current  : CN3722 / CN3767
        - Li-Ion        : CN3791 (4.2V / 2A) / CN3065 (4.2 / 0.5A)
- Regulators
    - Linear
        - Standard      : LM340 / LM140 / LM78xx / LM317 (variable)
        - High Current  : LT1085 / MIC29302 / LM1084-6 / LM2940
        - Low voltage   : AZ1084C / AMS1117 / LD1117 / LP2985 / MIC5225 / HT7333 / HT7771
    - Switching
        - High Current
            - Old Gen               : LM2596 / LM2576
            - New Gen
                - Texas Instrument  : LMR23625 / LMR33630
                - XL Semi           : XL4015 / XL4016
                - Linear Tech       : LTC3780 / LTC1871
        - Low  Current
            - Old Gen               : MC34063 / MC33063
            - New Gen
                - Monolithic power  : MP1584 / MP2307
                - Richtek           : RT8272 / RT8259
- Power Supply Monitor PC   : TL494 / KA7500
- Protection
    - eFuse                 : TPS2596xx
    - Li-ion voltage cut-off: DW01
- Schmitt-Trigger       : 74HC14N
- Shift Register
    - Parrel to Serial  : 74HC165N
- Flip-Flop             : HCF4013
- USB-C PD              : IP2368 (upto 100W buck boost converter)

### Discrete Components
- Resistor pack / set   : Blue (Metal Film) / Beige (Carbon Film)
- Potentiometers        : 1k, 4.7k, 10k, 22k, 100k (Multi-turn variants for fine control)
- Capacitor pack / set  : Ceramic / Electrolytic
- Diode
    - General Purpose
        - Low current   : IN4007 (If=1A, Vr=1000V) / IN4001 (If=1A, Vr=50V)
        - Power Diode   : 1N5408 (Vf=1V, If=3A, Vr=1000V, Pmax=.625W)
    - Small signal fast : 1N4148 (If=0.3A, Vr=75V, tr=8ns)
    - Schottky
        - Low Current   : 1N5819 (Vf=0.6V@1A / 0.34@0.1A, If=1A, Vr=40V)
        - Power Diode   : 1N5824 (Vf=0.34V@3A If=5A, Vr=30V, Ir=10mA)
- Thermistors (inrush)  : NTC-47D-15 (47 ohm -> 2 ohm 2.5A max)
- Toroidal Ferrite cores: For inductors
- Transistors           : BC547 (NPN) / BC557 (PNP)
- Darlington Transistor : TIP140 - 142 (NPN) / TIP145 - 147 (PNP)
- MOSFET:
    - Logic Level VGS   : IRLZ44N / FQP30N06L
    - Low side switch   : IRFZ44N / IRF3708 / IRLR8743 / STP55NF06
    - High side switch  : IRF5305
    - MOSFET/IGBT Driver
        - W/O Bootstrap : TC4420 / TC4428 (dual)
        - With Bootstrap: IR2110 - IR2113
- Triac                 : BT136
- Voltage Referece
    - General Purpose   : TL431A/B/C (0.5/1/2% tolerance) (Programmable shunt regulator)
    - Low Power         : LM4040 / LM4041 (Programmable) (0.1 - 1% tolerance)
    - High Precision    : REF01 / REF02 (Programmable) (0.001%)
- Metal Oxide Varistor (MOV) / IsoMOV (Hybrid GDT + MOV) low leakage made by Bourns Inc
    - EPCOS / TDK       : B72220S0431K101
                        : B722                      Product Code
                        :     20                    Disc Size
                        :       S                   Design Type: Standard (or omitted)
                        :        0                  Series Type: Standard (D: Disc)
                        :         431               43 x 10^1 = 430 VAC
                        :            K              Tolerance (J-5%, K-10%, L-15%, M-20%)
                        :             xxx           Packaging Info
- LED
    - Low voltage / high voltage
    - 5050 / 3526 LED Strip / Tape reel 85 lumen/watt

### Utilities
- Vero board / Strip board / Zero board (plated)
- Enamled wire (Motor / Transformer winding wire)
- Fuse wire
- Kapton Tape
- Cables:
    - 30 AWG wire wrapping wire (mod wire)
    - 24 AWG single core = .02" (.511 mm) dia / 25 AWG single core = (.455 mm) dia
    - 22 AWG single core hookup wire multiple colours
    - 13 AWG for AC = 1.8mm dia (2.5 sq.mm)
    - DuPont Jumper: M-F and F-F
- Connectors (Male/Female Combos)
    - 1/4" / 6.3 mm TS
    - 1/8" / 3.5 mm TS / TRS
    - XT connectors (2 Pin)
    - MT connectors (3 Pin)
    - JST connectors (a.k.a BEC)
        - XH = 0.1"
        - GH
        - VH = 0.156"
        - PH = 0.2"
    - Dupont connectors
    - Single Row Shells - Male / Female (0.1")
    - Bergstrip - Male / Female
    - 2510 Connector
    - Molex Connector
    - 9V battery connector
    - Barrel jack (5.5mm x 2.5mm dia external and internal)
    - Barrel jack to terminal connector / terminal block
    - Terminal Connectors (0.1" pitch / 0.2" pitch)
    - Crocodile clips
    - Banana Plugs
    - Binding post with wire hole and banana plug compatible
- Holders:
    - Fuse holders
    - Battery holders
    - Screw Connectors
    - IC Holder: Spring loaded SSOP socket
- Switches: SPST / SPDT / Push button / DIP
- Relays
- MCB

### Heat Shrink Tube
Limited sizes are available in small quantities for home projects. Here are 7 sizes that are often sold in kits together with 2:1 shrink ratio:
- 3/64 = 0.0470" dia: 28 to 30 AWG
- 1/16 = 0.0625" dia: 22 to 30 AWG
- 3/32 = 0.0938" dia: 16 to 26 AWG
- 3 mm = 0.1180" dia: 16 to 22 AWG
- 5 mm = 0.1980" dia: 10 to 14 AWG
- 6 mm = 0.2360" dia: 10 to 14 AWG
- 8 mm = 0.3150" dia: <10 AWG

Below is a general guideline showing the bare wire diameter without insulation to assist in choosing the right shrink tubing:
- 10 AWG: 0.1019" bare
- 12 AWG: 0.0808" bare
- 14 AWG: 0.0641" bare
- 16 AWG: 0.0508" bare
- 18 AWG: 0.0403" bare
- 20 AWG: 0.0320" bare
- 22 AWG: 0.0254" bare
- 24 AWG: 0.0201" bare
- 26 AWG: 0.0159" bare
- 28 AWG: 0.0126" bare
- 30 AWG: 0.0100" bare

### Battery Open Circuit Resting Voltages
###### During charging and discharging curves tend to shift and be allowed to rest before measuring
##### NMC
SOC(%)  Cell(V) 3 Cell(V)
100     4.2     12.6
92.5    4.15
87.5    4.1
82.5    4.05
72.5    4
65      3.92    11.76 (* Best battery life)
62.5    3.9
37.5    3.8
30      3.7     11.1
3.9 - 3.5 is a good range as charging and discharging curves are offset by 0.1 - 0.2V

##### Lithium Ferrous Phosphate
SOC(%)  Cell(V) 4 Cell(V)
100     3.6     14.4
50      3.2     12.8
        2.5     10.0 (Cut-off)
0       2.0      8.0
3.1 - 3.4 is a good range as charging and discharging curves are offset by 0.1 - 0.2V

##### Lithium Titanate
SOC(%)  Cell(V) 6 Cell(V)
100     2.8     16.8
50      2.4     14.4

##### Lead Acid - AGM
SOC(%)  Cell(V) 6 Cell(V)
100     2.1333  12.8
75      2.0833  12.5
50      2.0333  12.2
25      1.9833  11.9
20      1.9666  11.8
0       1.9333  11.6
Dead    1.5      9.0
Bouceback       10.8

##### Lead Acid - Flooded
SOC(%)  Cell(V) 6 Cell(V)
Boost   2.4     14.4
Float   2.25    13.5
Rested  2.2     13.2
100     2.1333  12.8
50      2.0000  12.0
20      1.9333  11.6
0       1.8666  11.2
Dead    1.5      9.0
Bouceback       11.2

##### Relative Capacity
Temp(C) Relative Capacity(%)
25      100%
0       80%
Source: Interwebz, Mortons on the Move, Battle Born, Battery University

### Tolerance Letter Codes
- F : +/- 1%
- G : +/- 2%
- H : +/- 3%
- I : +/- 4%
- J : +/- 5%
- K : +/-10%
- L : +/-15%
- M : +/-20%

## Sources
### Marketplaces
- Printing / Assembly
    - lioncircuits.com
    - nevonexpress.com
- Electronics
    - ktron.in
    - quartzcomponents.com
    - xcluma.com
    - electronicscomp.com
    - robu.in
    - robotbanao.com
    - electroncomponents.com
    - friendlyelec.com
    - fabtolab.com
- Electrical
    - bestomart.com
    - moglix.com

### OEM's
- Schnieder Electric
- L&T Switchgear
- ABB
- Yokins
- HPL India
- Selec
- Eltrac
- Elmeasure
- Power India

### Chinese Battery OEM
LFP:
- Winston
- CALB (China Aviation Lithium Battery)
- Gotion
- EVE
- Lishen
- FB Tech

NMC:
- BAK Tech
- Roofer
```
