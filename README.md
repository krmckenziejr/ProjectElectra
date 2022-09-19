# Project Electra

Project Electra is a rather complex multifaceted project dealing with, most simply put, electrical and electrochemical measurements. There are three Sub-Projects to Project Electra, however, only the first two will be made open-source and publicly available for a variety of reasons including the third's complexity, multi-field integration, primarily its potential for in its completed state to be a revolutionary commercial product, as well as a few other reasons. I would not suggest trying to devise what sub-project 3 is as it is ridiculously unlikely that even given Sub-Projects 1 & 2 knowledge Sub-Project 3 is related tangentially and non-linearly. 

## Project Electra Sub-Project One

Sub-Project One is by and far the most simple. It is a battery cycler project that can perform cycling using the constant current method (CC) or constant current constant voltage method (CC/CV) during battery testing. 

## Project Electra Sub-Project Two

Sub-Project Two is considerably more complex than Sub-Project One. To Start, it integrates several independent instruments and uses them in concert with one another. These instruments (or Sub-Systems) are the following:
- Keithley 2400 High Accuracy Multimeter as well as either a Current or Voltage Source.
- Keithley 2182A NanoVoltmeter
- Keithley 6517A Electrometer / High Resistance Meter
- Solartron 1260 Impedance Gain-Phase Analyzer
- Solartron 1287 ElectroChemical Interface
- Maccor Battery Cycler Model MC-4
- Thermal Products Solutions Tenney Model TJR Thermal Isolation Chamber
- Potentially Keithley 2700 Multimeter, Current or Voltage Source, and Data Acquisition Device

