Clase 04
```
int potPin = A0;
int ledPin = 7;
int valorPot = 0;
int potMapeado = 0;
int tiempoParpadeo = 100;
void setup(){
  pinMode(ledPin,OUTPUT);
Serial.begin(9600);
}

void loop(){
  tiempoParpadeo = potMapeado;
  valorPot = analogRead(potPin);
  potMapeado = map(valorPot,0,1023,100,2000);
  Serial.println(tiempoParpadeo);
  digitalWrite(ledPin, HIGH);
  delay (tiempoParpadeo);
   digitalWrite(ledPin, LOW);
  delay (tiempoParpadeo);
  

}
```
