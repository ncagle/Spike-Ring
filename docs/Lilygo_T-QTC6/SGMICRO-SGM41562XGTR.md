# **SGM41562 ** **500mA Single-Cell Li-Ion Battery Charger ** **with Power Path Management **

## **GENERAL DESCRIPTION **

The SGM41562 is highly integrated, I [2] C programmable,

single-cell Li-Ion or Li-polymer battery charger with system

power path management. It is specifically designed for

portable applications requiring minimum board space and

small external components. The charging profile includes

pre-charge, constant-current and constant-voltage phases.

Several safety and protection features are included such as

built-in safe charge timer to set maximum duration of charge

and pre-charge, input voltage and current monitoring, internal

(junction) and external (battery) temperature monitoring, input

current limiting and load current limiting. SGM41562 can

charge with an input voltage range up to 6V charging range.

The SGM41562 has 3 power ports: input power port (IN),

battery port (BAT) and system or load port (SYS). The system

is powered from the input whenever it is available. Input is

typically a USB power source. If the input source is weak or

removed, power source for the system will automatically switch

to the battery. The voltage and currents from input and

battery as power sources are continuously monitored to

prevent battery damage due to excessive currents or

over-discharge.

I [2] C serial interface is used to program the device functions

and parameters or to read its status. ~~12~~ ~~read/write~~ ~~or~~ ~~read~~ ~~only~~

~~8~~ - ~~bit~~ ~~registers~~ ~~(REG00~~ ~~to~~ ~~REG0B)~~ ~~are~~ ~~accessible~~ . A watchdog

protection feature is also included. If this feature is enabled

and there is no in time read/write activity or signal from the

host, the device will reset the charging parameters to their

defaults and recycles power to the system (turn off/on) that

may reset the host.

The SGM41562 goes into voltage protection state if V IN - 6V.

The input changes are continuously monitored and a system

power recycle (SYS) may occur if the system does not

response to the input toggles.

The SGM41562 is available in a Green WLCSP-1.47×1.47-9B

package. Device functionality and protection features are

assured in the ambient temperature range from -40℃ to

+125℃. Charging parameters are guaranteed in 0℃ to +55℃.

## **FEATURES **

- **Fully Autonomous Charger for Single-Cell Li-Ion and**

**Li-Polymer Battery**

- **21V Maximum Input Voltage Rating with Over-Voltage**

**Protection**

- **±0.6% Charging Voltage Accuracy**

- **I** **[2]** **C Interface for Parameters Setting/Status Reporting**

- **Fully Integrated Power Switches**

- **No External Blocking Diode Required**

- **Built-in Robust Charge Protections Including Battery**

**Temperature Monitor and Programmable Timer**

- **Battery or PCB Over-Temperature Protection**

- **System Reset Function**

- **Built-in Battery Disconnection Function**

- **Thermal Limit Regulation on Chip**

- **Available in a Green WLCSP-1.47×1.47-9B Package**
## **APPLICATIONS **

Wearable Devices

IoT Gadgets
## **TYPICAL APPLICATION **


|USB 4.7μF<br>Port<br>1μF|Col2|Col3|System Load<br>10μF|Col5|Col6|Col7|
|---|---|---|---|---|---|---|
|USB 4.7μF<br>Port<br>1μF|USB 4.7μF<br>Port<br>1μF|IN SYS<br>Qbypass Qrvs Qswitch<br>VDD<br>SGM41562<br>nINT<br>BAT<br>SDA<br>SCL NTC<br>GND|IN SYS<br>Qbypass Qrvs Qswitch<br>VDD<br>SGM41562<br>nINT<br>BAT<br>SDA<br>SCL NTC<br>GND|IN SYS<br>Qbypass Qrvs Qswitch<br>VDD<br>SGM41562<br>nINT<br>BAT<br>SDA<br>SCL NTC<br>GND|IN SYS<br>Qbypass Qrvs Qswitch<br>VDD<br>SGM41562<br>nINT<br>BAT<br>SDA<br>SCL NTC<br>GND|IN SYS<br>Qbypass Qrvs Qswitch<br>VDD<br>SGM41562<br>nINT<br>BAT<br>SDA<br>SCL NTC<br>GND|
|Host|||4.7μF|4.7μF|||
|Host|||||||


VDD

**Figure 1. Typical Application Circuit**

**APRIL 2021 - REV.A**





Li-Ion

Battery
Pack





## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **PACKAGE/ORDERING INFORMATION **







|MODEL|PACKAGE<br>DESCRIPTION|SPECIFIED<br>TEMPERATURE<br>RANGE|ORDERING<br>NUMBER|PACKAGE<br>MARKING|PACKING<br>OPTION|
|---|---|---|---|---|---|
|SGM41562|WLCSP-1.47×1.47-9B|-40℃ to +125℃|SGM41562XG/TR|XXXXX<br>41562|Tape and Reel, 3000|


**MARKING INFORMATION**

NOTE: XXXXX = Date Code, Trace Code and Vendor Code.

**X** **X** **X** **X** **X**

Vendor Code

Trace Code

Date Code - Year

Green (RoHS & HSF): SG Micro Corp defines "Green" to mean Pb-Free (RoHS compatible) and free of halogen substances. If
you have additional comments or questions, please contact your SGMICRO representative directly.


**ABSOLUTE MAXIMUM RATINGS**

IN ....................................................................... -0.3V to 21V

SYS ........................................ -0.3V to 5.3V (5.5V for 500μs)

All Other Pins to GND .......................................... -0.3V to 6V

I INCLAMP ............................................................................ 5mA

Package Thermal Resistance

WLCSP-1.47×1.47-9B, θ JA ........................................ 95℃/W

Junction Temperature ................................................. +150℃

Storage Temperature Range ....................... -65℃ to +150℃

Lead Temperature (Soldering, 10s) ............................ +260℃

ESD Susceptibility

HBM ............................................................................. 3000V

CDM ............................................................................ 1000V

**RECOMMENDED OPERATING CONDITIONS**

Supply Voltage, V IN ......................... 4.35V to 5.5V (Charging)

I IN ...................................................................... Up to 500mA

I BAT ........................................................................ Up to 3.2A

I CHG ................................................................... Up to 456mA

V BAT_REG ............................................................ Up to 4.545V

Operating Junction Temperature Range ....... -40℃ to +125℃


**OVERSTRESS CAUTION**

Stresses beyond those listed in Absolute Maximum Ratings

may cause permanent damage to the device. Exposure to

absolute maximum rating conditions for extended periods

may affect reliability. Functional operation of the device at any

conditions beyond those indicated in the Recommended

Operating Conditions section is not implied.

**ESD SENSITIVITY CAUTION**

This integrated circuit can be damaged if ESD protections are

not considered carefully. SGMICRO recommends that all

integrated circuits be handled with appropriate precautions.

Failure to observe proper handling and installation procedures

can cause damage. ESD damage can range from subtle

performance degradation to complete device failure. Precision

integrated circuits may be more susceptible to damage

because even small parametric changes could cause the

device not to meet the published specifications.

**DISCLAIMER**

SG Micro Corp reserves the right to make any change in

circuit design, or specifications without prior notice.

APRIL2021

2

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **PIN CONFIGURATION **

**(TOP VIEW)**

**1** **2** **3**


**A**

**B**

**C**



**WLCSP-1.47×1.47-9B**
## **PIN DESCRIPTION **




|PIN|NAME|TYPE|FUNCTION|
|---|---|---|---|
|A1|IN|P|Input Power Pin. Place a minimum 2.2μF ceramic capacitor between IN pin and GND pin as close as<br>possible to these pins.|
|A2|SYS|P|System Power Supply Output. Place a ceramic capacitor between SYS pin and GND pin as close as<br>possible to these pins.|
|A3|BAT|P|Battery Positive Terminal Connection Pin. Place a ceramic capacitor between BAT pin and GND pin<br>as close as possible to the device. Connect the negative battery terminal to power GND.|
|B1|NTC|AIO|Battery Temperature Sense Input. Connect a negative temperature coefficient thermistor between this<br>pin and GND pin. NTC is usually placed in touch with battery pack. Hot-cold temperature window can be<br>programmed by a resistor divider network placed between VDD to NTC to GND pins. Charging will<br>suspend if NTC function is enabled and NTC pin voltage goes out of the V and V range.<br>HOT COLD|
|B2|nINT|DIO|Interrupt Output. The nINT pin can send a charging status and fault interrupt signal to the host. nINT<br>is also used to disconnect the system from the battery. Pull nINT pin from high to low for > t<br>RST_DGL<br>(16s default). The battery FET turns off and turns on again automatically after > t (4s default)<br>RST_DUR<br>regardless of the nINT state. Both t and t can be programmed via the I2C interface.<br>RST_DGL RST_DUR|
|B3|VDD|P|Internal Power Supply Pin. Connect a minimum 0.1μF decoupling ceramic capacitor from this pin to<br>GND. External load current on this pin should not exceed 1mA.|
|C1|SDA|DIO|I2C Bus Data. A 10kΩ pull-up to the logic-high rail should be used on SDA line.|
|C2|SCL|DI|I2C Bus Clock. A 10kΩ pull-up to the logic-high rail should be used on SCL line.|
|C3|GND|—|Ground Pin of the Device.|


NOTE:

AIO = Analog Input and Output; DI = Digital Input; DO = Digital Output; DIO = Digital Input and Output; P = Power.

APRIL2021

3

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **ELECTRICAL CHARACTERISTICS **

(T A = +25℃, V IN = 5V and V BAT = 3.5V, unless otherwise noted.)










