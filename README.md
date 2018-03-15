# digital-design
This is for the digital design project.
//this is the charactors code.
hide();
makeCircleGuy();
makeRectangleMan();

//This is used to make the man named circle guy.

function makeCircleGuy(){//This function was made by Mathew.
penUp();
moveTo(39,340);
penDown();
penRGB(250,0,0);
penWidth(15);
turnRight();
moveForward(50);
penUp();
moveTo(20, 315);
penRGB(242, 100, 100);
dot(50);
moveForward();
penWidth(15);
penRGB(250,0,0);
penDown();
moveForward(50);
circleEyes();
penUp();
moveTo(55, 327);
penRGB(125,0,0);
penWidth(15);
penDown();
moveForward();
turnLeft(35);
moveForward();
turnTo(360);
penRGB(203,128,13);
moveForward();
penRGB(230,230,230);
 for (var s = 25; s>0; s--){//this for loop is used so I can make the knife have a point.
    penWidth(s);
    moveForward(2);
  }
}

//This function is used to make the eyes of circle man.

function circleEyes(){//This function was made by Mathew.
  penUp();
  moveTo(48, 302);
  penWidth(10);
  dot(15);
  turnLeft();
  moveForward(10);
  penRGB(255,255,255);
  dot(5);
}

function makeRectangleMan(){//This function was made by Mathew.
  penUp();
  moveTo(300, 350);
  penRGB(0,0, 255);
  turnTo(360);
  penWidth(50);
  penDown();
  makeRectangle(75, 50);
  penUp();
  moveTo(248, 285);
  turnRight();
  penWidth(10);
  penRGB(255,255,255);
  penDown();
  makeRectangle(20, 5);
  penUp();
  moveTo(264, 376);
  penRGB(0,0,255);
  penDown();
  turnRight();
  penWidth(15);
  moveForward();
  penUp();
  moveTo(290, 376);
  penDown();
  moveForward();
  penUp();
  moveTo(239, 317);
  turnTo(270);
  penDown();
  penRGB(0,0,40);
  moveForward(25);
  turnRight(35);
  moveForward();
  turnTo(360);
  penRGB(203,128,13);
  moveForward(20);
  penRGB(230,230,230);
  for (var s = 25; s>0; s--){//this for loop is used so I can make the knife have a point.
    penWidth(s);
    moveForward(2);
  }
}

//This function makes a rectangle specificaly used for rectangle man's head and body.

function makeRectangle(length, width){//This function was made by Mathew.
 for (var i = 0; i < 4; i++){
  moveForward(length);
  turnLeft();
  moveForward(width);
  turnLeft();
 }
}
