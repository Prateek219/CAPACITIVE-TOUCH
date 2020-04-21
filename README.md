# DARLINGTON AMPLIFIER BASED CAPACITIVE TOUCH SENSOR
####                                                 Chirag Sangani
_Abstract: To develop a capacitive touch sensor by the use of commonly available Bipolar Junction Transistors (BJTs) in an
amplifier configuration._

Capacitive touch sensors are very popular compared to resistive touch sensors due to higher sensitivity and the ability to
implement multi-touch sensors. Such sensors need to be touched with capacitive material such as human skin. This project
implements such a single-touch sensor using common BJTs and a microcontroller unit (Atmel AVR).

Touching the interface will cause minute current to flow across the base junction of the first amplifier. The square-amplified
current flowing through the collector junction of the second amplifier will cause a drop in the potential Vo which can be digitally
detected by the microcontroller unit.

### CODE
```Arduino

DDR = 0;
PORT = 1;
int i = 0;
while(i < 10000)
{
if(PIN == 0)
break;
i = i + 1;
}
if(i == 10000)
return false;
else
return true;
```