Other hardware and networking utilized includes the following:
<table border="0">
    <tr>
        <td>
            <ul>
                <li>Ethernet Hardware</li>
                    <ul>
                        <li>Managed Switch; Ethernet Networking</li>
                        <li>Wiring/Cabling</li>
                        <li>Ethernet to GPIB Adapter</li>
                    </ul>
                <li>GPIB Networking</li>
                <li>Thermocouples >= 2</li>
                    <ul>
                        <li>Type K</li>
                            <ul>
                                <li>Range:        -200&deg;C to 1350&deg;C</li>
                                <li>Sensitivity:  41&mu;V/C</li>
                            </ul>
                        <li>Type T</li>
                            <ul>
                                <li>Range:        -200&deg;C to 350&deg;C</li>
                                <li>Sensitivity:  43&mu;V/C</li>
                            </ul>
                        <li>Type E</li>
                            <ul>
                                <li>Range:        -110&deg;C to 140&deg;C</li>
                                <li>Sensitivity:  68&mu;V/C</li>
                            </ul>
                        <li>Most Likely Type Chosen is Type T</li>
                    </ul>
                <li>Strain Gauge</li>
                    <ul>
                        <li>Precise</li>
                        <li>Sensitive</li>
                        <li>Detect Small (&mu;m or smaller changes is goal)</li>
                    </ul>
                <li>Microcontroller and assorted electrical components including:</li>
                    <ul>
                        <li>Operational Amplifiers</li>
                            <ul>
                                <li>Standard</li>
                                <li>Instrumental</li>
                                <li>Rail to Rail</li>
                                <li>Precision</li>
                                <li>JFET</li>
                                <li>Low Noise</li>
                                <li>Low Power</li>
                                <li>Type Combination</li>
                            </ul>
                        <li>Resistors</li>
                            <ul>
                                <li>Low Accuracy</li>
                                <li>High Accuracy</li>
                                <li>Low Wattage/Current</li>
                                <li>High Wattage/Current</li>
                            </ul>
                        <li>Inductors</li>
                            <ul>
                                <li>Standard</li>
                                <li>Wire Coils</li>
                                <li>Toroid</li>
                            </ul>
                        <li>Capacitors</li>
                            <ul>
                                <li>General</li>
                                <li>Ceramic</li>
                                <li>Electrolytic</li>
                                <li>Polymer</li>
                                <li>Tantalum</li>
                                <li>Etc.</li>
                            </ul>
                    </ul>
                <li>Transistors</li>
                    <ul>
                        <li>General</li>
                            <ul>
                                <li>NPN</li>
                                <li>PNP</li>
                            </ul>
                        <li>FET</li>
                            <ul>
                                <li>NPN</li>
                                <li>PNP</li>
                            </ul>
                        <li>MOSFETT </li>
                            <ul>
                                <li>NPN</li>
                                <li>PNP</li>
                            </ul>
                        <li>IGBT</li>
                        <li>UJT</li>
                    </ul>
                <li>4 x Analog to Digital Converter (ADC) >= 16bit</li>
                <li>PIR Motion Detector</li>
                <li>Potentiometers, varying resistance ranges</li>
                <li>Interface Electronics</li>
                    <ul>
                        <li>Buttons</li>
                        <li>Switches</li>
                        <li>Rotary encoders</li>
                        <li>Display elements</li>
                        <li>LEDs</li>
                        <li>Etc. </li>
                    </ul>
                <li>Transformers</li>
                    <ul>
                        <li>Standard</li>
                        <li>Tapped</li>
                    </ul>
                <li>Diodes</li>
                    <ul>
                        <li>General</li>
                        <li>Signal Diodes</li>
                        <li>Zerner Diodes</li>
                        <li>Rectifier Diodes</li>
                    </ul>
            </ul>
        </td>
        <td>
            <ul>
                <li>Voltage Regulators</li>
                    <ul>
                        <li>Negative Voltage</li>
                        <li>Positive Voltage</li>
                    </ul>
                <li>Current Regulators</li>
                    <ul>
                        <li>Negative Current</li>
                        <li>Positive Current</li>
                    </ul>
                <li>Multiple Fuses</li>
                <li>Oscillators</li>
                    <ul>
                        <li>Crystal</li>
                        <li>Other</li>
                    </ul>  
                <li>Relays</li>
                <li>Logic ICs</li>
                    <ul>
                        <li>AND</li>
                        <li>OR</li>
                        <li>NAND</li>
                        <li>NOR</li>
                        <li>XOR</li>
                        <li>Inverter</li>
                    </ul>
                <li>Flip Flops</li>
                    <ul>
                        <li>D Type</li>
                        <li>JK Type</li>
                        <li>SR Type</li>
                    </ul>
                <li>555 Timers</li>
                <li>Counter</li>
                    <ul>
                        <li>Binary</li>
                            <ul>
                                <li>Up</li>
                                <li>Down</li>
                            </ul>
                        <li>Decade</li>
                            <ul>
                                <li>Up</li>
                                <li>Down</li>
                            </ul>
                        <li>Decimal</li>
                            <ul>
                                <li>Up</li>
                                <li>Down</li>
                            </ul>
                        <li>Octal</li>
                            <ul>
                                <li>Up</li>
                                <li>Down</li>
                            </ul>
                    </ul>
                <li>EEPROM(s)</li>
                <li>Register(s)</li>
                <li>Multiplexers</li>
                <li>DeMultiplexers</li>
                <li>Encoders</li>
                <li>Decoders</li>
                <li>TPM</li>
                <li>Register</li>
                    <ul>
                        <li>General</li>
                        <li>8 Bit Shift</li>
                        <li>4 Step Shift</li>
                        <li>8 Step Shift</li>
                        <li>64 Step Shift</li>
                        <li>Quad D Type</li>
                        <li>32 Stage Shift</li>
                        <li>4 Bit Right / Left Shift</li>
                    </ul>
                <li>Comparator</li>
                <li>Toroid Inductors</li>
                <li>Triacs</li>
                <li>Thyristor</li>
                <li>Optocouplers</li>
                <li>Rectifiers</li>
                    <ul>
                        <li>Full Wave Bridge Rectifier</li>
                    </ul>
                <li>Thermistors</li>
                    <ul>
                        <li>NTC Type</li>
                        <li>PTC Type</li>
                    </ul>
                <li>Relays</li>
                    <ul>
                        <li>Mechanical</li>
                        <li>Solid State</li>
                        <li>Optical</li>
                    </ul>
                <li>Real Time Clock or RTC</li>
                <li>Analog Switch IC</li>
                <li>Phase Locked Loop</li>
                <li>Monostable MultiVibrator</li>
                <li>Astable MultiVibrator</li>
                <li>Hardware Interface for Initialization, Activation, Simple Configuration, and Simple/Basic Control.</li>
                <li>Computer and Software Interface for System Use, Control, Data Collection, Data Retrieval, Analysis, Sub-System Management, etc. </li>
                <li>Atmospheric Hygrometer / Humidity Sensor</li>
                <li>Atmospheric Barometric Pressure Sensor</li>
                <li>Pressure Transducer</li>
                <li>Altimeter</li>
                <li>Vibration Sensor</li>
                <li>3 Axis Gyroscope</li>
                <li>Thermal Camera</li>
            </ul>
        </td>
    </tr>
</table>



