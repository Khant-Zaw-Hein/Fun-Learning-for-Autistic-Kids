# How to run this Android project locally
1. Install Android Studio as the IDE to view the code and run the code on an emulator or actual device
2. When running code on an emulator, choose an emulator that has an Android version (29-32) that the android code can compile and run on
3. Ensure that the SpringBoot Server is already running. For flask server, if testing localhost, need to ensure flask server is running. If not, default configuration is routed to flask server hosted on google cloud.
4. With emulator, the learn facial expression use case cannot be tested.
5. In order to test the learn facial expression use case, this project has to be run at a physical android phone device with Android version 29-32, so that the in-app camera can be activated to take photos to send to Flask server for prediction of emotion. 
6. Before testing, make sure to update the IP address under the HOST_ADDRESS in strings.xml file 
(e.g. current: <string name="HOST_ADDRESS">http://192.168.1.137:8083/</string>)
7. And if testing on physical phone device, please ensure phone and laptop is connected to the same wifi and update the IP address accordingly when change wifi connection.



