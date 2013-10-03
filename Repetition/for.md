buildings
=========
  
void setup() {
  size(900, 400); 
  smooth();
     
}

void draw() {
  background(0); 
  
for ( int i= 0; i<3; i++) {
  fill(#E8AF82);
  int xPosition =i*300+200;
  rect( xPosition, 100, 210, 300 );

  fill(#FFFFFF);
  noStroke (); 
  for (int x= 0; x<4; x++) { 
    for (int y=0; y<4; y++){
   rect( x*50+20+xPosition, y*75+120, 25, 50);
  }
  }
  }
  //  for( int x=             {
  //rect(x,y,width, height)

  //}

  //for (init; test; update) { 
  // statements
  //} 
  //for (datatype element : array) { 
  // statements
}
