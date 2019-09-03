# Test Application for 4-20mA ADC (#53) Tibbit

This Tibbo BASIC demo application is fairly straight forward, the Tibbit outputs 15V and measures between 0~20mA, inside of the application, the values are converted into voltages, so 4mA is read as 0V while 20mA is 5V. In the case of an open circuit, the readout would be below -0.7V.

You will need:

- TPP2, TPP2(G2), TPP3, or TPP3(G2) board
- One Tibbit #53 (4-20mA)
- One Tibbit #20 (9 pin Terminal Block)
- One Tibbit #12 (+/-15V regulator)
- Optionally, one Tibbit #9 or #10 (12V->5V regulator)
- Optionally, one Tibbit #18 (power jack)