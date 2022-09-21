# SmartDoorBell
This the sample code for my smart doorbell project.
It uses a Haar cascade facial filter to detect the face of the visitor. For testing purposes we used a 3rd party android application to which embeds itself to our phone camera.
When it successfully detects the face, it sends the signal to Twilio. The program uses the Twilio API to send a message and an email to the user prompting that someone is at the door
