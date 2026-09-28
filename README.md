# LED-Blinking


A basic Arduino project that makes an LED blink ON and OFF at a fixed interval.

# Components

* Arduino Uno
* LED
* Breadboard
* Jumper wires


# Code

```cpp
int pin = 8 ;

void setup() {
  pinMode(pin,OUTPUT) ;
}

void loop() {
  digitalWrite(pin,1) ;
  delay(500) ;
  digitalWrite(pin,0) ;
  delay(500) ;
}
```

# Demo



[![LED Blinking Demo](https://img.youtube.com/vi/6ODHzes-b6w/0.jpg)](https://www.youtube.com/shorts/6ODHzes-b6w)



# Project Level

**Beginner**

# Author

SAYEM
