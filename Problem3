int servoPin=21;
int buzzer =14;
int pirSensor= 12;
int value=0;
#include <ESP32Servo.h>
Servo pressureServo;
void setup(){
  pinMode(buzzer,OUTPUT);
  pinMode(pirSensor, OUTPUT);
  Serial.begin(9600);
  pressureServo.attach(servoPin);
  pressureServo.write(0);

}

void loop(){
  value=digitalRead(pirSensor);
  if(value==HIGH){
     digitalWrite(buzzer,HIGH);
     pressureServo.write(90);
     Serial.println("Motion is detected--> The door is open!!");

  }
  else{
    digitalWrite(buzzer,LOW);
    pressureServo.write(0);
    Serial.println("No Motion  detected--> The door is Closed!!");

  }
}
  
