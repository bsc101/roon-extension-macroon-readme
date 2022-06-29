# Roon Extension: macro.on

**macro.on** lets you define macros for your Roon music player. A macro is a sequence of macro steps, for example:
set volume, play internet radio station, pause playback, and so on...

A macro can be executed manually by using the **macro.on** web interface or by using the **macro.on** Android app.
You can also run macros by sending http GET requests, this way you can run macros from any other software that is capable of 
sending http GET requests.

Furthermore, macros can be run automatically by using triggers. Examples for triggers are: a certain point in time (alarm clock),
a Roon endpoint appears (autoplay after power on), and so on... 

Then, you can assign constraints to a trigger to restrict the execution of a macro. A simple example would be an alarm clock that runs
at 6am in the morning, but only on Mondays through Fridays. A more advanced example would an autoplay functionality with 
different audio sources played at different times of day (news radio station in the morning, music playlist in the evening).