|PARAMETER|SYMBOL|CONDITIONS|MIN|TYP|MAX|UNITS|
|---|---|---|---|---|---|---|
|Input Source and Battery Protection|Input Source and Battery Protection|Input Source and Battery Protection|Input Source and Battery Protection|Input Source and Battery Protection|Input Source and Battery Protection|Input Source and Battery Protection|
|Input Under-Voltage Lockout Threshold|V<br>IN_UVLO|Input falling|3.45|3.65|3.88|V|
|V Threshold Hysteresis<br>IN_UVLO|V<br>IN_UVLO_HYS|Input rising||105||mV|
|Input Over-Voltage Protection Threshold|V<br>IN_OVLO|Input rising threshold|5.75|6|6.27|V|
|V Threshold Hysteresis<br>IN_OVLO|V<br>IN_OVLO_HYS|||290||mV|
|Input Clamp Voltage|V<br>IN_CLAMP|Test for having 1mA clamp current|19.5|21||V|
|Input vs. Battery Voltage Headroom<br>Threshold|V<br>HDRM|Input rising vs. battery||100||mV|
|V Threshold Hysteresis<br>HDRM|V<br>HDRM_HYS|Input vs. battery voltage headroom<br>threshold hysteresis||150||mV|
|Input Power Detection Time|t<br>PWD|Wait time before sending interrupt pulse for<br>reporting input power new status|60|70|82|ms|
|nINT Output Pulse Duration|t<br>INT_PULSE|||250||μs|
|BAT Pin Input Voltage|V<br>BAT||||4.5|V|
|Battery Under-Voltage Lockout Threshold|V<br>BAT_UVLO|V falling, VBAT_UVLO[2:0] = 000<br>BAT|2.30|2.40|2.66|V|
|Battery Under-Voltage Lockout Threshold|V<br>BAT_UVLO|V falling, VBAT_UVLO[2:0] = 100<br>BAT|2.69|2.76|2.86|2.86|
|Battery Under-Voltage Lockout Threshold|V<br>BAT_UVLO|V falling, VBAT_UVLO[2:0] = 111<br>BAT|2.95|3.00|3.14|3.14|
|Battery Under-Voltage Threshold<br>Hysteresis|V<br>BAT_UVLO_HYS|V = 2.76V<br>BAT_UVLO||210||mV|
|Battery Over-Voltage Protection Threshold|V<br>BAT_OVP|Rising, higher than V<br>BAT_REG||100||mV|
|Power Path Management|Power Path Management|Power Path Management|Power Path Management|Power Path Management|Power Path Management|Power Path Management|
|Regulated System Output<br>Voltage Accuracy|V<br>SYS_REG_ACC|V = 5.5V, R = 100Ω, I = 0A,<br>IN SYS CHG<br>VSYS_REG[3:0] = 0000, V = 4.2V<br>SYS_REG|4.158|4.2|4.242|V|
|Regulated System Output<br>Voltage Accuracy|V<br>SYS_REG_ACC|V = 5.5V, R = 100Ω, I = 0A,<br>IN SYS CHG<br>VSYS_REG[3:0] = 1001, V = 4.65V<br>SYS_REG|4.603|4.65|4.696|4.696|
|Regulated System Output<br>Voltage Accuracy|V<br>SYS_REG_ACC|V = 5.5V, R = 100Ω, I = 0A,<br>IN SYS CHG<br>VSYS_REG[3:0] = 1111, V = 4.95V<br>SYS_REG|4.900|4.95|4.999|4.999|
|Input Current Limit|I<br>IN_LIM|IIN_LIM[3:0] = 0000, I = 50mA<br>IN_LIM||50||mA|
|Input Current Limit|I<br>IN_LIM|IIN_LIM[3:0] = 0011, I = 140mA<br>IN_LIM||140|||
|Input Current Limit|I<br>IN_LIM|IIN_LIM[3:0] = 1001, I = 320mA<br>IN_LIM||320|||
|Input Current Limit|I<br>IN_LIM|IIN_LIM[3:0] = 1111, I = 500mA<br>IN_LIM||500|||
|Input Minimum Voltage Regulation|V<br>IN_MIN|VIN_MIN[3:0] = 0000, V = 3.88V<br>IN_MIN|3.710|3.88|4.060|V|
|Input Minimum Voltage Regulation|V<br>IN_MIN|VIN_MIN[3:0] = 1001, V = 4.60V<br>IN_MIN|4.405|4.60|4.815|4.815|
|Input Minimum Voltage Regulation|V<br>IN_MIN|VIN_MIN[3:0] = 1111, V = 5.08V<br>IN_MIN|4.870|5.10|5.320|5.320|
|IN to SYS Switch On-Resistance|R<br>ON_Q1|V = 4.5V, I = 100mA<br>IN SYS||235||mΩ|
|Input Quiescent Current|I<br>IN_Q|V = 5.5V, EN_HIZ = 0, CEB = 0,<br>IN<br>charge enable, I = 0A, I = 0A<br>CHG SYS||220|265|µA|
|Input Quiescent Current|I<br>IN_Q|V = 5.5V, EN_HIZ = 0, CEB = 1,<br>IN<br>charge disabled||180|220|220|
|Input Suspend Current|I<br>IN_SUSP|V = 5.5V, EN_HIZ = 1, CEB = 0,<br>IN<br>charge enable||50|75|µA|


APRIL2021

4

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **ELECTRICAL CHARACTERISTICS (continued) **

(T A = +25℃, V IN = 5V and V BAT = 3.5V, unless otherwise noted.)











|PARAMETER|SYMBOL|CONDITIONS|MIN|TYP|MAX|UNITS|
|---|---|---|---|---|---|---|
|Battery Quiescent Current|I<br>BAT_Q|V = 5V, CEB = 0, I = 0A, V = 4.3V,<br>IN SYS BAT<br>charge complete||15||µA|
|Battery Quiescent Current|I<br>BAT_Q|V = GND, CEB = 1, VDD_GATE = 1,<br>IN<br>FET_DIS = 0, EN_SHIP_DGL[1:0] ≠ 11,<br>I = 0A, V = 4.35V, disable external NTC<br>SYS BAT<br>circuit driving||10|40|40|
|Battery Quiescent Current|I<br>BAT_Q|V = GND, CEB = 1, I = 0A, V = 4.35V,<br>IN SYS BAT<br>enable PCB OTP function, excluding the<br>external NTC bias.||11|||
|Battery Quiescent Current|I<br>BAT_Q|V = GND, CEB = 1, I = 0A,<br>IN SYS<br>V = 4.35V, enable PCB OTP function and<br>BAT<br>watchdog, excluding the NTC bias.||27|||
|Battery Quiescent Current|I<br>BAT_Q|V = 4.5V, IN is open or grounded, shipping<br>BAT<br>mode||0.7|1.2|1.2|
|Battery FET On-Resistance|R<br>ON_Q2|V < 2V, V = 3.5V, I = 100mA<br>IN BAT SYS||100||mΩ|
|Battery FET Discharge Current Limit|I<br>DSCHG|IDSCHG[3:0] = 0001, I = 400mA<br>DSCHG|295|400|545|mA|
|Battery FET Discharge Current Limit|I<br>DSCHG|IDSCHG[3:0] = 1001, I = 2000mA<br>DSCHG||2000|||
|Delay before Discharge Over Current Cut|t<br>DSCHG_CUT|Delay after discharge OC detection and<br>before turning switch off||64||μs|
|Delay before Retry after Cut|t<br>RETRY|Turn on retry delay after OC turn off||800||μs|
|Ideal Diode Forward Voltage in Supplement<br>Mode (BAT to SYS)|V<br>FWD|10mA discharge current||10||mV|
|Shipping Mode|Shipping Mode|Shipping Mode|Shipping Mode|Shipping Mode|Shipping Mode|Shipping Mode|
|Enter to Shipping Mode Deglitch Delay<br>Time after Programming the Shipping Mode|t<br>SMEN_DGL|FET_DIS is set from 0 to 1,<br>EN_SHIP_DGL[1:0] = 00||1||s|
|Exit Shipping Mode Delay<br>(Initiated by nINT pin or V Plug-in)<br>IN|t<br>SMEX_DGL|nINT pin is pulled low||2||s|
|Auto-Reset Mode|Auto-Reset Mode|Auto-Reset Mode|Auto-Reset Mode|Auto-Reset Mode|Auto-Reset Mode|Auto-Reset Mode|
|Reset and Power Recycle<br>by nINT Pin is Pull Down|t<br>RST_DGL|tRST_DGL[1:0] = 00||8||s|
|Reset and Power Recycle<br>by nINT Pin is Pull Down|t<br>RST_DGL|tRST_DGL[1:0] = 10||16|||
|Battery FET Off-Time Duration after Reset|t<br>RST_DUR|tRST_DUR = 0||2||s|
|Battery FET Off-Time Duration after Reset|t<br>RST_DUR|tRST_DUR = 1||4|||
|Battery Charger|Battery Charger|Battery Charger|Battery Charger|Battery Charger|Battery Charger|Battery Charger|
|Battery Charge Regulation Voltage|V<br>BAT_REG|VBAT_REG[5:0] = 000000, V = 3.6V<br>BAT_REG|3.564|3.600|3.636|V|
|Battery Charge Regulation Voltage|V<br>BAT_REG|VBAT_REG[5:0] = 101000, V = 4.2V<br>BAT_REG|4.175|4.200|4.225|4.225|
|Battery Charge Regulation Voltage|V<br>BAT_REG|VBAT_REG[5:0] = 110100, V = 4.38V<br>BAT_REG|4.354|4.380|4.406|4.406|
|Battery Charge Regulation Voltage|V<br>BAT_REG|VBAT_REG[5:0] = 111111, V = 4.545V<br>BAT_REG|4.518|4.545|4.572|4.572|
|Charge Current|I<br>CC|ICC[5:0] = 000000, I = 8mA<br>CC|4|8|10|mA|
|Charge Current|I<br>CC|ICC[5:0] = 001100, I = 96mA<br>CC|84|96|106|106|
|Charge Current|I<br>CC|ICC[5:0] = 100000, I = 264mA<br>CC|242|264|300|300|
|Charge Current|I<br>CC|ICC[5:0] = 111000, I = 456mA<br>CC|390|456|520|520|
|Junction Temperature Regulation|T<br>J_REG|I2C programmable range|60||120|℃|
|Junction Temperature Regulation|T<br>J_REG|TJ_REG[1:0] = 11, T = 120℃<br>J_REG||120|||
|Pre-Charge Current|I<br>PRE|ITERM[3:0] = 0000, I = I = 1mA<br>TERM PRE|0.35|1|1.45|mA|
|Pre-Charge Current|I<br>PRE|ITERM[3:0] = 0001, I = I = 3mA<br>TERM PRE|1.25|3|3.9|3.9|
|Pre-Charge Current|I<br>PRE|ITERM[3:0] = 0101, I = I = 11mA<br>TERM PRE|5.5|11|14.5|14.5|
|Pre-Charge Current|I<br>PRE|ITERM[3:0] = 1111, I = I = 31mA<br>TERM PRE|17|31|42|42|


APRIL2021

5

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **ELECTRICAL CHARACTERISTICS (continued) **

(T A = +25℃, V IN = 5V and V BAT = 3.5V, unless otherwise noted.)







