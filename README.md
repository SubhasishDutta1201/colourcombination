Project Title: Colour Combination using RGB LED and Fabric Pressure Sensors

About: Based on colour theory, we know that using the three primary colours ( green and blue), we can create a wide range of colours. Each primary colour uses 8 bits, with an integer value ranging from 0 255. Combining all three primary colours we can create 256^3= 16,777,216 colours. In this project, we will deal with a small range of colours specifically seven the three primary colours (green and blue), the three secondary colours (cyan and yellow) and white.

Materials Required

1. 15x15 Wooden Frame
2. EeonTex Conductive non-woven - the basis of any fabric pressure sensor
3. Non-conductive fabric - to cover the conductive fabric (pressure sensor)
4. Double-sided Iron on Adhesive - to attach the conductive fabric to the non-conductive fabric together.
5. Conductive thread - to make the connections
6. Thread and needle - to sew the fabrics together and to make the connections.
7. Clothing Iron - to iron on the fabric and the Iron on adhesive to be affixed to the conductive fabrics
8. Velostat - to separate the two conductive fabrics from physically touching each other in order to protect from electrostatic discharge.
8. Common Anode RGB LED - to visualize the sensed values, here the colours.
9. CR2032 Cell Battery - to power the entire circuit.
10. Sewable Cell Battery Holder
11. Multimeter and Crocodile Wires - to check the connections and functioning of the pressure sensors.

Implementation (A High Level View)

To make the three pressure sensors, 6 pieces each of conductive and non-conductive fabrics are cut in the desired shape and three velostats. Then all these fabrics are attached to each other as shown in the image: https://user-images.githubusercontent.com/67683277/86340210-dbda1a00-bc54-11ea-9f3e-b3eaf0242285.jpg [layered view]. Likewise, three such pressure sensors are created. Then the leads from the pressure sensors are connected to the three corresponding leads (R,G,B) of the RGB LED to control the colour feedback and the common anode lead to the positive terminal of the battery.  Pressing any of the three pressure sensors individually will trigger the LED to emit either red, green or blue colours. On pressing two of these three sensors together, the RGB LED will get triggered to emit either yellow, cyan or magenta and on pressing all three, the LED will emit white light. For further clarity on how the schematic and the working, follow https://user-images.githubusercontent.com/67683277/86343672-91a76780-bc59-11ea-970c-dac2f413a4b4.jpg. [schematic diagram and working]

References

[1] https://www.instructables.com/id/Flexible-Fabric-Pressure-Sensor/
[2] https://www.digikey.com/en/articles/how-to-drive-multicolor-leds
[3] https://www.youtube.com/watch?v=Qnoso-uHNfs&list=PL59E3463FF233187D&index=16
