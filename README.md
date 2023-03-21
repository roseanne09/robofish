# robofish-esp32cam

This code controls a fish using servos and streams video through an ESP32CAM. Additionally, an LED is used to improve the brightness underwater for clearer imaging.
To improve computational efficiency and reduce the load on the ESP32, the hardware has been shifted to another board. Therefore, this code only turns on/off the corresponding pins based on the commands received from the webpage. For full functionality, you will need to connect another board and make the necessary changes.
