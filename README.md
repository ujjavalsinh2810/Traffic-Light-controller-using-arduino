/Using Arduino to make a lane traffic signal light.

void setup() {
// configure the output pins
  pinMode(2,OUTPUT);
  pinMode(3,OUTPUT);
  pinMode(4,OUTPUT);
  pinMode(5,OUTPUT);
  pinMode(6,OUTPUT);
  pinMode(7,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(13,OUTPUT);

}
void loop() 
{
   //enables the 1st set of signals

  digitalWrite(2,1); 
  digitalWrite(5,1); 
  digitalWrite(8,1);
  digitalWrite(13,1);
  digitalWrite(3,0);
  digitalWrite(4,0);  
  digitalWrite(6,0);
  digitalWrite(7,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(11,0);
  digitalWrite(12,0);
  delay(5000);
 

//enables the yellow lights
  digitalWrite(2,1);
  digitalWrite(5,1);
  digitalWrite(8,1);
  digitalWrite(12,1);
  digitalWrite(3,0); 
  digitalWrite(4,0);
  digitalWrite(6,0);
  digitalWrite(7,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(11,0);
  digitalWrite(13,0);
  delay(2500);
  
 //enables the 2nd set of signals
  digitalWrite(2,1);
  digitalWrite(5,1);
  digitalWrite(10,1);
  digitalWrite(11,1);
  digitalWrite(3,0);
  digitalWrite(4,0);
  digitalWrite(6,0);  
  digitalWrite(7,0);
  digitalWrite(8,0);
  digitalWrite(9,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(5000);
 
  //enables the yellow lights
  digitalWrite(2,1);
  digitalWrite(5,1);  
  digitalWrite(9,1);
  digitalWrite(11,1);
  digitalWrite(3,0);
  digitalWrite(4,0);
  digitalWrite(7,0);
  digitalWrite(8,0);
  digitalWrite(10,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(2500); 

 //enables the 3rd set of signals
  digitalWrite(2,1);
  digitalWrite(7,1);
  digitalWrite(8,1);
  digitalWrite(11,1);  
  digitalWrite(3,0);
  digitalWrite(4,0);
  digitalWrite(5,0);
  digitalWrite(6,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(5000);

  //enables yellow light

  digitalWrite(2,1);
  digitalWrite(6,1);
  digitalWrite(8,1);
  digitalWrite(11,1);  
  digitalWrite(3,0);
  digitalWrite(4,0);
  digitalWrite(5,0);
  digitalWrite(7,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(2500);


 //enables the 4th set of signals
 
  digitalWrite(4,1);
  digitalWrite(5,1);
  digitalWrite(8,1);
  digitalWrite(11,1);  
  digitalWrite(2,0);
  digitalWrite(3,0);
  digitalWrite(6,0);
  digitalWrite(7,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(5000);

  
  //enables yellow light


  digitalWrite(3,1);
  digitalWrite(5,1);
  digitalWrite(8,1);
  digitalWrite(11,1);  
  digitalWrite(2,0);
  digitalWrite(4,0);
  digitalWrite(6,0);
  digitalWrite(7,0);
  digitalWrite(9,0);
  digitalWrite(10,0);
  digitalWrite(12,0);
  digitalWrite(13,0);
  delay(2500);



}