|PARAMETER|SYMBOL|CONDITIONS|MIN|TYP|MAX|UNITS|
|---|---|---|---|---|---|---|
|Charge Termination Current Threshold|I<br>TERM|ITERM[3:0] = 0000, I = 1mA<br>TERM|0.75|1|1.15|mA|
|Charge Termination Current Threshold|I<br>TERM|ITERM[3:0] = 0001, I = 3mA<br>TERM|2|3|4|4|
|Charge Termination Current Threshold|I<br>TERM|ITERM[3:0] = 0101, I = 11mA<br>TERM|7|11|15|15|
|Charge Termination Current Threshold|I<br>TERM|ITERM[3:0] = 1111, I = 31mA<br>TERM|22|31|42|42|
|Termination Deglitch Time|t<br>TERM_DGL|||200||ms|
|Pre-Charge to Fast Charge Threshold|V<br>BAT_PRE|V Rising, VBAT_PRE = 1,<br>BAT<br>V = 3V<br>BAT_PRE|2.9|3|3.1|V|
|Pre-Charge to Fast Charge Threshold<br>Hysteresis|V<br>BAT_PRE_HYS|||90||mV|
|Battery Auto-Recharge Voltage Drop Threshold|V<br>RECH|Below V, VRECH = 0<br>BAT_REG|110|135|155|mV|
|Battery Auto-Recharge Voltage Drop Threshold|V<br>RECH|Below V, VRECH = 1<br>BAT_REG|210|240|275|275|
|Battery Auto-Recharge Deglitch Time|t<br>RECH_DGL|||200||ms|
|Thermal Protection|Thermal Protection|Thermal Protection|Thermal Protection|Thermal Protection|Thermal Protection|Thermal Protection|
|Thermal Shutdown Threshold|T<br>J_SHDN|||150||℃|
|Thermal Shutdown Hysteresis||||20||℃|
|NTC Pin Output Current|I<br>NTC|CEB = 0, NTC = 3V|-150||150|nA|
|NTC Cold Temp Rising Threshold|V<br>COLD|As percentage of V<br>DD|63|65|67|%|
|NTC Cold Temp Rising Threshold Hysteresis||||30||mV|
|NTC Hot Temp Falling Threshold|V<br>HOT|As percentage of V<br>DD|30|33|35|%|
|NTC Hot Temp Falling Threshold Hysteresis||||70||mV|
|NTC Hot Temp Falling Threshold for PCB OTP|V<br>HOT_PCB|As percentage of V<br>DD|30|32|34|%|
|NTC Hot Temp Falling Threshold<br>Hysteresis for PCB OTP||||90||mV|
|Logic IO Pin Characteristics|Logic IO Pin Characteristics|Logic IO Pin Characteristics|Logic IO Pin Characteristics|Logic IO Pin Characteristics|Logic IO Pin Characteristics|Logic IO Pin Characteristics|
|Low Logic Voltage Threshold|V<br>L||||0.4|V|
|High Logic Voltage Threshold|V<br>H||1.4|||V|
|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|I2C Interface (SDA, SCL)|
|Input Low Logic Voltage Threshold|V<br>IL||||0.4|V|
|Input High Logic Voltage Threshold|V<br>IH||1.4|||V|
|Output Low Threshold Level|V<br>OL|I = 5mA<br>SINK|||0.2|V|
|I2C Clock Frequency|f<br>SCL||||400|kHz|
|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|Clock Frequency and Watchdog Timer|
|Watchdog Timer|t<br>WDT|WATCHDOG[1:0] = 11||160||s|


APRIL2021

6

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL PERFORMANCE CHARACTERISTICS **

T A = +25℃, V IN = 5V, I IN = 500mA, I CC = 128mA and V IN_MIN = 4.6V, unless otherwise noted.

Battery Charge Curve Auto-Recharge


V IN
V SYS

V BAT

I BAT

V IN
V SYS

V BAT

I BAT

V SYS

I BAT

I IN
I SYS


V IN
V SYS

V BAT

I BAT

Time (4s/div) Time (500ms/div)

CC Charge Steady State SYS Load Transient

V IN

V SYS

I SYS

Time (2ms/div) Time (500ms/div)

Input Current Limit-Based PPM Input Voltage Regulation-Based PPM

V IN
V SYS

I BAT

I SYS

Time (4s/div) Time (2s/div)


APRIL2021

7

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL PERFORMANCE CHARACTERISTICS (continued) **

T A = +25℃, V IN = 5V, I IN = 500mA, I CC = 128mA and V IN_MIN = 4.6V, unless otherwise noted.

Power On Power Off

V IN
V SYS


V SYS

V BAT

V IN
I BAT

V IN
V SYS

V BAT

I BAT

V IN
V SYS

V BAT

I BAT


V BAT

I BAT

Time (4ms/div) Time (200μs/div)

Charge Enable Charge Disable

V IN
V SYS

V BAT

I BAT

Time (400μs/div) Time (400μs/div)

BATT Insertion BATT Removal

V IN
V SYS

V BAT

I BAT

Time (500ms/div) Time (500ms/div)


APRIL2021

8

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL PERFORMANCE CHARACTERISTICS (continued) **

T A = +25℃, V IN = 5V, I IN = 500mA, I CC = 128mA and V IN_MIN = 4.6V, unless otherwise noted.

NTC Rising NTC Falling


V SYS

V BAT

V NTC

I BAT

V NTC
V SYS

V BAT

I BAT

V SYS

V IN

V BAT

I BAT


V NTC
V SYS

V BAT

I BAT

Time (10ms/div) Time (10ms/div)

PCB_OTP at Charge Mode PCB_OTP at Discharge Mode

V NTC

V BAT
V SYS

I BAT

Time (2s/div) Time (2s/div)

V IN OVP Operation System Reset Function Operation Profile

V IN

V BAT

V SYS

Time (2s/div) Time (2s/div)


APRIL2021

9

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL PERFORMANCE CHARACTERISTICS (continued) **

T A = +25℃, V IN = 5V, I IN = 500mA, I CC = 128mA and V IN_MIN = 4.6V, unless otherwise noted.

Battery Charge Regulation Voltage vs. Temperature System Regulation Voltage vs. Temperature


|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
|||||||V<br>SYS|_REG|= 4.6|5V|5V|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)


4.5

4.4

4.3

4.2

4.1

4.0

3.9



5.0

4.9

4.8

4.7

4.6

4.5

4.4

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
|||||||V<br>B|AT_RE|= 4<br>G|.2V|.2V|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)


Battery Current under Shipping Mode vs. Temperature Pre-Charge Current vs. Temperature


3.0

2.5

2.0

1.5

1.0

0.5

0.0

-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)


4.0

3.5

3.0

2.5

2.0

1.5

1.0


|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||I<br>PR|= 3<br>E|mA|mA|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)


160

150

140

130

120

110

100


Fast Charge Current vs. Temperature Charge Termination Current vs. Temperature

4.0

3.5

3.0

2.5

2.0

1.5


1.0



|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||I<br>TERM|= 3|mA|mA|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)

APRIL2021

10

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
||||||||I =<br>CC|128|mA|mA|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL PERFORMANCE CHARACTERISTICS (continued) **

T A = +25℃, V IN = 5V, I IN = 500mA, I CC = 128mA and V IN_MIN = 4.6V, unless otherwise noted.

Battery OVP Voltage vs. Temperature Input Current Limit vs. Temperature


|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
|||||||I<br>I|N_LIM|= 500|mA|mA|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)

APRIL2021

11


4.6

4.5

4.4

4.3

4.2

4.1

4.0

4.80

4.75

4.70

4.65

4.60

4.55

4.50


|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
|||||||V<br>B|AT_RE|= 4<br>G|.2V|.2V|


-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)

Input Minimum Voltage vs. Temperature

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|
|---|---|---|---|---|---|---|---|---|---|---|
||||||||||||
||||||||||||
||||||||||||
||||||||||||
|||||||V<br>I|N_MIN|= 4.6|V|V|



-40 -25 -10 5 20 35 50 65 80 95 110

Temperature (℃)


800

700

600

500

400

300

200

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **FUNCTIONAL BLOCK DIAGRAM **
















|Col1|N SY<br>Qbypass Qrvs<br>LDO Regulator<br>gm_<br>I IN_ILIM_REF I LIM Qswitch Body<br>Switch<br>Loop Control<br>D<br>gm_<br>V IN_DPM V DPM<br>BAT<br>I<br>VSYS BATTERY<br>gm_ gm_<br>V SYSREG sys I CHRG I<br>CHRG_REF<br>BAT-20mV gm_ gm_ B<br>VSYS fwd V TERM V TERM_REF<br>NT<br>EOC I TERM_REF<br>Interrupt<br>I<br>Control BATTERY<br>ND<br>RECHG V TERM - V RECHG<br>V<br>BAT<br>A I2C Register Charger PRECOND V BAT<br>Interface<br>CL Control V PRECON_REF<br>OVP V VIN<br>Thermistor<br>C 6V<br>Monitor<br>V BAT + 150mV SLEEP nUVLO V VIN<br>V 3.65V<br>VIN|Col3|Col4|
|---|---|---|---|
|I|N|SY|S|
|||||
|VD|D|D|D|
|||||
|||B|AT|
|||B||
|nI|NT|NT|NT|
|||||
|G|ND|ND|ND|
|||||
|SD|SD|SD|SD|
|S|CL|CL|CL|
|||||
|NT|C|C|C|
|||||


**Figure 2. Functional Block Diagram**


APRIL2021

12

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION **


**Introduction**

The SGM41562 is a single-cell battery charger with power

path management function for Li-Ion and Li-polymer batteries.

The charge features include pre-charge, fast charge including

constant-current mode (CCM) and constant-voltage mode

(CVM), end-of-charge termination, auto-recharge, and a

built-in safe charge timer. The safe charge timer is used to

prevent over-charging or other issues if the host runs out of

control.

A bypass switch between IN and SYS pins, and a battery

switch between SYS and BAT pins are integrated to provide

complete power path management (PPM). The switches have

low on-resistances to minimize loss and heat. System load is

primarily powered from the input when it is available, and the

remaining input power is used to charge the battery if needed.

When the input source is weak, the load is powered partially

from the battery. This mode in which the battery provides the

power deficit, is called supplement mode. Battery will provide

the full load power if input is removed or if V IN is out of range.

For battery charging, the power to the battery is regulated by

the battery switch. To prevent faulty charge conditions, input

voltage, input current, system voltage, chip temperature and

external temperature (sensed by NTC) are continuously

monitored during charge.

Figure 3 shows the power paths and key internal blocks of the

device. The Qbypass switch regulates the voltage of the

system and the internal charge circuit. The Qrvs switch acts

as a near ideal blocking diode to prevent reverse power (or

leakage) from the load (SYS pin) back to the input (IN pin).

The Qswitch switch is responsible for battery charging

regulation and connecting or disconnecting of the battery

(BAT pin) to the system (SYS pin). The charge and discharge

circuits in the Figure 3 that are connected to the IN and BAT

pins have their own independent UVLO and power supply.

The rest of the chip is powered by either IN or SYS pin,
whichever has the higher voltage. The I/F interface (I [2] C

communication and nINT) block is active whenever any of the

power sources (IN or BAT pin) are available.


|Col1|Col2|tPWD|Col4|tPWD|Col6|tPWD|Col8|tPWD|Col10|
|---|---|---|---|---|---|---|---|---|---|
|||PWD||PWD||PWD||PWD||
|IN_OVLO_HYS||||||t<br>INI||||
|t<br>INI|t<br>INI|||||||||
|N_UVLO_HYS||||||||||
|V<br>IN<br>V<br>SYS|V<br>IN<br>V<br>SYS|||||||||
|V<br>IN<br>V<br>SYS|V<br>IN<br>V<br>SYS|||||||||
|V<br>IN<br>V<br>SYS|V<br>IN<br>V<br>SYS||tINT_PULSE|tINT_PULSE|tINT_PULSE|tINT_PULSE||||
|I I<br>IN BAT|I I<br>IN BAT|I I<br>IN BAT|I I<br>IN BAT|tINT_PULS|E|E|E|E|tINT_P|
|nINT|nINT|||||||||


**Figure 4. Input Power Detection and nINT Signaling Timings**

APRIL2021

