---
share: true
---


# Erstes Programm
```c
# wird einmal beim Start ausgeführt
void setup (){
	pinMode(5,OUTPUT);
}

# wird immer wieder ausgeführt
void loop (){
	digitalWrite(5,HIGH);
	delay(1000);
	digitalWrite(5,LOW);
	delay(1000);
}
```
