# automatic-humidifier
Automatic humidifier app for Smarthings.
As usual copy the code over to Smartthings IDE and profit

So I am not a coder, I haven't written code since 2001.  Forgive the crap coding here.
This app takes the outside temp based off of weather underground, or your own personal temp sensor
and then does a slope intercept type thing on that to derive an ideal indoor humidity setting
this compares to the reading of the indoor humidity sensor and turns your humidifier on or off.  
that is it in a nutshell.  

I have put into this app as many failsafes as I can think of without bloating it too much
so that if a sensor drops out it will turn off the humidifier at the next poll. 
Feel free to recode this to be a better app.  Again my coding sucks.

I have used this for the last two months as a beta test and it has worked well for me.  One warning, this is a cloud app.
If you lose internet connection AFTER the humidifier starts it will continue to run until either the net comes back
or you turn it off which could result in very high humidity levels during that time.  

This is more or less something I did for myself, I am not likely to maintain the app or make any notable changes at this point unless it 
stops doing what I want it to do.  I felt the app might benefit others so I made it more user friendly and adjustable and put it out there for others to build on or use.  
