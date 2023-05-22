# SAFEME--A_Crisis-Alerting_Device
With all the technology available to us in recent times, it's not hard to build a safety device for users that will not only generate an emergency alarm but also send a message to your friends, family, or
other concerned individuals. Here we will build a band that can be worn by anyone, using which they can inform the police or anyone, using SOS emergency SMS along with their current location.
Using this information, the police or volunteer will be able to save the victim from the location. 
For this, we are using an Arduino, which can be interfaced with a GSM and GPS module for sending SMS alerts and getting the location coordinates. We have also used an RF transmitter and receiver
module for wireless communication between the band and the receiving device with GPS/GSM. While sending the alert to the registered number, we would be using AES - 256 for the bulk encryption
of the text messageTo ensure that the transmission of the text is safe and secure, we'll be using ECDH ephemeral as our primary key exchange algorithm.
While retrieving the text from the database for the receiver, the message would be decrypted and displayed to the receiver.
