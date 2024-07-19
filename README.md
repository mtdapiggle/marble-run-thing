# marble-run-thing
i wanted to learn CAD, didn't know what i wanted to make so i guess i decided on this
i also didn't read the bit about needing a github repo and STEP file exports + onshape link so uh... that's my bad (also i just realised i needed both STEP and STL files so uh... and i also found out through the arcade constitution (after session 7) that i have to upload the new STEP and STL files every hour/session, also what's a commit link??)
onshape link:
https://cad.onshape.com/documents/6775d66129ffc58f7396ec51/w/03b11f099dcbbd50d9e0f05e/e/6ea6d18276b03266ed36c889

**session 1:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719739734958409
![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/7279b1b8-024e-407b-a0c3-78d0d59c7808)
i already kinda knew how to sketch and extrude and that kind of stuff, but i had no clue how to make a spiral, i eventually had to search it up

**session 2:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719739734958409 
i did this session during school time in a free period i had, i made a thing where the ball can land on and then roll around, eventually dropping down a chute

**session 3:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719814792149569
i made a hole in the chute and tried to extend/make the chute better, i was able to get the bottom of the chute done but didn't really know how to connect it and loft wasn't entirely working 

**session 4:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719819362606659
after a while of trying to figure out what was wrong and why loft wasn't working, i decided to cut out the curves (circled in red)
![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/6dc980d3-e2c9-4705-944b-9faf14184243)
loft would now work, but i had another problem which was that the loft couldn't include the curves, which made the curves sort of stick out a lot, i tried to fix it with a fillet but it still looks weird. it looks really disconnected and i really don't like it.

**session 5:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719829442715359
i realised that i could use loft on the curves by selecting the sides (image included to help explain, sides circled in green) and then the bottom of the chute, it still looked a bit weird. then i realised that i didn't need to get rid of the curves, i just needed to select the faces in a different way.
sides image: ![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/dedb59e9-b4f4-4ae1-bbaf-5af75b60d093)
after selecting the sides first: ![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/0aed852e-1bf4-44cd-bc07-c16e327b504f)
after realising that i just needed to select one side before the other (i got rid of 1 sketch and 2 lofts): ![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/7a29f5c1-f729-4aed-8cd6-44911bee97a2)
i am much, much more pleased with the result, words cannot describe how happy i am after being able to get the result that i wanted. (i didn't expect to spend 3 hours on this bit) although, as a perfectionist i can't live without it being fully tangent with a fillet, so i filleted it. 
i also started on working on a chicane part of the marble run.

**session 6:** https://hackclub.slack.com/archives/C06SBHMQU8G/p1719905241795599 
the chicane was much harder than i thought, the spline tool was confusing and i eventually had to search up how to get out of the spline tool (which was double clicking the end point) then i thought that i shouldn't use the spline tool, since i thought that i could only move the curves through the points, but then i found  out that i could dimension the points on the spline. when i used the sweep tool, it didn't work. i got confused on what was wrong

**session 7:** 
i realised that when i used the sweep tool, some of the red shapes collided with each other (image added to help explain, red shapes colliding highlighted in blue) ![image](https://github.com/mtdapiggle/marble-run-thing/assets/174234024/ea3b38c7-cd1e-4310-81cb-28d4583c4750)
so i had to change the sketch and make the dimensions longer, and it worked so that's cool.
next, i started work on a way to make everything modular/you can connect them sort of like lego, not sure how i can do this considering that i had already cadded a bunch of stuff up without making it modular, so it could cause problems. i also didn't really know how to make them modular/connect, i was thinking of using slots and a pin or a bolt of some kind to link them together, but the bolt could slide out, so either i could make a way to lock the bolt/pin/cylinder in or i could think of another way to do it

**session 8:** 
i had a 2 week hiatus from hack club, during that 2 weeks i thought about ways to make it modular. 
![image](https://github.com/user-attachments/assets/75ae78b9-767c-46c4-9b62-c55b57934df2)
i decided to make slots that would fit into the other pieces. then i realised that i would have to cad these slots and the areas that they would fit in on every single piece, which i didn't want to do because i was lazy, but i had to do it because i had no other choice. there probably is a way that i could've done to make it more efficient. i then tried to make the hole so that i could fit a pin through the slots. then i realised that the slots were much too small and the diameter of the pin could be at most 3 mm. i decided to enlarge the entire track so i would have more space to make the slots bigger. 
![image](https://github.com/user-attachments/assets/911ccf47-0693-47e0-8cf8-7be7f0c8364b)
this caused many problems down the track, as the curvy chicane thing (which i don't think is a chicane but i'm not sure) broke and the cone also broke. 
![image](https://github.com/user-attachments/assets/0a2b8688-21f0-42ca-b8b4-1614e992a524)
i had to fix the loft and the circle that i had used to cut a hole in the cone
![image](https://github.com/user-attachments/assets/fd2152d3-7d7c-400f-980e-4b857183d888)
the circle looked a bit small, then i realised that i  hadn't adjusted it to the correct size, since i made the marble track larger. i corrected this and it's fine now. i also realised that i didn't really like how the sweep sort of stuck out from the back, so i made the area that i was going to sweep smaller
![image](https://github.com/user-attachments/assets/21112197-7c0f-48c1-ac68-d3a5a9eeac87)
then i realised that i shouldn't have done that, and it looks much worse now. 
![image](https://github.com/user-attachments/assets/d5c156d9-110c-4a5b-9199-a966ee5cd17a)
i used loft to try and fix it but it looks even worse somehow
![image](https://github.com/user-attachments/assets/87741bf1-32d6-45cf-a231-128c113493a9)
then i realised that i probably should use loft in some other way to pull it off. i extended the plane that i used to draw the cone to give me more space to use loft which caused a couple of problems, so i fixed them and pushed the sweep path guiding line further away from the spiral. 
![image](https://github.com/user-attachments/assets/b6f8c165-a96f-4723-b846-e4ed685c2073)
it broke. really badly.
![image](https://github.com/user-attachments/assets/d54e5927-6d4c-4465-bb98-f79bd5b94a4b)
i think the reason behind it was because sweep didn't work how i thought it worked. sweep starts at the face of the object and you can't offset it unlike extrudes or other things, so i had to create another plane and offset it. i had to add a line at the top so it became a shape
![image](https://github.com/user-attachments/assets/9f3a5b89-64a4-447f-82be-59853c032376)
i forgot to add the circle so it became a solid block. then i ran into the problem of the loft not working (the loft for the cone), it was an easy fix though
![image](https://github.com/user-attachments/assets/379a73f8-acf8-4458-8902-bec198bc1d39)
i realised that i wanted more space between the spiral and the cone so i extended it again, but i ended up with too little space for the cone so i had to push the cone's plane back by 12.5mm
![image](https://github.com/user-attachments/assets/b3f52123-508b-4ae5-b0dc-eec978b0ff50)
probably not what i wanted.... (it's definitely not what i want)

**session 9:**
i fixed the sketch/sweep path and it turns out fine now, i put a loft and now it looks like this:
![image](https://github.com/user-attachments/assets/7d5207bd-87cd-4558-8162-270b6c81ed0b)
i then put a loft between 2 faces (circled in black) to make it look better, it didn't turn out well so i just put a fillet.
then i moved back to the slots. i realised whilst exporting all of the stl and step files, i could simply just combine two parts in the assembly area and export them together as one piece, meaning that i could possibly make a section or a part, put them into assembly and fasten them together. (i probably didn't explain this very well, but i'll put some pictures to help.)
![image](https://github.com/user-attachments/assets/7436b444-066f-49df-9687-b01b3b3bcdfd)
there are 2 sections/parts in different colours. then i realised that i didn't change the size of the slots. i expanded the size of the slots to  be 10mm tall and 5mm wide, then i thought that it might be too big, i also added some tolerances onto the slots to help them fit. i tried to make a hole for the slots then realised that it'd still be too small,  but i didn't want to make the slots bigger again, so i thought about it for 10 minutes straight and decided to make rectangular holes instead, so it hopefully might be more secure as well. i wasn't sure on how much tolerance i needed, since i wanted it to be a press fit. i spent the rest of my time doing a bit of research on tolerances, and wasn't able to finish the slots.

**session 10:**
i started this session off by realising how many hours per day i would need to put in to get what i wanted, and suffice to say, it isn't efficient for me to keep on doing this marble run stuff because i'd  have to make design decisions, and i'd rather cad an FRC robot so i won't have to make design decisions, but i'll try to finish this up and  have it in a semi workable state.

i made the rectangular slots and the rectangle to go with it 
![image](https://github.com/user-attachments/assets/aec93220-c026-46a3-bb3d-94ac4349dfa4)
then i thought about how i wanted to mount the different parts.
i attempted to make some sort of arm extending out of a cylinder
![image](https://github.com/user-attachments/assets/6b3070c2-9fcd-4c50-b26b-aa9ed194fc0f)
i tried to do something like this
![image](https://github.com/user-attachments/assets/e688659e-1ee6-402f-8c88-2990474e10e8)
then i changed it and the fillet tool stopped working for some reason, it said that the current fillet radius resulted in invalid geometry, which i think is fair, but i couldn't change the radius for some reason. (uh turns out, when i was trying to change the radius, i made it 9.8 instead of 0.8, i love typos (i did it like 10 times in a row))
also i accidentally reloaded onshape, and it took me a long while to open up the sketch again
![image](https://github.com/user-attachments/assets/4ae96af2-5f9a-422b-8688-e49eb9044fa8)
kjsadkjfa;kjfas;k djjdlkjk;kjlajjd;kjlpiuoweji t twqqipuwtunvuvqiwempoc AHHHHHHHHHHHHHHHHHHHHHHH (it's been like this for 6 straight minutes please help)
![image](https://github.com/user-attachments/assets/4716d47f-82f6-4a88-9c0a-932defb3c293)
it's been like this for like 20 minutes now
