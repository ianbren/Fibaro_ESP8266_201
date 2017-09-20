# Fibaro_Esp8266_101 - Fibaro Virtual Device Code

- Create a new Virtual Device

In the "General" Section
- Add the IP and Address of the ESP8266

In the "Advanced" Section

- Add a button - call it "Test ESP8266"
- Add to Labels - leave them as the default names
- Add the code to the LUA section for the button

- Save the Device

To test
- Go to the "Advanced" tab and scroll down until the "Test ESP8266" button's code is seen.
- Press "Debug" for the "Test ESP8266" button
- Press "Start" to enable debugging
- In the new window, press "Test ESP8266"
- Esure there's text returned - it will be JSON if you are using the companion ESP8266 code


If there are issues 
- in a browser, check that there's some text returned when you select the IP address used in the "General" tab above.

