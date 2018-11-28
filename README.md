# Home-Automation-Clent

This is the companion Android application for my senior year project.This application recognizes the speech input, converts it to a command, and sends it over to the server I created on Raspberry Pi to control home appliances.


I created the server using Open Source platform ‘Jasper’ running on Raspberry Pi and improved its voice recognition by linking with ‘Pocketsphinx’ library. I created a custom grammar for a natural conversational style. 
The system sourced information from Wolfram Alpha and social network feeds; so it responded to questions such as, “Who’s the President of the US?” with “Barrack Obama”, and also read out latest emails, tweets and weather information. It also had an intruder detection feature using OpenCV library for computer vision. I linked the system to an Android app to provide remote, voice-controlled operation of appliances and other IoT features.