13


The chip has a watchdog timer as a protective feature against

unexpected host malfunctions. When watchdog timer is

enabled, it must be reset by host regularly to prevent

watchdog timer overflow that results in a chip reset and power

recycle. Watchdog reset is by writing into the watchdog
register through I [2] C interface (I/F). If the watchdog is not reset

on time, the power to the host will recycle.

The power fed to the SYS pin is recycled when watchdog

times out, the host does not response to IN power input

(when watchdog is forced on) or COLD_RESET bit is set to 1,

to clear the running environment before system program

upgrade or release from locked situations.

**Input Detection**
Figure 4 shows how the input voltage status is detected and

affects the device function along with the relevant timings and

nINT output signal updates. The device continuously monitors

the input voltage at the IN node. The SYS node and charge

circuit is only started and connected to the input when for a

duration of t INI, V IN is within its normal range (above V IN_UVLO
and below V IN_OVLO ). Qbypass and Qrvs switches will turn off

as soon as an input UVLO or OVLO is detected.

As shown in Figure 4 any input state is considered stable if it

continuously stays in the same condition for a duration of t PWD

after which the device sends out a negative pulse to the nINT

pin with a pulse width of t INT_PULSE to inform the host about the

input state change.

The watchdog timer WATCHDOG[1:0] register is set to 01

once the valid input is detected and when an INT pulse is

asserted, which resumes its original setting when any writing

to this device occurs. If the host does not clear the watchdog,

power to the host is recycled for reset when watchdog runs

time out.





V IN_OVLO

V IN_UVLO






|IN|Col2|Qbypass Qrvs<br>UVLO<br>Charge<br>Qswitch<br>Circuit<br>UVLO<br>I/F<br>Discharge<br>Interface<br>Circuit|Col4|SYS|
|---|---|---|---|---|
|IN|||||
|er Input|er Input|||System L<br>BAT|
|er Input|er Input|UVLO<br>Charge<br>Circuit|UVLO<br>Charge<br>Circuit|UVLO<br>Charge<br>Circuit|
|er Input|er Input|I/F<br>Interface|I/F<br>Interface|I/F<br>Interface|


**Figure 3. Power Path Management Structure**

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **


**Power Path Management**
When the input voltage is normal and have enough headroom

for powering the system (V IN - V IN_UVLO and V IN - V SYS 
V HDRM ), the input power path will conduct and the device

starts to power the system from input by setting the system

voltage to V SYS_REG . V SYS_REG is selected by programming

VSYS_REG[3:0] register, the lower 4 bits of REG07 (also

called system voltage register or VSYS_REG[3:0] register).

However, the actual system voltage (V SYS ) can be affected by

the input voltage level, input current limit and battery voltage.

I [2] C commands can directly control the power paths. Input

path will be disconnected (high-impedance) by turning off

Qbypass switch if the EN_HIZ bit is set to 1. If the battery is

getting charge and Qswitch switch is on, it can also be

disconnected by setting charge enable bit, set the CEB bit to

1 (turn off Qswitch switch in charge direction). The power path

control bits are explained in Table 1. When these bits are

clear, they have no effect.

**Table 1. Switch Control by I** **[2]** **C Interface**

|FETs|EN_HIZ = 1|CEB = 1|
|---|---|---|
|Qbypass|Off|X|
|Qswitch (Charging)|X|Off|
|Qswitch (Discharging)|X|X|



NOTE: X = Don't Care.

**Battery Charge Profile**
Figure 5 shows the battery charge profile used in this device.

The charge phases are explained below. Depending on the
I [2] C settings and the battery state of charge (SOC), some or

all of the phases may be skipped or used to finish a complete

charge cycle as explained below:


***Pre-Charge*** : If the battery voltage is less than the pre-charge

threshold (V BAT_PRE ), the battery is charged with the small

pre-charge current (I PRE ). The pre-charge current value is the

same as the termination current (I TERM ) that is programmed

via bit D[3:0] of the REG03, also called ITERM[3:0].

***Constant-Current Charge*** : When battery voltage is higher

than V BAT_PRE, and less than V BAT_REG, it will be charged with a

constant current. The constant-current value is determined by

bit D[5:0] of the REG02 that is called ICC[5:0] and a single

scaling bit that if set, multiplies it by ¼. This bit is used for

finer CC adjustment (CC_FINE bit in REG0A).

***Constant-Voltage Charge*** *:* When the battery voltage reaches

to the V BAT_REG, the voltage is kept constant and the charge
current drown by battery will start to fall. The V BAT_REG value is

determined by bit D[7:2] of the REG04 that is also called

VBAT_REG[5:0].

***Charge Termination*** *:* A charge termination is recognized

when the charge current drops to a small value represented by

I TERM . If the termination detection is enabled by setting the

EN_TERM bit in REG05 D[4] to 1, then if the charge current

(I CHG ) stays equal or lower than I TERM for a period of t TERM_DGL

(termination deglitching time) the charge cycle is considered

complete and charging current will be turned off and drop to

zero. With no termination, the charge current will continue to

drop. Note that a charge cycle is also considered complete and

charging will be turned off, if the safe timer function runs out of

time provided that the safe timer function is already enabled

by setting EN_TIMER bit in REG05 D[3] to 1.


V BAT_REG

I CC

V BAT_REG                                     - V RECH

V BAT_PRE

|Col1|Col2|Col3|Col4|Col5|Col6|Col7|
|---|---|---|---|---|---|---|
||||||||
||||||||
|Charge<br>Current|Battery<br>Voltage||||||
||||I = I<br>TERM PRE||||
||||||||
|Pre-Charge|CC Charge|CV Charge|Termination|Discharge|Auto-Rec|Auto-Rec|



**Figure 5. Battery Charge Profile**


APRIL2021

14

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **


The charge status is updated to "charge complete" once the

termination condition is detected. The charge current will be

terminated when termination conditions are met and if the

TERM_TMR bit is set to 0 (REG05 D[0] = 0); The charge will not

terminate and current keeps decreasing if TERM_TMR bit is 1.

During the whole charging process, the actual charge current

may fall below the set values due to the other regulations or

controls such as dynamic power management (DPM)

regulation caused by insufficient input voltage or current or

due to thermal regulation. In thermal regulation the device

reduces the power path currents to keep junction temperature

below the programmed limit.

A new charge cycle starts when one of the following

conditions occurs:

 The input power recycles (input on/off).
 Battery charging is enabled by I [2] C command.

 Auto-recharge kicks in due to battery charge state.

If all the following conditions are satisfied:

 No NTC thermistor temperature fault.

 No safety (charge) timer fault.

 No battery over voltage event.

 The Qswitch switch is not forced to turn off (e.g. CEB = 1).

**Battery Over-Voltage Protection**
SGM41562 has a built-in battery over-voltage protection limit.

A battery over-voltage event is detected when battery voltage

is higher than V BAT_OVP + V BAT_REG . When this event occurs,

the charging is immediately suspended and a fault is asserted.

The discharging path will be turned on if battery over-voltage

condition does not clear and continues.


**Input Current and Input Voltage Based**
**Power Management**
Usually the input source (typically USB) is not strong enough

for all system power demands and a power management

scheme is needed to keep the system voltage in desired level

without over loading the source. Figure 6 shows the power

management profile and explains how it is implemented in

SGM41562 including the battery assist operation (supplement)

when input source is not able to provide required power.

The input current is continuously monitored to make sure the

input source maximum current limit specification is met. The
total input current limit is programmable by I [2] C and is used to

prevent over loading of the input source.

If the input source is weak and the programmed input current

limit is higher than the effective capability of the source (like in

a dynamic loading condition) the back-up power management

will come in effect to prevent over loading of the input source.

The back-up power management is based on limiting the

input voltage drop to V IN_MIN value (programmable). The

voltage based dynamic power management (DPM) will

regulate the input voltage to V IN_MIN when the load is higher

than the input current capacity. If input current and voltage

limit are both reached, then the Qbypass switch (between IN

and SYS pins) will regulate and limit the total power taken

from the input. With the power limiting, if the system voltage

drops to the minimum value of (V SYS_REG - 90mV) or the input

voltage falls below (V IN - 160mV), the device will finally

reduce the charge current to prevent further voltage drops.

The programmed V IN_MIN must be at least 250mV higher than
V BAT_REG to assure stable operation of the regulator.

APRIL2021

15

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **





~~I~~ ~~DSCHG~~ ~~×~~ ~~R~~ ~~ON~~ _ ~~BATFET~~

|I<br>SYS|Col2|Col3|Col4|Col5|Col6|Col7|Col8|Col9|Col10|Col11|Col12|
|---|---|---|---|---|---|---|---|---|---|---|---|
|I<br>SYS||||||||||||
|I<br>SYS||||||||||||
|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|I<br>IN|
|I<br>IN|I<br>IN|||MIN(V - 90<br>SYS_REG|mV, V -<br>IN|mV, V -<br>IN|160|160|mV)|10mV||
|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|V<br>SYS|
|V<br>BAT||||||||||||
|V<br>BAT||||||||||||
|I<br>BAT||||30|mV||||||I ×<br>DSCHG|
|I<br>BAT||||30|mV|||||||
|I<br>BAT||||30|mV|||||||
|I<br>BAT||||30|mV|||||||
|Charging<br>0<br>Discharging||||||||||||
|Charging<br>0<br>Discharging||||||||||||
|Charging<br>0<br>Discharging||||||||||||
|Charging<br>0<br>Discharging||||||||||||
|Charging<br>0<br>Discharging||||||||||||


**Figure 6. Dynamic Power Management and Battery Supplement Operation Profile**


**Battery Supplement Mode**
As mentioned above, the DPM will reduce the charge current

to keep the input current or voltage in regulation when source

power is not sufficient for system demand. If the charge

current is reduced to zero but still due to heavy system load

the input source is overloaded and V SYS continues to drop,

then the battery will supply the deficit to assist the input

source. This mode is called battery supplement mode in

which the battery provides I DSCHG as supplement current to

the load. This mode starts when the system drop reaches to

30mV below the battery voltage. In this mode the Qswitch

switch acts as a near ideal diode from battery to the system.

The Qswitch switch is controlled to regulate and maintain the

V BAT - V SYS drop to a fixed 10mV value when I DSCHG ×

R ON_BATFET is less than 10mV. If I DSCHG × R ON_BATFET is larger

than 10mV, the Qswitch switch is fully turned on to pass

battery voltage to the system with minimum drop.

In the battery supplement mode the ideal diode mode will be

disabled as soon as the system load decreases and V SYS

exceeds the V BAT + 20mV value.

When V IN source is not available, the device operates in

discharge mode (battery power) in which the Qswitch switch

is always fully on to reduce the losses.


**Battery Regulation Voltage**
The battery voltage for the constant-voltage regulation phase

(CV) is represented by V BAT_REG .

**Thermal Regulation and Shutdown**
SGM41562 continuously monitors its internal junction

temperature to avoid junction overheating while keeping the

power delivery at its maximum. When the internal junction

temperature reaches its programmable limit (T J_REG ), the

