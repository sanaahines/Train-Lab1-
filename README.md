// Train-Lab1-
size(600,425);               // The size of the window is 500x500 pixels
strokeWeight(5);           // Rectangle border: 5 pixels wide
background(220,181,252);   // Light Purple

stroke(57,173,12);       //green outline
fill(71,5,118);         //  purple fill
rect(180,150,280,160);  // 280x160 rectangle.  Upper left at (x=20,y=20)

stroke(57,173,12);       //green outline
fill(0,118,5);         // dark green fill
beginShape();
vertex(460,150);  // Top line green triangle
vertex(600,310);  // Bottom line green triangle
vertex(460,310);  // Straight line green triangle
endShape(); // green triangle



stroke(168, 8,250);      //purple border
fill(71,5,118);        // dark purple fill
rect(10,10,170,300);      // 170x300 rectangle.  Upper left at (x=10,y=10)
stroke(57,173,12);       //green outline
fill(36,118,5);         // dark green fill
rect(40,40,100,100);      // 100,100 rectangle.  Upper left at (x=40,y=40)(window rectangle)



stroke(57,173,12);       //green outline
fill(71,5,118);        // dark purple fill
ellipseMode(CORNERS);
ellipse(20,280,170,420);      //first circle 
ellipseMode(CORNERS);
ellipse(325,315,225,420);   //second circle
ellipseMode(CORNERS);
ellipse(450,315,350,420);   //third circle


ellipseMode(CENTER);
ellipse(95,355,70,70);     // fourth circle center x=95 y=355 
stroke(57,173,12);       //green outline
fill(36,118,5);         // dark green fill
rect(60,360,370,15);      // 370x15 rectangle.  Upper left at (x=60,y=360)



beginShape();
vertex(90,200); //1st Point
vertex(100,225); // 2nd Point
vertex(130,225); //3rd point
vertex(110,240); //4th point
vertex(120,270);  // 5th point
vertex(90,255);  // 6th point
vertex(65,270);  // 7th point
vertex(70,240);  // 8th point
vertex(50,225);  // 9th point
vertex(80,225);  // 10th point
vertex(90,200); //1st Point
endShape();
//window circle
fill(15,179,242);
arc(140, 140, 150, 150,PI,HALF_PI+PI); //arc in small rectangle
