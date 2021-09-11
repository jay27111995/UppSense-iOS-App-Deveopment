# iOS App for UppSense H1N1 Biosensor
Medical app developed for InfluSense 1.0 - H1N1 Biosensor: developed by UppSense, Uppsala University, Sweden 

UpSense team and project info:
Website: https://sensusuppsala.com/
LinkedIn: https://www.linkedin.com/company/uppsense/mycompany/
Facebook: https://www.facebook.com/UppsalaSensUs
Instagram: https://www.instagram.com/uppsalasensus/ 
Sensus Competition: https://digital.sensus.org/teams/4

### Read team results document in repo for more info. 

Description: 
The main purpose of the app is to display the H1N1 test result from the biosensor to the user. 
The design implemented works as follows: 
* A QR code displayed on the app will indicate the BLE(Bluetooth Low Energy) UUID(Universally Unique Identifier) to connect to the phone. 
* The QR code is read by the biosensor (RaspberryPI + Camera), then connects to the app via BLE and sends the result. For code on the biosensor visit: https://github.com/jay27111995/UppSense2021-Embedded-Control
* Additionally, the app also saves the current location of the test, displays to the user and saves it on the phone.   