device starts to reduce the charge current to prevent higher

power dissipation. The thermal regulation limit is

programmable to help adjusting the design for the thermal

requirements in different applications. 4 different junction

temperature regulation thresholds can be chosen by

programming the TJ_REG[1:0] register.

The device fixed thermal shutdown limit (T J_SHDN ) is slightly
higher than the highest programmable T J_REG . If T J rises

above this limit, both Qbypass and Qswitch switches will turn

off.

APRIL2021

16

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **


**NTC Function and VDD Gating**
The NTC pin is provided to sense the battery temperature

using an NTC thermistor. Thermistors are usually included in

the rechargeable battery packs to ensure safe operation by

monitoring the battery temperature and making sure it is

between hot and cold limits. To adjust the temperature limits

for the device, two resistors (R T1 and R T2 in Figure 13) should

be connected to NTC pin as a divider between VDD and GND

pins. The thermistor itself is connected between NTC pin and

GND. The voltage on the NTC pin is determined by all three

resistors. This resistor divider along with the hot and cold limit

voltages defined in the EC table determines the hot-cold

operating window. Note that due to the negative temperature

coefficient of NTC, when its voltage drops below V HOT, it

means the battery temperature is exceeding the hot limit. The

NTC protection function can be disabled by clearing the

EN_NTC bit to 0. The default settings for NTC function are

the PCB OTP levels specified in EC table that can be change
by I [2] C as explained in Table 2.

**Table 2. NTC Function Selection**

|I2C Control|Col2|Function|
|---|---|---|
|EN_NTC|EN_PCB OTP|EN_PCB OTP|
|0|don’t care|Disable|
|1|1|NTC|
|1|0|PCB OTP|



NTC function only works in charge mode. When NTC pin

voltage falls out of the hot-cold window it means that the

temperature is outside the safe operating range and results in

a pause in charging and sets the fault bits. Charging will

resume when the temperature falls back into the safe range.

If DIS_VDD bit is disabled and V IN is removed, V DD power

turns off and becomes high-impedance leaving only R T2 in

parallel with the NTC thermistor. If DIS_VDD bit is enabled,

V DD remains active. V DD uses battery power if V IN is removed.

With PCB OTP selected, if the NTC pin voltage is lower than

the NTC hot threshold, Qbypass and Qswitch switches will

turn off. The PCB OTP fault also will set the NTC_FAULT

status bit to 1. The operation will resume when the NTC pin

voltage goes back above the NTC hot threshold.

**Safety Timer**
Using an internal safety timer, SGM41562 is capable to limit

the maximum duration of the pre-charge and charge periods

to avoid extended charging cycles that may happen due to

abnormal battery conditions. This protection can be disabled
by I [2] C. The safety timer starts counting if one of the following

occurs:


 A new charge cycle is started.

 Write in REG01 D[3] bit: from 1 to 0 (charge enable)

 Write in REG05 D[3] bit: from 0 to 1 (safety timer enable)

 Write in REG02 D[7] bit: from 0 to 1 (software reset)

 Write in REG0A D[4] bit: from 0 to 1 (software power recycle)

The safety time limit is 1 hour for pre-charge condition in

which the battery voltage stays lower than V BAT_PRE and

cannot go higher. For the charge phase the time limit is
programmable through I [2] C and the safety timer starts

counting when the battery enters in constant-current charge

mode or constant-voltage charge mode.

**Host Mode and Default Mode**

SGM41562 can operate in either default mode (with default

parameters) or host mode (parameters programmed by host).

It will go to the default mode if one of the following occurs:

 Input refresh with no battery connected.

 Re-insert battery with no input source connected.

 Device registers reset by writing 1 to REG_RST bit.

 Watchdog timer expiry.

Upon a power on reset, the device starts in default mode and

in the same state as if watchdog timer expiration has

occurred. In this mode all registers take their default values,

including EN_HIZ = 0 and CEB = 1, that means the input

power path is enabled and device is set to battery discharge

mode. Note that by default the battery will not be charged

after a reset.

When the device is in the host mode, watchdog function can

be activated and works in both charge and discharge modes

(Watchdog timer is independent of the charge safety timer).

Watchdog timer can be enabled by programming a non-zero

expiry time in its register, that is WATCHDOG[1:0] ≠ 00. If

watchdog timer is enabled, it must be reset regularly before it

runs out of time by writing 1 to WD_RST bit in REG02.

Otherwise the watchdog timer will expire and results in a

power recycle to the system. Therefore, resetting the

watchdog timer by host must happen in the intervals shorter

than watchdog time limit. The power recycle is performed by

turning off Qswitch and Qbypass for a duration of t RST_DUR and

then turning them on again. After watchdog timer expiration,

all registers will reset to their default values and the device

goes to the default mode.

To reduce the quiescent current during discharge mode, the

watchdog timer can be turned off by setting the

EN_WD_DISCHG bit to 0. If the WATCHDOG[1:0] is set to 00,

the watchdog timer is disabled under charge and discharge

modes independent of the EN_WD_DISCHG bit value.

APRIL2021

17

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **


**Battery Discharge Function**
If the battery is connected (V BAT is above the V BAT_UVLO

threshold) and the input source is missing, the Qswitch turns

fully on. The low on resistance of the Qswitch minimizes the

conduction loss during discharge. The quiescent current of

the device is as low as 11μA in this mode. By setting REG0A

D[3] bit to 1, the Qswitch will stay on even if the rest of the

internal blocks are turned off, to reduce the device quiescent

current to less than 1.2μA. The low on-resistance and low

quiescent current of the device extend the run time.

**Over-Discharge Current Protection**
The over-discharge current protection is effective in discharge

mode and supplement mode. If the I BAT exceeds discharge

current limit value programmed in the REG03 D[7:4], the

Qswitch turns off after a wait delay (t DSCHG_CUT ) and then

resumes conducting after a retry delay time (t RETRY ). Qswitch

turns off instantly if the discharge current exceeds 3.7A value.

When the battery voltage falls below the V BAT_UVLO limit that is

programmed in the REG01 D[2:0], the Qswitch turns off to

prevent over discharging the battery.

If SWITCH_MODE bit (REG0A D[3]) is set to 1, the Qswitch is

forced to remain on like a simple switch and the over
discharge is ignored during battery discharge. This bit will

reset if power is re-applied to the input. It will also reset if the

battery is connected or disconnected while power is applied

to the input.

**System Short Circuit Protection**
If a short circuit (to GND) occurs on the load connected to

SYS pin, the Qswitch disconnects the BAT to SYS path and

the Qbypass limits the current flowing in the IN to SYS path. If

the short circuit persists, the die temperature goes high and

causes a thermal shutdown.


**Interrupt to Host (nINT Pin)**
The nINT output signal is provided to alert the host on power

events. SGM41562 sends out a negative pulse (width =

t INT_PULSE ) to nINT if any of the following events occurs:

 A good input source is detected (UVLO < V IN < OVLO).

 UVLO or OVLO is detected (input).

 Charge completed.

 A charging status change.

 A fault record in REG09 occurs (input fault, thermal fault,

safety timer fault, battery OVP fault or NTC fault).

 Watchdog expiration (WTD_FAULT in REG08 D[7]).

When one of the mentioned faults occurs, the relevant fault

bit will latch in the register except for NTC fault bit that always

reports the current status of the thermistor. A fault status bit is

unlatched if the device quits that fault state. It will reset to 0

after the host reads the register if the bit is unlatched.

The assertion of nINT signal pulse can be masked for some

of the events listed above when the corresponding mask

control bits are set in REG06 D[4:0]. If a mask bit is set, and

the event occurs, the nINT signals stays high.

The nINT pin is also used as an input to initiate a power

recycle on the SYS output for example when a turn off/turn on

is needed on the system when battery is not removable. This

input is also used to exit the shipping mode that keeps the

battery disconnected. The nINT pin is weakly pulled up

internally to an unregulated low voltage that is not high

enough for most logic devices. The weak and low voltage

pull-up is used to avoid unexpected battery drain or leakage

when the product is in shipping or is stocked for prolonged

times (called shipping mode). The pull-up can be overdriven

externally to higher appropriate logic voltages when it is in

operation.

APRIL2021

18

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **DETAILED DESCRIPTION (continued) **


**Battery Disconnection Function**
When the battery is not removable, it’s essential to disconnect

the battery from the system to allow system power recycling

or to put that in the shipping mode. It is performed by forcing

the Qswitch to remain off by setting FET_DIS bit to 1. Table 3

explains how the SGM41562 can be programmed in shipping

mode (or to do a power recycle on SYS) and how to exit the

shipping mode. To exit shipping mode either the input power

should be applied to IN port, or a low voltage (ground) should

be applied to nINT pin for a short time (for example by holding

a push bottom).

**Table 3. Shipping Mode Control**




|Items|Enter Shipping Mode|Exit Shipping Mode|Col4|
|---|---|---|---|
|Items|FET_DIS = 1|nINT Pin<br>H to L for 2s|V Plug-in<br>IN|
|Qbypass|don’t care|don’t care|On|
|Qswitch<br>(Charging)|Off|On|On (64ms Later)|
|Qswitch<br>(Discharging)|Off|On|On (64ms Later)|


The FET_DIS bit is used for battery disconnection control. If

this bit is set to 1, the device enters shipping mode after a

delay time, which can be programmed by EN_SHIP_DGL[1:0].

After the delay the Qswitch turns off and the FET_DIS bit

resets to 0. The device wakes up from shipping mode by

pulling down nINT pin or detecting an acceptable voltage on

the IN pin. The device exits from shipping mode 2 seconds

after pulling nINT pin down or 64ms after detecting an

acceptable V IN . For the application of nINT pulled down to a

low voltage in the shipping mode `,` EN_SHIP_DGL[1:0] must

keep default value.


System power can be recycled by turning off the Qswitch and

Qbypass if nINT pin is pulled low for a duration of more than

t RST_DGL . It is the time delay to avoid noise and glitches or to

hold a push bottom. The t RST_DGL time is programmed by

tRST_DGL[1:0] in REG01. The off state lasts for a duration of

t RST_DUR which can be programmed via tRST_DUR in REG01.

After this time the Qswitch and/or Qbypass will be

automatically turned on and the system is powered again.

During the off period, the nINT pin is biased to a lower

voltage.

The waveforms of power recycling are shown in Figure 7.

|nINT|t<br>RST_DGL|t<br>RST_DUR|Col4|Col5|
|---|---|---|---|---|
|V<br>BATT|V<br>BATT||||
|V<br>SYS|V<br>SYS||||
||||||



**Figure 7. Power Recycling Waveforms**

APRIL2021

19

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP **

All registers are 8-bit and individual bits are named from D[0] (LSB) to D[7] (MSB).

**I** **[2]** **C Slave Address is: 03H**

R/W: Read/Write bit(s).
R: Read only bit(s).

PORV: Power-On-Reset value.

n: Parameter code formed by the bits as an unsigned binary number.

**REG00**

Register address: 0x00; R/W

PORV = 10011111

**Table 4. REG00 Register Details**











