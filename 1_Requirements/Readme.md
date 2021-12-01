# **Requirements**

**Introduction**

Now-days everyone is looking for automation and advancements in all the sectors. The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In European countries, the temperature is very low and any electronic designer should make sure that his equipment should work efficiently in that whether. In our project, the sensor will sense is the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. Read the values given to the ADC from the temperature sensor. Generate PWM pulses according to the ADC values and displaying it on a CRO.

**Features**

- The System will sense is driver or passenger seated or not.

- Driver or Passenger has the access to modify the temperature in the vehicle.

- As per Drivers request, Heater will generate the heat accordingly.

- Low cost and robust system.

**SWOT- Strengths, and Weakness, Opportunities Threats**

**Strengths**

- User Friendly

- Easy to alter the temperature inside the vehicles.

- Low cost and Robust system.

**Weakness**

- Its only applicable for those countries which are having low temperature.

**Opportunities**

- It can be implemented by having both Heater and AC.

**Threats**

- Not suitable for average or high temperature places.

**4W&#39;s and 1&#39;H**

**WHAT : SeatHeatingApplication**

**WHERE : Used in Automotive Industries**

**WHEN : At low Temperature**

**Detail requirements**

**High Level Requirements**

| **High Level Requirements** | **Description** |
| --- | --- |
| HLR1 | Microcontroller ||||
| HLR2 | Temperature Sensor |
| HLR3 | Heat Generation |
| HLR4 | Display |
| HLR5 | Software used |

**Low Level Requirements**

| **Low Level Requirements** | **Description** |
| --- | --- |
| HLR1\_LLR1 | ATmega328 ||||
| HLR2\_LLR1 | ADC |
| HLR2\_LLR2 | ADC with PWM-fast |
| HLR3\_LLR1 | Thermoelectric module |
| HLR4\_LLR1 | CRO and LED |
| HLR5\_LLR1 | Code Blocks with AVR GCC compiler |
| HLR5\_LLR2 | SimulIDE |
