int startX = 400;
  int endX = 400;
  int startY = 0;
  int endY = 0;
 
 
void setup(){
  size(800,800);
  strokeWeight(8);
 
}

void draw(){
 
  color c = (int)(Math.random()*5);
 
  if(c <= 1){
    c = color(255,192,203);
    stroke(c);
  }
  else if (c <= 2){
    c = color(255,182,193);
    stroke(c);
  }
  else if(c <= 3){
    c = color(255,105,180);
    stroke(c);
  }
  else if(c <= 4){
    c = color(255,20,147);
    stroke(c);
  }
 

 
 
  while(endY<=800){
    endX = startX + (int)(Math.random()*19)-9;
    endY = endY + (int)(Math.random()*10);
    line(startX, startY, endX, endY);
    startX = endX;
    startY = endY;
  }
 

  }

void  mousePressed(){
  startX = 400;
  endX = 400;
  startY = 0;
  endY = 0;
 
}
