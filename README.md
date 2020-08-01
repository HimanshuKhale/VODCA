# V.O.C.A
Voice Operated Computer Assistant. 

This is a novelty version of Apple's Siri. I have used pyttsx3 speech to text translator. And then fed the output in loop of if else and upon detection of certain keywords there are certain action which are preprogrammed. 


I have imported the following libraries: 
  1. pyttsx3
  2. speech_recognition
  3. datetime
  4. wikipedia
  5. webbrowser
  6. os
  7. smtplib
  8. pyaudio
  
  
The following are the keywords which are needed to be spoken followed by the results one can expect. 

1) "what is the time" :  #tells us the time 
2) "Open youtube" : #opens www.youtube.com in internet explorer. 
3) "open stackoverflow": # opens www.stackoverflow.com in internet explorer.
4) "open google" : #opens www.google.com in internet explorer. 
5) "Wikipedia ______":  #will read the first few lines of wikipedia search on the topic that follows "wikipedia"
6) "Mail to ____" : #takes a dictation and then sends it as an email to the mail id from the contact list. 
7) "Play music" : Plays the music from the directory one have programmed in. 


Kindly note: This is a zeroth form of this application, as I will be updating it with better 
