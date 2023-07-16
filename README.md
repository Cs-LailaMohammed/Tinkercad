# Tinkercad
Turn on the lighting in the robot


//الكود لتشغيل إضاءة المصفوفة
// C++ code
//

int C1= 5;

int C2= 4;

int C3= 3;

int C4= 2;

int C5= 1;


int R1= 10;

int R2= 9;

int R3= 8;

int R4= 7;

int R5= 6;

int wait = 250;

void setup(){

  pinMode (C1,OUTPUT);
  
  pinMode (C2,OUTPUT);
  
  pinMode (C3,OUTPUT);
  
  pinMode (C4,OUTPUT);
  
  pinMode (C5,OUTPUT);
  
  pinMode (R1,OUTPUT);
  
  pinMode (R2,OUTPUT);
  
  pinMode (R3,OUTPUT);
  
  pinMode (R4,OUTPUT);
  
  pinMode (R5,OUTPUT);
}
  
  void loop(){
    colulrow1();}

void colulrow1(){

  digitalWrite (C1, HIGH);
  
  digitalWrite (C2, LOW);
  
  digitalWrite (C3, HIGH);
  
  digitalWrite (C4, LOW);
  
  digitalWrite (C5, HIGH);
  
  digitalWrite (R1, LOW);
  
  digitalWrite (R2, LOW);
  
  digitalWrite (R3, LOW);
  
  digitalWrite (R4, LOW);
  
  digitalWrite (R5, LOW);
  
  delay(5);
}
  
