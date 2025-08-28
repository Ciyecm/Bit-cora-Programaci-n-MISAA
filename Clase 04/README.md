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
```
int ledPin = 7;
int potPin = A0;
int intervalo = 1000;
bool estadoLed = 0;
int valorPot = 0;
int potMapeado = 0;
unsigned long tiempoActual = 0;
unsigned long tiempoAnterior = 0;
void setup(){
pinMode(ledPin,OUTPUT);
  Serial.begin(9600);
}

void loop(){
tiempoActual = millis();
  valorPot = analogRead(potPin);
  potMapeado = map(valorPot,0,1023,100,2000);
  intervalo = potMapeado;
  if (tiempoActual - tiempoAnterior > intervalo){
  estadoLed = !estadoLed;
    Serial.println("se cumple la condicion");
    tiempoAnterior = tiempoActual;
  } 
digitalWrite(ledPin, estadoLed);  
Serial.println(intervalo);
}
```
```
int ledPin = 9;
int potPin = A0;
int valorPot = 0;
int potMapeado = 0;
int intensidadLed = 0;



void setup(){
pinMode(ledPin,OUTPUT);
  Serial.begin(9600);
}

void loop(){
  valorPot = analogRead(potPin);
  potMapeado = map(valorPot,0,1023,0,255);
  intensidadLed = potMapeado;

analogWrite(ledPin, intensidadLed);  
Serial.println(intensidadLed);
}
```
