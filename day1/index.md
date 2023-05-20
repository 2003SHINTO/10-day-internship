# day-1
# day-2
# TINKER CADED 
. created acc
. created new circiut
. using tinker caded Led Glow Circuit in bread board
![alt hii](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-09%2012-36-53.png)
 # led cel
[tinker caded](https://www.tinkercad.com/things/a1ugtvcB2yg-ied-cel)
# day-3
 tinker caded
 .using logic gate AND Gate
 ![alt simulation](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-11%2010-35-35.png)
using tinkercade
 .using arduino led light biling
 ![alt simulation](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-11%2011-31-41.png)
  .using led light code
   ![alt codeing](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-11%2011-50-44.png)
     # using arduion led light chaser with code
     ![alt loading](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-11%2012-34-43.png)
  
 #USING arduion led chaser
 ![alt](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-15%2010-48-56.png)
     .using POT 
     ![ALT](https://github.com/2003SHINTO/10-day-internship/commit/f84cbd8df8bcb581e50f3194de1077cedf1184bc)
 7 _Sengmet
 ![ait](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-15%2014-40-59.png)
7_segament
```
// code// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}
void loop()
{
  digitalWrite(13, LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,HIGH);
  delay(1000); // Wait for 1000 millisecond(s
  digitalWrite(11,LOW);
  digitalWrite(12,LOW);
  digitalWrite(10,HIGH);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,LOW);
  digitalWrite(10,LOW);
  digitalWrite(8,HIGH);
  digitalWrite(11,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(7,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  delay(1000);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(13,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(10,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,HIGH);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(8,LOW);
  digitalWritte(7,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-20%2012-06-07.png
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  digitalWrite(8,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(13,LOW);
  digitalWrite(12,LOW);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  digitalWrite(8,LOW);
  digitalWrite(7,LOW);
  delay(1000);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(1000);
  
  delay(1000); // Wait for 1000 millisecond(s)
}
```
# DAY10 using tinkercade
QUICK BUZZER
quick buzzer code
```
const int buttonPin0 = 2;     // the number of the pushbutton pin
const int ledPin0 =  13;
const int buttonPin1 = 4;     // the number of the pushbutton pin
const int ledPin1 =  12;
const int buttonPin2 = 7;     // the number of the pushbutton pin
const int ledPin2 =  8; // the number of the LED pin

// variables will change:https://github.com/2003SHINTO/10-day-internship/blob/main/day1/assignment.md
int buttonState0 = 0;         // variable for reading the pushbutton status
int buttonState1 = 0; 
int buttonState2 = 0; 

void setup()
{
  // initialize the LED pin as an output:
  pinMode(ledPin0, OUTPUT);  // initialize the pushbutton pin as an input:
  pinMode(buttonPin0, INPUT);
  // initialize the LED pin as an output:
  pinMode(ledPin1, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin1, INPUT);
  // initialize the LED pin as an output:
  pinMode(ledPin2, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin2, INPUT);
}

void loop()
{
  // read the state of the pushbutton value:
  buttonState0 = digitalRead(buttonPin0);
   buttonState1 = digitalRead(buttonPin1);
   buttonState2 = digitalRead(buttonPin2);

  // check if the pushbutton is pressed. If it is, the buttonState is HIGH:
  if (buttonState0 == HIGH)
  {
    // turn LED on:
    digitalWrite(ledPin0, HIGH);
  }
  else if (buttonState1 == HIGH)
  { 
   digitalWrite(ledPin1, HIGH); 
  }
  else if (buttonState2 == HIGH)
  { 
   digitalWrite(ledPin2, HIGH); 
  } 
  else
  {
    // turn LED off:
    digitalWrite(ledPin0, LOW);
     digitalWrite(ledPin1, LOW);
     digitalWrite(ledPin2, LOW);
  }
}
```

![alt mkl](https://github.com/2003SHINTO/10-day-internship/blob/main/day1/Screenshot%20from%202023-05-20%2012-06-07.png)

#3Dprint
![alt](https://www.tinkercad.com/things/2eeYvlUcLXE-bodacious-wolt/edit)
