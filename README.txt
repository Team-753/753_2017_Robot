This version of the code support vision processing to the point of recognizing the goal from, approximately, 
the distances that will be present in the competitions. In order for it to work, the template that is included
in this set of project files ("GreenTemplate.png" in the folder "templates") must be placed in the RoboRio's 
file system. To do this, tether the RoboRio to the computer via USB, and open the file explorer. Type
"ftp://roborio-753-frc.local/". Then, copy "GreenTemplate" and paste it into the "templates" folder inside of
the "C" folder on the root directory of the RoboRio.

Then it will probably work.

And you don't really need to do any of this if it is to the extra/old RoboRio, as I did that already.

Also, it turns out that the first 'X' position in the "Matches (Color Location 1)" display in the Vision
Processing.vi front panel is likely (emphasis on "likely"--I haven't yet had the opportunity to conduct thorough
tests) the actual center of the recognized object rather than one of its "bounding box" coordinates.


--Caleb Meyers
