# Tinkercad-servo-beginner-code
//makes the servo go continuously
#include <Servo.h>

// C++ code
//
Servo myservo;
void setup()
{
 myservo.attach(9);
}

void loop(){
 
myservo.write(2);
  delay(1000);
  myservo.write(90);
  delay(1000);
     myservo.write(180);
  delay(1000);
  myservo.write(90);
  delay(1000);
}
