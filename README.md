# Project Electra

Project Electra is a rather complex multifaceted project dealing with, most simply put, electrical and electrochemical measurements. There are three Sub-Projects to Project Electra, however, only the first two will be made open-source and publicly available for a variety of reasons including the third's complexity, multi-field integration, primarily its potential for in its completed state to be a revolutionary commercial product, as well as a few other reasons. I would not suggest trying to devise what sub-project 3 is as it is ridiculously unlikely that even given Sub-Projects 1 & 2 knowledge Sub-Project 3 is related tangentially and non-linearly. 

## Project Electra Sub-Project One

Sub-Project One is by and far the most simple. It is a battery cycler project that can perform cycling using the constant current method (CC) or constant current - constant voltage method (CC/CV) during battery testing. 

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
- Ethernet Switch
- Ethernet to GPIB Adapter
- GPIB Networking
- Ethernet Networking
- Thermocouples >= 2
    - Type K
        - Range:        -200&deg;C to 1350&deg;C
        - Sensitivity:  41&mu;V/C Sensitivity
- 2x Type K (-200C to 1350C, 41uV/C Sensitivity), Type T(-200C to 350C, 43uV/C), or Type E(-110C to 140C, 68uV/C); most likely Type T.
- Omega Force Strain Gauge
- Microcontroller and assorted electrical components including:
    - Precision Strain Gauge
    - Operational Amplifiers
        - Standard
        - Instrumental
        - Rail to Rail
    - Resistors
        - Low Accuracy
        - High Accuracy
        - Low Wattage/Current
        - High Wattage/Current
    - Inductors
        - Standard
        - Toroid
    - Capacitors
        - Ceramic
        - Electrolytic
        - Polymer
        - Etc.
    - Transistors
    - 4 x Analog to Digital Converter (ADC) >= 16bit
    - PIR Motion Detector
    - Potentiometers, varying resistance ranges
    - Interface Electronics
        - Buttons
        - Switches
        - Rotary encoders
        - Display elements
        - LEDs
        - Etc. 
    - Transformers
        - Standard
        - Tapped
    - Diodes
        - General
        - Zerner Diodes
    - Voltage Regulators
    - Multiple Fuses
    - Oscillators
        - Crystal
        - Other
    - Relays
    - Logic ICs
        - AND
        - OR
        - NAND
        - NOR
        - XOR
        - Inverter
    - Flip Flops
        - D Type
        - JK Type
        - SR Type
    - 555 Timers
    - Counter
    - EEPROM(s)
    - Register(s)
    - Multiplexers
    - DeMultiplexers
    - Encoders
    - Decoders
    - TPM
    - Shift Register
    - Toroid Inductors
    - Triacs
    - Thyristor
    - Optocouplers
    - Rectifiers
    - Thermistors
    - Relays
        - Mechanical
        - Solid State
        - Optical

- Hardware Interface for Initialization, Activation, Simple Configuration, and Simple/Basic Control.
- Computer and Software Interface for System Use, Control, Data Collection, Data Retrieval, Analysis, Sub-System Management, etc. 
- Atmospheric Hygrometer / Humidity Sensor
- Atmospheric Barometric Pressure Sensor
- Pressure Transducer
- Altimeter
- Vibration Sensor
- 3 Axis Gyroscope
- Thermal Camera