|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:4]|VIN_MIN[3:0]|VIN_MIN[3]<br>1 = 640mV|Minimum Input Voltage Limit (n: 4 bits):<br>= 3.88 + 0.08n (V)<br>Offset: 3.88V<br>Range:3.88V (0000) - 5.08V (1111)<br>Default: 4.60V (1001)|1|R/W|REG_RST|
|D[7:4]|VIN_MIN[3:0]|VIN_MIN[2]<br>1 = 320mV|VIN_MIN[2]<br>1 = 320mV|0|R/W|REG_RST|
|D[7:4]|VIN_MIN[3:0]|VIN_MIN[1]<br>1 = 160mV|VIN_MIN[1]<br>1 = 160mV|0|R/W|REG_RST|
|D[7:4]|VIN_MIN[3:0]|VIN_MIN[0]<br>1= 80mV|VIN_MIN[0]<br>1= 80mV|1|R/W|REG_RST|
|D[3:0]|IIN_LIM[3:0]|IIN_LIM[3]<br>1 = 240mA|Input Current Limit (n: 4 bits):<br>= 50 + 30n (mA)<br>Offset: 50mA<br>Range: 50mA (0000) - 500mA (1111)<br>Default: 500mA (1111)|1|R/W|REG_RST|
|D[3:0]|IIN_LIM[3:0]|IIN_LIM[2]<br>1 = 120mA|IIN_LIM[2]<br>1 = 120mA|1|R/W|REG_RST|
|D[3:0]|IIN_LIM[3:0]|IIN_LIM[1]<br>1= 60mA|IIN_LIM[1]<br>1= 60mA|1|R/W|REG_RST|
|D[3:0]|IIN_LIM[3:0]|IIN_LIM[0]<br>1 = 30mA|IIN_LIM[0]<br>1 = 30mA|1|R/W|REG_RST|


**REG01**

Register address: 0x01; R/W

PORV = 10101100

**Table 5. REG01 Register Details**













|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:6]|tRST_DGL[1:0]|00 = 8s<br>01 = 12s<br>10 = 16s (default)<br>11 = 20s|nINT Pull-Down Period to Disconnect the<br>Battery (n: 2 bits):<br>= 8s + 4n (seconds)|1|R/W|REG_RST<br>or Watchdog|
|D[7:6]|tRST_DGL[1:0]|00 = 8s<br>01 = 12s<br>10 = 16s (default)<br>11 = 20s|nINT Pull-Down Period to Disconnect the<br>Battery (n: 2 bits):<br>= 8s + 4n (seconds)|0|R/W|REG_RST<br>or Watchdog|
|D[5]|tRST_DUR|0 = 2s<br>1 = 4s (default)|Battery FET off-time duration after reset.<br>The Qbypass and Qswitch off-time before auto<br>turn-on.|1|R/W|REG_RST<br>or Watchdog|
|D[4]|EN_HIZ|HIZ Mode Enable<br>0 = Disable (default)<br>1 = Enable|Control Qbypass switch.<br>Default: disable (0) or switch on<br>Note: The EN_HIZ bit only controls the on and<br>off of the Qbypass.|0|R/W|REG_RST<br>or Watchdog|
|D[3]|CEB|Setting Charge Enable<br>0 = Charge Enable<br>1 = Charge Disabled (default)|Charge enable/disable Qswitch configuration.<br>Default: charge disabled (1) or Qswitch off|1|R/W|REG_RST<br>or Watchdog|
|D[2:0]|VBAT_UVLO[2:0]|VBAT_UVLO[2]<br>1 = 360mV|Battery UVLO Threshold Value (n: 3 bits):<br>= 2.4V + 0.09n (V)<br>Offset: 2.4V<br>Range: 2.4V (000) - 3.03V (111)<br>Default: 2.76V (100)|1|R/W|REG_RST<br>or Watchdog|
|D[2:0]|VBAT_UVLO[2:0]|VBAT_UVLO[1]<br>1 = 180mV|VBAT_UVLO[1]<br>1 = 180mV|0|R/W|REG_RST<br>or Watchdog|
|D[2:0]|VBAT_UVLO[2:0]|VBAT_UVLO[0]<br>1 = 90mV|VBAT_UVLO[0]<br>1 = 90mV|0|R/W|REG_RST<br>or Watchdog|


APRIL2021

20

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP (continued) **

**REG02**

Register address: 0x02; R/W

PORV = 00001111

**Table 6. REG02 Register Details**











|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7]|REG_RST|Software Reset<br>0 = Keep Current Setting<br>(default)<br>1 = Reset|If set, will reset most parameters to default.<br>(as explained in the last column of register map<br>tables)|0|R/W|REG_RST|
|D[6]|WD_RST|I2C Watchdog Timer Reset<br>0 = Normal (default)<br>1 = Reset|If set, will reset watchdog timer.|0|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[5]<br>1= 256mA|Fast Charge Current Value (CC Mode)<br>(n: 5 bits): = 8mA + 8n (mA) (n ≤ 56)<br>Offset: 8mA<br>Range: 8mA (000000) - 456mA (111000)<br>Default: 128mA (001111)<br>Note:<br>Values above 56D = 111000 (456mA) are<br>clamped to 56D = 111000 (456mA).|0|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[4]<br>1 = 128mA|ICC[4]<br>1 = 128mA|0|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[3]<br>1 = 64mA|ICC[3]<br>1 = 64mA|1|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[2]<br>1 = 32mA|ICC[2]<br>1 = 32mA|1|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[1]<br>1 = 16mA|ICC[1]<br>1 = 16mA|1|R/W|REG_RST<br>or Watchdog|
|D[5:0]|ICC[5:0]|ICC[0]<br>1 = 8mA|ICC[0]<br>1 = 8mA|1|R/W|REG_RST<br>or Watchdog|


**REG03**

Register address: 0x03; R/W

PORV = 10010001

**Table 7. REG03 Register Details**









|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:4]|IDSCHG[3:0]|IDSCHG[3]<br>1 = 1600mA|BAT to SYS Discharge Current Limit Value<br>(n: 4 bits): = 200mA + 200n (mA), n ≠ 0<br>Offset: 200mA<br>Valid Range: 400mA (0001) - 3.2A (1111)<br>Default: 2000mA (1001)|1|R/W|REG_RST<br>or Watchdog|
|D[7:4]|IDSCHG[3:0]|IDSCHG[2]<br>1 = 800mA|IDSCHG[2]<br>1 = 800mA|0|R/W|REG_RST<br>or Watchdog|
|D[7:4]|IDSCHG[3:0]|IDSCHG[1]<br>1 = 400mA|IDSCHG[1]<br>1 = 400mA|0|R/W|REG_RST<br>or Watchdog|
|D[7:4]|IDSCHG[3:0]|IDSCHG[0]<br>1 = 200mA|IDSCHG[0]<br>1 = 200mA|1|R/W|REG_RST<br>or Watchdog|
|D[3:0]|ITERM[3:0]|ITERM[3]<br>1 = 16mA|Charge Termination Current Value (n: 4 bits):<br>= 1mA + 2n (mA)<br>Offset: 1mA<br>Range: 1mA (0000) - 31mA (1111)<br>Default: 3mA (0001)|0|R/W|REG_RST<br>or Watchdog|
|D[3:0]|ITERM[3:0]|ITERM[2]<br>1 = 8mA|ITERM[2]<br>1 = 8mA|0|R/W|REG_RST<br>or Watchdog|
|D[3:0]|ITERM[3:0]|ITERM[1]<br>1 = 4mA|ITERM[1]<br>1 = 4mA|0|R/W|REG_RST<br>or Watchdog|
|D[3:0]|ITERM[3:0]|ITERM[0]<br>1 = 2mA|ITERM[0]<br>1 = 2mA|1|R/W|REG_RST<br>or Watchdog|


APRIL2021

21

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP (continued) **

**REG04**

Register address: 0x04; R/W

PORV = 10100011

**Table 8. REG04 Register Details**









|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[5]<br>1 = 480mV|Battery Charge Regulation Voltage Value<br>(CV Mode) (n: 6 bits):<br>= 3.6V + 0.015n (V)<br>Offset: 3.60V<br>Range: 3.60V (000000) - 4.545V (111111)<br>Default: 4.2V (101000)|1|R/W|REG_RST<br>or Watchdog|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[4]<br>1 = 240mV|VBAT_REG[4]<br>1 = 240mV|0|R/W|REG_RST<br>or Watchdog|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[3]<br>1 = 120mV|VBAT_REG[3]<br>1 = 120mV|1|R/W|REG_RST<br>or Watchdog|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[2]<br>1 = 60mV|VBAT_REG[2]<br>1 = 60mV|0|R/W|REG_RST<br>or Watchdog|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[1]<br>1 = 30mV|VBAT_REG[1]<br>1 = 30mV|0|R/W|REG_RST<br>or Watchdog|
|D[7:2]|VBAT_REG[5:0]|VBAT_REG[0]<br>1 = 15mV|VBAT_REG[0]<br>1 = 15mV|0|R/W|REG_RST<br>or Watchdog|
|D[1]|VBAT_PRE|Pre-Charge to Fast Charge<br>Threshold<br>0 = 2.8V<br>1 = 3.0V (default)||1|R/W|REG_RST<br>or Watchdog|
|D[0]|VRECH|Battery Recharge Threshold<br>0 = 100mV<br>1 = 200mV (default)|Offset below VBAT_REG.|1|R/W|REG_RST<br>or Watchdog|


**REG05**

Register address: 0x05; R/W

PORV = 01111010

**Table 9. REG05 Register Details**



|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7]|EN_WD_DISCHG|Watchdog Control<br>0 = Disable (default)<br>1 = Enable|Watchdog control in discharge mode.|0|R/W|REG_RST|
|D[6:5]|WATCHDOG[1:0]|Watchdog Timer<br>00 = Disable timer<br>01 = 40s<br>10 = 80s<br>11 = 160s (default)|If WATCHDOG[1:0] = 00, then watchdog timer<br>is disabled no matter EN_WD_DISCHG is set<br>or not.|1|R/W|REG_RST|
|D[6:5]|WATCHDOG[1:0]|Watchdog Timer<br>00 = Disable timer<br>01 = 40s<br>10 = 80s<br>11 = 160s (default)|If WATCHDOG[1:0] = 00, then watchdog timer<br>is disabled no matter EN_WD_DISCHG is set<br>or not.|1|R/W|REG_RST|
|D[4]|EN_TERM|Termination Control<br>0 = Disable<br>1 = Enable (default)|Use termination or not.|1|R/W|REG_RST<br>or Watchdog|
|D[3]|EN_TIMER|Safety Timer Control<br>0 = Disable<br>1 = Enable (default)|Charge safety timer enable/disable setting.|1|R/W|REG_RST<br>or Watchdog|
|D[2:1]|CHG_TMR[1:0]|Charge Timer<br>00 = 3hrs<br>01 = 5hrs (default)<br>10 = 8hrs<br>11 = 12hr||0|R/W|REG_RST<br>or Watchdog|
|D[2:1]|CHG_TMR[1:0]|Charge Timer<br>00 = 3hrs<br>01 = 5hrs (default)<br>10 = 8hrs<br>11 = 12hr||1|R/W|REG_RST<br>or Watchdog|
|D[0]|TERM_TMR|Termination Timer Control<br>0 = Disable (default)<br>1 = Enable|When TERM_TMR is enabled, the device will<br>not suspend the charge current after charge<br>termination.|0|R/W|REG_RST<br>or Watchdog|


