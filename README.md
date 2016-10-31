# hello-world-D
hey anthony, my code for arduino is here:

 #include <Servo.h>
Servo servo1; 
void setup() {
  // put your setup code here, to run once:
servo1.attach(9);
pinMode(13, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
servo1.write(180);
digitalWrite(13, HIGH);
delay(10000);
servo1.write(0);
digitalWrite(13, LOW);
delay(10000);
}
please comment thanks!
