KProgrammer4 is an eeprom programmer that lets you write to 28c64 eeprom, 24c series eeprom (i.e. 24c256 - 4 pin io). Also, source bin file data is specifically via 24c eeprom to 28c64 eeprom, 28c64 eepom to 24c series eeprom, data file to either 28c64 eeprom or 24c series eeprom, terminal uoad data to either 28c64 or 24c series eeprom. Seven operating modes along with Switch register IO and terminal mode via arduino ide, putty, etc.

I liked beneater's design of using 74595 and 74165 chips. What I thought is that with adafruit mcp23017, the project has the ability for multiple dynamic pin mapping using the 28c64 eeprom as the first example.

version 1 uses a nodemcu v3 along with (4) 74595 and (1) 74165 with static pin mapping. An update to beneater's eeprom project with additional capabilities.

version 2 uses esp32, devkit1, along with (2) mcp23017 and dynamic pin mapping and additional capabilities.