APRIL2021

22



## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP (continued) **

**REG06**

Register address: 0x06; R/W

PORV = 11000000

**Table 10. REG06 Register Details**











|BITS|BIT NAME|DESCRIPTION|COMMENT|POR|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7]|EN_NTC|NTC Control<br>0 = Disable<br>1 = Enable (default)||1|R/W|REG_RST<br>or Watchdog|
|D[6]|TMR2X_EN|Enable Half Clock Rate Safety Timer<br>0 = Disable.<br>1 = Enable 2× extended<br>safety timer during PPM. (default)||1|R/W|REG_RST<br>or Watchdog|
|D[5]|FET_DIS|0 = Enable (default)<br>1 = Disable|Qswitch control for shipping mode<br>and system power recycle.<br>Note: The FET_DIS bit controls the<br>on and off of the Qswitch in both<br>charging and discharging.|0|R/W|REG_RST|
|D[4]|PG_INT_CTL|0 = On (default)<br>1 = Off||0|R/W|REG_RST<br>or Watchdog|
|D[3]|EOC_INT_CTL|Charge Completed INT Mask Control<br>0 = On (default)<br>1 = Off||0|R/W|REG_RST<br>or Watchdog|
|D[2]|CHG_STATUS_<br>INT_CTL|Charging Status Change INT Mask<br>Control<br>0 = On (default)<br>1 = Off|Charging statuses are: not<br>charging, pre-charge and charge.|0|R/W|REG_RST<br>or Watchdog|
|D[1]|NTC_INT_CTL|0 = On (default)<br>1 = Off||0|R/W|REG_RST<br>or Watchdog|
|D[0]|BATOVP_INT_CTL|0 = On (default)<br>1 = Off||0|R/W|REG_RST<br>or Watchdog|


**REG07**

Register address: 0x07; R/W

PORV = 00110111

**Table 11. REG07 Register Details**









|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7]|EN_PCB OTP|PCB OTP Enable<br>0 = Enable (default)<br>1 = Disable||0|R/W|REG_RST<br>or Watchdog|
|D[6]|EN_VINLOOP|0 = Enable (default)<br>1 = Disable||0|R/W|REG_RST<br>or Watchdog|
|D[5:4]|TJ_REG[1:0]|Thermal Regulation Threshold<br>00 = 60℃<br>01 = 80℃<br>10 = 100℃<br>11 = 120℃ (default)||1|R/W|REG_RST<br>or Watchdog|
|D[5:4]|TJ_REG[1:0]|Thermal Regulation Threshold<br>00 = 60℃<br>01 = 80℃<br>10 = 100℃<br>11 = 120℃ (default)||1|R/W|REG_RST<br>or Watchdog|
|D[3:0]|VSYS_REG[3:0]|VSYS_REG[3]<br>1 = 400mV|System Regulation Voltage Value:<br>= 4.2V + 0.05n (V) (n: 4 bits)<br>Offset: 4.2V<br>Range: 4.2V (0000) - 4.95V (1111)<br>Default: 4.55V (0111)|0|R/W|REG_RST|
|D[3:0]|VSYS_REG[3:0]|VSYS_REG[2]<br>1 = 200mV|VSYS_REG[2]<br>1 = 200mV|1|R/W|REG_RST|
|D[3:0]|VSYS_REG[3:0]|VSYS_REG[1]<br>1 = 100mV|VSYS_REG[1]<br>1 = 100mV|1|R/W|REG_RST|
|D[3:0]|VSYS_REG[3:0]|VSYS_REG[0]<br>1 = 50mV|VSYS_REG[0]<br>1 = 50mV|1|R/W|REG_RST|


APRIL2021

23


## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP (continued) **

**REG08**

Register address: 0x08; R and RW

PORV = 00000000

**Table 12. REG08 Register Details**




|BITS|BIT NAME|DESCRIPTION|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|
|D[7]|WTD_FAULT|Watchdog Expiration<br>0 = Normal (default)<br>1 = Watchdog Timer Expiration|0|R|NA|
|D[6]|IIN_LIM_REL|Input Current Limit Release<br>0 = Disable (default)<br>1 = Enable|0|R/W|REG_RST<br>or Watchdog|
|D[5]|IIN_LIM_ADD200|Add 200mA to Input Current Limit<br>0 = Disable (default)<br>1 = Enable|0|R/W|REG_RST<br>or Watchdog|
|D[4:3]|CHG_STAT[1:0]|Charging Status<br>00 = Not Charging (default)<br>01 = Pre-Charge<br>10 = Charge<br>11 = Charge Done|0|R|NA|
|D[4:3]|CHG_STAT[1:0]|Charging Status<br>00 = Not Charging (default)<br>01 = Pre-Charge<br>10 = Charge<br>11 = Charge Done|0|R|NA|
|D[2]|PPM_STAT|Device in Power Path Management Mode (PPM)<br>0 = No PPM (default)<br>1 = IN PPM|0|R|NA|
|D[1]|PG_STAT|Input Power (IN) Status<br>0 = Power Fail (default)<br>1 = Power Good|0|R|NA|
|D[0]|THERM_STAT|Thermal Regulation Status<br>0 = No Thermal Regulation (default)<br>1 = In Thermal Regulation|0|R|NA|


**REG09**

Register address: 0x09; R and R/W

PORV = 00000000

**Table 13. REG09 Register Details**


|BITS|BIT NAME|DESCRIPTION|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|
|D[7:6]|EN_SHIP_DGL<br>[1:0]|Enter Shipping Mode Deglitch Time<br>00 = 1s (default)<br>01 = 2s<br>10 = 4s<br>11 = 8s|0|R/W|REG_RST|
|D[7:6]|EN_SHIP_DGL<br>[1:0]|Enter Shipping Mode Deglitch Time<br>00 = 1s (default)<br>01 = 2s<br>10 = 4s<br>11 = 8s|0|R/W|REG_RST|
|D[5]|VIN_FAULT|Input VIN Fault Status<br>0 = Normal (default)<br>1 = Input Fault (OVP or bad source)|0|R|NA|
|D[4]|THEM_SD|Thermal Shutdown Fault Status<br>0 = Normal (default)<br>1 = Thermal Shutdown|0|R|NA|
|D[3]|BAT_FAULT|Battery Over-Voltage Fault Status<br>0 = Normal (default)<br>1 = Battery OVP|0|R|NA|
|D[2]|STMR_FAULT|Safety Timer Expiration Fault Status<br>0 = Normal (default)<br>1 = Safety Timer Expiration|0|R|NA|
|D[1]|NTC_FAULT[1]|NTC Exceeding Hot Level<br>0 = Normal (default)<br>1 = NTC Hot|0|R|NA|
|D[0]|NTC_FAULT[0]|NTC Exceeding Cold Level<br>0 = Normal (default)<br>1 = NTC Cold|0|R|NA|


APRIL2021

24



## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **REGISTER MAP (continued) **

**REG0A**

Register address: 0x0A; R and R/W

PORV = 01100000

**Table 14. REG0A Register Details**






|BITS|BIT NAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:5]|ADDR[2:0]|Slave Address<br>001 = 01H<br>010 = 02H<br>011 = 03H (default)<br>100 = 04H<br>101 = 05H<br>110 = 06H<br>111 = 07H||0|R|NA|
|D[7:5]|ADDR[2:0]|Slave Address<br>001 = 01H<br>010 = 02H<br>011 = 03H (default)<br>100 = 04H<br>101 = 05H<br>110 = 06H<br>111 = 07H||1|R|NA|
|D[7:5]|ADDR[2:0]|Slave Address<br>001 = 01H<br>010 = 02H<br>011 = 03H (default)<br>100 = 04H<br>101 = 05H<br>110 = 06H<br>111 = 07H||1|R|NA|
|D[4]|COLD_RESET|Software Power Recycle<br>0 = No Action (default)<br>1 = Power Recycle Reset|Causes a system power recycles if set to 1.<br>Automatically clears after power recycle.|0|R/W|NA|
|D[3]|SWITCH_MODE|0 = Normal Power Path (default)<br>1 = Qswitch Forced On|Effective in battery discharge mode only.<br>When Qswitch is forced on, there is no<br>current and voltage limit because the internal<br>circuits are shut down for lower consumption.|0|R/W|NA|
|D[2]|DIS_VDD|0 = Enable Battery Power (default)<br>1 = Disable Battery Power|If set to 1, V becomes high-impedance<br>DD<br>when V is removed.<br>IN<br>If the PCB OTP of NTC function is be<br>selected, the DIS_VDD bit setting is invalid.|0|R/W|NA|
|D[1]|DIS_VINOVP|0 = Enable (default)<br>1 = Disable|Disables over-voltage lockout detection of<br>V if set to 1.<br>IN|0|R/W|NA|
|D[0]|CC_FINE|0 = Normal Scale (default)<br>1 = Fine Scale|If set to 1, the programmed charge current<br>in ICC[5:0] is weighted to ¼.|0|R/W|NA|


**REG0B**

Register address: 0x0B; R

PORV = 00000100 (SGM41562)

**Table 15. REG0B Register Details**





|BITS|BITNAME|DESCRIPTION|COMMENT|PORV|TYPE|RESET BY|
|---|---|---|---|---|---|---|
|D[7:0]|ID[7:0]|Device ID|SGM41562 = 00000100||R|NA|


APRIL2021

25

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **OTP MAP **

The following table shows the one time programmable (OTP) regions of the register map. The OTP bits can be read only.




|ADDRESS|Bit7|Bit6|Bit5|Bit4|Bit3|Bit2|Bit1|Bit0|
|---|---|---|---|---|---|---|---|---|
|0x0A|OTP BITS: ADDR[2:0]|OTP BITS: ADDR[2:0]|OTP BITS: ADDR[2:0]|COLD_<br>RESET|SWITCH_<br>MODE|DIS_VDD|DIS_VINOVP|CC_FINE|
|0x0B|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|OTP BITS: ID[7:0]|

## **OTP DEFAULT **

|OTP ITEMS|DEFAULT|
|---|---|
|ICC|128mA|
|ITERM|3mA|
|VBAT_REG|4.2V|
|WATCHDOG|160s|
|EN_VINLOOP|Enable|
|Address|03H|
|Device ID|SGM41562: 00000100. V = 6V<br>IN_OVLO| **STATE CONVERSION CHART **





















**Figure 8. State Machine Conversion**


APRIL2021

26

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **CONTROL FLOW CHART **








|YES|Col2|
|---|---|
|Write<br>EN_WD_DISCHG[ ]=1|Write<br>EN_WD_DISCHG[ ]=1|
||YES|

