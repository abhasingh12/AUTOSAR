
![image](https://github.com/abhasingh12/AUTOSAR/assets/153552335/978bfca1-86b5-4353-bd2d-8316a38585fd)




**TEMPERATURE SENSOR ABSTRACTION LAYER:**

Uses the ADC Driver from MCAL using standardised interfaces to trigger ADC.
ADC Driver call-back once conversion is completed.
Results are read back by the abstraction and converted to temperature.

**H-BRIDGE ABSTRACTION:**

Uses DIO Driver from MCAL using standardised interfaces to write to DIO ports.
DIO ports are written directly from actuating point, to switch ON or OFF the motor
Can further be extended to Read back Motor status feedback from another DIO ports.
