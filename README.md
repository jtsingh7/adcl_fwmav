# adcl_fwmav

0. Following https://www.youtube.com/watch?v=LXgL850p7b0&ab_channel=Robocraze
1. Open Arduino IDE
2. Tools > Board > Board Manager: search "nano 33 BLE" and install "Arduino Mbed OS Nano Boards" (may have to do on non-campus wifi due to weird service unavailable message during download)
3. (Optional) Install libs for certain sensors: Tools > Manage Libraries > APDS9960 (Color sensor), HTS221 (temp/humidity), LPS22HB (barometer), LSM9DS1 (IMU), PDM (microphone, install its dependencies as well), tensorflow lite (ML)
4. Restart IDE after installs
5. Double tap sensor button before uploading code