|MONITOR MODE<br>- Set Registers to Default<br>- Set WATCHDOG[1:0] to 01<br>- Start Watchdog Timer Counter|Col2|
|---|---|
|||





















**Figure 9. Startup, Host Mode, Default Mode and Host Power Reset**


APRIL2021

27

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **CONTROL FLOW CHART (continued) **

V IN < V IN_UVLO or V IN                      - V IN_OVLO
or V IN < V BAT + V SLP
or CEB[ ] = 1 or BATFET OFF

















**Figure 10. Charging Process**


APRIL2021

28

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **CONTROL FLOW CHART (continued) **







|Regulation Mode<br>V is regulated at V<br>SYS SYS_REG<br>NO<br>V < 1.5V<br>SYS<br>YES<br>YES I > 360mA (Fixed)<br>IN<br>Current Limit<br>NO<br>NO<br>I > I<br>IN IN_LIM<br>YES<br>CC Mode<br>Limit I at I<br>IN IN_LIM<br>Start 60μs Timer<br>NO<br>60μs Expired<br>YES<br>Hiccup Mode<br>Turn off Qbypass and Qswitch,<br>Start 800μs Timer<br>NO<br>800μs Expired<br>YES<br>Turn On Qbypass and Qswitch|Col2|
|---|---|
|Regulation Mode<br>V is regulated at V<br>SYS SYS_REG<br>NO<br>V < 1.5V<br>SYS<br>YES<br>YES I > 360mA (Fixed)<br>IN<br>Current Limit<br>NO<br>NO<br>I > I<br>IN IN_LIM<br>YES<br>CC Mode<br>Limit I at I<br>IN IN_LIM<br>Start 60μs Timer<br>NO<br>60μs Expired<br>YES<br>Hiccup Mode<br>Turn off Qbypass and Qswitch,<br>Start 800μs Timer<br>NO<br>800μs Expired<br>YES<br>Turn On Qbypass and Qswitch|Turn On Qbypass and Qswitch|
|||

|Battery Discharge<br>Battery Supplement or Discharged<br>NO<br>V < 1.5V<br>SYS<br>YES<br>Fold Back BAT to V<br>SYS<br>Current I to 50%<br>DISCHG<br>YES I > 3.7A (Fixed)<br>BAT<br>Current Limit<br>NO<br>NO<br>I > I<br>BAT DISCHG<br>YES<br>CC Mode<br>Limit I at I<br>BAT DISCHG<br>Start 60μs Timer<br>NO<br>60μs Expired<br>YES<br>Hiccup Mode<br>Turn off Qbypass and Qswitch,<br>Start 800μs Timer<br>NO<br>800μs Expired<br>YES<br>Turn On Qbypass and Qswitch|Col2|
|---|---|
|Battery Discharge<br>Battery Supplement or Discharged<br>NO<br>V < 1.5V<br>SYS<br>YES<br>Fold Back BAT to V<br>SYS<br>Current I to 50%<br>DISCHG<br>YES I > 3.7A (Fixed)<br>BAT<br>Current Limit<br>NO<br>NO<br>I > I<br>BAT DISCHG<br>YES<br>CC Mode<br>Limit I at I<br>BAT DISCHG<br>Start 60μs Timer<br>NO<br>60μs Expired<br>YES<br>Hiccup Mode<br>Turn off Qbypass and Qswitch,<br>Start 800μs Timer<br>NO<br>800μs Expired<br>YES<br>Turn On Qbypass and Qswitch|Turn On Qbypass and Qswitch|
|||


**Figure 11. System Short Circuit Protection**


APRIL2021

29

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **APPLICATION INFORMATION **


**Resistor Divider for NTC Sensor**

A resistor divider between VDD and GND pins can be used to

adjust the battery temperature limits sensed by the NTC

sensor. The R T1 and R T2 resistors (see Figure 12) allow

independent programming of the high and low temperature

limits for any type of NTC temperature characteristics.




V COLD

Hot Temp Threshold
V HOT

|VDD|Col2|Col3|Col4|
|---|---|---|---|
|R<br>T1<br>NTC<br>R<br>T2|R<br>T1<br>NTC<br>R<br>T2|||
|R<br>T1<br>NTC<br>R<br>T2|NTC|||
|R<br>T1<br>NTC<br>R<br>T2|NTC|||


**Figure 12. NTC Function Block**

For a given NTC thermistor, if the NTC resistances at the

desired high and low temperatures are R NTCH and R NTCL

respectively, R T1 and R T2 values can be calculated by:


( V COLD − V HOT ) × R NTCH × R NTCL
( V HOT − V COLD V HOT ) × R NTCL − ( V COLD − V COLD V HOT )


R T2 = V − V ( VV COLD ×−RV HOT ) −× RV NTCH −× RV NTCL V × R


= COLD − HOT × NTCH × NTCL

V − V V × R − V − V V ×


T2 = ( V HOT − V COLD V HOTCOLD ) × R NTCLHOT − ( V COLDNTCH − V COLDNTCL V HOT ) × R NTCH


R T1 = 1− V COLD × ( R T2 / /R NTCL )
V COLD


where V COLD and V HOT thresholds values are voltage levels on

the NTC pin given in the EC table for hot and cold detection.

For example, for a thermistor with R 25℃ = 10kΩ and β = 3260,

R NTCL is 27.2kΩ at T COLD = 0℃, and R NTCH is 4.29kΩ at T HOT =

50℃. Using Equation 1 and Equation 2 to calculate R T1 =

7.6kΩ and R T2 = 29.33kΩ (to be recalculated when the EC

table mean values are characterized), assuming that the NTC

window is between 0℃ and 50℃ and using the V COLD and

V HOT values from the EC table.


**External Capacitor Selection**
Like many low-dropout regulators, SGM41562 requires

external capacitors on its power ports for stability and noise or

spike voltage immunity. These capacitors must be properly

selected and placed near the device.

**Input Capacitor (IN to GND)**
A minimum 2.2μF input capacitor must be connected between

IN and GND pins for stable operation over full load range. In

general an output capacitance larger than the input capacitor

is acceptable if the input capacitor is at least 2.2μF.

**Output Capacitor (SYS to GND)**
SGM41562 is designed specifically to operate with small

ceramic output capacitance. A ceramic capacitor (X5R or X7R)

larger than 2.2μF is suitable for the SGM41562 applications.

The output capacitor should be connected close to the device

between SYS and GND pins with thick traces and small loop

area.

**BAT to GND Capacitor**
A capacitor is needed between BAT and GND pins. Use a

ceramic capacitor (X5R or X7R) that is at least 2.2μF.

**VDD to GND Capacitor**

VDD voltage powers the internal control and logic circuit. It is

critical to use a 0.1μF decoupling ceramic capacitor between

VDD pin and GND close to the device with thick PCB traces

to decouple noise and stabilize VDD voltage.

**PCB Layout Guide**
1. Place external capacitors as close as possible to the

device to minimize stray inductances and connection

impedance.

2. The GND for the I [2] C signals should be clean and directly
connected to GND pin, without sharing its route with GND
returns that carry high current or switching currents.

3. Due to relatively slow rise/fall times, it is ok to route the
I [2] C wires in parallel on the same PCB layer.

APRIL2021

30

## **500mA Single-Cell Li-Ion Battery Charger ** **SGM41562 with Power Path Management ** **TYPICAL APPLICATION CIRCUIT **



SYS







Input
/Host








|A1 A2<br>5V IN SYS<br>C C<br>1 2<br>4.7μF 10μF<br>B3<br>VDD<br>C B2<br>3 nINT<br>R T1 1μF<br>B1 Push<br>NTC SGM41562<br>Button<br>R<br>NTC T2 A3<br>BAT BAT<br>C<br>4<br>4.7μF<br>C1 C3<br>SDA GND<br>Host C2<br>SCL|Col2|
|---|---|
|Host|Host|
|Host||


**Figure 13. SGM41562 Typical Application Circuit with 5V Input**

**Table 16. The Key BOM of Figure 13**

|QTY|REF|VALUE|DESCRIPTION|PACKAGE|
|---|---|---|---|---|
|1|C1, C4|4.7µF|Ceramic Capacitor; 16V; X5R or X7R|0603|
|2|C2|10µF|Ceramic Capacitor; 16V; X5R or X7R|0603|
|1|C3|1µF|Ceramic Capacitor; 16V; X5R or X7R|0603|


APRIL2021

31

## **PACKAGE INFORMATION **

## **PACKAGE OUTLINE DIMENSIONS ** **WLCSP-1.47×1.47-9B **









NOTE: All linear dimensions are in millimeters.


TX00168.001

## **TAPE AND REEL INFORMATION **

**REEL DIMENSIONS**

Reel Width (W1)

## **PACKAGE INFORMATION **

**TAPE DIMENSIONS**

P2 P0






|Q1|Q2|
|---|---|
|Q3|Q4|

|Q1|Q2|
|---|---|
|Q3|Q4|


|W<br>Q1 Q2 Q1 Q2 Q1 Q2<br>B0<br>Q3 Q4 Q3 Q4 Q3 Q4<br>P1 A0|Col2|Col3|Col4|Col5|
|---|---|---|---|---|
|W<br>Q1 Q2 Q1 Q2 Q1 Q2<br>B0<br>Q3 Q4 Q3 Q4 Q3 Q4<br>P1 A0|Q1|Q2||B0|
|W<br>Q1 Q2 Q1 Q2 Q1 Q2<br>B0<br>Q3 Q4 Q3 Q4 Q3 Q4<br>P1 A0|Q3|Q4|Q4|Q4|
|W<br>Q1 Q2 Q1 Q2 Q1 Q2<br>B0<br>Q3 Q4 Q3 Q4 Q3 Q4<br>P1 A0|A0|A0|||

|Col1|Col2|Col3|Col4|
|---|---|---|---|
|||||
|Reel Width (W1)|Reel Width (W1)|Reel Width (W1)|Reel Width (W1)|


**DIRECTION OF FEED**

NOTE: The picture is only for reference. Please make the object as the standard.

**KEY PARAMETER LIST OF TAPE AND REEL**












|Re<br>Package Type<br>Diam|Reel Width<br>el<br>W1<br>eter<br>(mm)|A0<br>(mm)|B0<br>(mm)|K0<br>(mm)|P0<br>(mm)|P1<br>(mm)|P2<br>(mm)|W<br>(mm)|Pin1<br>Quadrant|
|---|---|---|---|---|---|---|---|---|---|
|WLCSP-1.47×1.47-9B 7″|9.2|1.61|1.61|0.7|4.0|4.0|2.0|8.0|Q1|


TX10000.000

## **PACKAGE INFORMATION **


**CARTON BOX DIMENSIONS**

NOTE: The picture is only for reference. Please make the object as the standard.

**KEY PARAMETER LIST OF CARTON BOX**





|Reel Type|Length<br>(mm)|Width<br>(mm)|Height<br>(mm)|Pizza/Carton|
|---|---|---|---|---|
|7″ (Option)|368|227|224|8|
|7″|442|410|224|18|


TX20000.000

