# RoboticsPerceptionWeek1AssignmentCode
Dolly_Zoom
as we all know that f = 100*(4-pos), so, once we get pos, we can fix f, thus, just two lines of code can resolve it:

pos = (H2*ratio*d1_ref - H1*d2_ref)/(H2*ratio - H1);

f = 100 * (4-pos);

you can find clue in the second pic, referenced in the first pic. 
I looked up several representation of dolly zoom, only find that the coursera courseware was the most confusing version, the figure above was interpreted from wikipedia and course of Illinois: 
https://courses.engr.illinois.edu/cs543/sp2011/lectures/Lecture%2002%20-%20Projective%20Geometry%20and%20Camera%20Models%20-%20Vision_Spring2011.pdf

