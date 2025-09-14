Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

Part 2

Q21. It is because in the source code of the class NumberDisplay, the value is set to 0.

Q22. setTime changes the value in the field displayString and the timeTick increments it by 1 is the minutes.

Q23. I would have to increment it 60 times, since the limit for the NumberDisplay(minutes) is 60, which rolls
     over to 0 and increments the NumberDisplay(hours) by 1.

Q24. NumberDisplay digit = new NumberDisplay(10); 

Q25. Rectangle window = new Rectangle(int height, int width)
{
    window.setValue(height);
    window.setValue(widht);
    
}

Q26. The second constructor creates a new ClockDisplay where you can enter a custom value for hours and minutes,
     which will then start at that time.
     
Q27. similarities: - same constructor header names
                   - same assignments
                   - access modifier
     
     difference: The second constructor has parameters, which is why is doesn't have updateDisplay, and instead it has 
                 setTime(hour, minute); because it is a setter.
                 
Q28. p1.print("filename1", true);
     p1.print("filename2", false);
     
     int delay = p1.getStatus(5);
     int delay = p1.getStatus(10);
     
Q29. roof = NewTriangle();
     roof.changeSize(60,180)
     roof.moveHorizontal(20);
     roof.moveVertical(-60); 
     roof.makeVisible();
     roof.changeColor("black");
     roof.changeColor("green");\
     
Q30. roof.changeSize(60, 180);
     roof.moveHorizontal(20);
     roof.moveVertical(-60);
     roof.makeVisible();
     
Q31. No

Q32. 8 % 3 = 2

Q33. if the negative number is on the left hand, the result will be a negative number.
     if the negative number is on the right hand, the result will be a positive number.
     if both numbers are negative, the result will be a negative number.
     
Q34. All whole numbers

Q35. All whole numbers

Q36 and Q37: 

Q52. Yes it does give the same results as the previous version.


          