# IOT-Blockchain
A IOT Sensor data/temperature control for a ASIC mine (building inside a building)- on blockchain - because hey, why not.

This is a system designed for a (room) within a building. Referred to in this document as a room within a shop.

Background: I have a 30'x30'x12'(h) shop/Garage. (Diagrams 1.1, 1.2) //will be added//

Within that Shop, I have built a double walled structure to first and foremost contain as much noise as possible to the mining room, and have peace and quiet in the shop. The mining room has a cold room and hot room.

The outside temperature varies from seasonal lows of -35 Degrees Celcius in winter to +30 Degrees celcius in Summer.

Cold room has 18" Cold air intake with var speed fan in cold room with damper(in shop, pre fan) to balance fresh air(cold) and recirculation of shop air. Diagram 1.3

Hot room has a 16" Exhaust to outside, and a 14" exhaust to shop to accomodate the wide variance in outside temperatures from season to season.




The aim of the project is to satisfy the following:


1.The noise needs to be contained by the room. Absolutely! I can't stand noise. (ASIC's = Noise++).
2.The temperature of the mining cold room, hot room, and temperature of the shop each need to be monitored and controlled.
3.The various room pressures need to be maintained according to ideal pressures.



Phase 1: Using multiple variable speed fans, temperature sensors, dampers,and controllers, establish a code suitable for Arduino to control the system to maintain shop at 70 Degrees, while having the cold isle within acceptable parameters.

Phase 2: Log the data on blockchain as an example of IOT controlled environment that can be verified and monitored by others. As a prototype of how IOT sensor data can interact with the blockchain in a useful way.

List of controlled fans:
18" Intake fan (PWM Control)
14" Shop Exhaust fan (PWM Control)
16" Exhaust (220v var speed, no PWM Control. Can rig servo to turn knob on fan control)
8" shop exhaust fan (No PWM control. Can rig servo to turn knob on fan control)
